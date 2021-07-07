# Neovim Native LSP - Yarn PnP (v2) & TypeScript Language Server

This is a repo I've been using to debug and demo neovim's native LSP implementation with a yarn v2 PnP project and the TypeScript language server.

## Requirements

- [Neovim 0.5](https://neovim.io/) with plugins
  - [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) - config to use TS language server with Neovim's native LSP
  - [vim-rzip](https://github.com/lbrayner/vim-rzip) - open yarn PnP's `.zip` files
- [typescript-language-server](https://github.com/theia-ide/typescript-language-server) installed somewhere
  - by default nvim-lspconfig will want it globally installed
- [yarn](https://yarnpkg.com/) package manager
  - v1 needs to be globally installed

## Aims

- Support running of tsserver in yarn v2 projects
  - https://github.com/theia-ide/typescript-language-server/pull/220
- Support opening of yarn archive files for things like go-to-definition, etc.
  - https://github.com/neovim/neovim/pull/14959
  - https://github.com/lbrayner/vim-rzip/issues/15
- Support Yarn PnP virtual files
  - https://github.com/yarnpkg/berry/pull/3041
