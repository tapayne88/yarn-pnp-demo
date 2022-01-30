# Neovim Native LSP - Yarn PnP v3 & TypeScript Language Server

This is a repo I've been using to debug and demo neovim's native LSP implementation with a yarn Plug'n'Play project and the TypeScript language server.

## Branches

Checkout the different branches to run.

- [`yarn-v2`](https://github.com/tapayne88/yarn-pnp-demo/tree/yarn-v2)
- [**`yarn-v3`**](https://github.com/tapayne88/yarn-pnp-demo/tree/yarn-v3)

## Requirements

- [Neovim >=0.5](https://neovim.io/) with plugins
  - [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) - config to use TS language server with Neovim's native LSP
- [typescript-language-server](https://github.com/theia-ide/typescript-language-server) installed somewhere
  - `0.9.5` offers best support - prior to this some version of a snippet is required, check https://github.com/lbrayner/vim-rzip/issues/15
  - by default nvim-lspconfig will want it globally installed
- [yarn](https://yarnpkg.com/) package manager
  - v1 needs to be globally installed

## Aims

- Support running of tsserver in yarn PnP projects
  - https://github.com/theia-ide/typescript-language-server/pull/220
- Support opening of yarn archive files for things like go-to-definition, etc.
  - https://github.com/neovim/neovim/pull/14959
- Support Yarn PnP virtual files
  - https://github.com/yarnpkg/berry/pull/3041
