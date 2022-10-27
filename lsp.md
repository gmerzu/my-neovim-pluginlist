# Table of Contents

- [Table of Contents](#table-of-contents)
  - [LSP](#lsp)
    - [LSP Installer](#lsp-installer)
    - [LSP Feature Extension UI](#lsp-feature-extension-ui)
      - [Diagnostics](#diagnostics)
      - [Definition, Reference](#definition-reference)
      - [Code action](#code-action)
      - [Hint](#hint)
      - [Hover Doc](#hover-doc)
      - [Rename](#rename)
    - [LSP Status](#lsp-status)
    - [Local LSP Config](#local-lsp-config)
  - [Disable/Enable](#disableenable)
  - [Pre-configuration](#pre-configuration)
  - [Backwards Compatibility](#backwards-compatibility)

## LSP

- [neovim/nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) ![](https://img.shields.io/github/stars/neovim/nvim-lspconfig) ![](https://img.shields.io/github/last-commit/neovim/nvim-lspconfig) ![](https://img.shields.io/github/commit-activity/y/neovim/nvim-lspconfig)

### LSP Installer

- [williamboman/mason.nvim(lsp installer)](https://github.com/williamboman/mason.nvim) ![](https://img.shields.io/github/stars/williamboman/mason.nvim) ![](https://img.shields.io/github/last-commit/williamboman/mason.nvim) ![](https://img.shields.io/github/commit-activity/y/williamboman/mason.nvim)
  - [williamboman/mason-lspconfig.nvim](https://github.com/williamboman/mason-lspconfig.nvim) ![](https://img.shields.io/github/stars/williamboman/mason-lspconfig.nvim) ![](https://img.shields.io/github/last-commit/williamboman/mason-lspconfig.nvim) ![](https://img.shields.io/github/commit-activity/y/williamboman/mason-lspconfig.nvim)
- [williamboman/nvim-lsp-installer](https://github.com/williamboman/nvim-lsp-installer) ![](https://img.shields.io/github/stars/williamboman/nvim-lsp-installer) ![](https://img.shields.io/github/last-commit/williamboman/nvim-lsp-installer) ![](https://img.shields.io/github/commit-activity/y/williamboman/nvim-lsp-installer)
- [lspcontainers/lspcontainers.nvim](https://github.com/lspcontainers/lspcontainers.nvim) ![](https://img.shields.io/github/stars/lspcontainers/lspcontainers.nvim) ![](https://img.shields.io/github/last-commit/lspcontainers/lspcontainers.nvim) ![](https://img.shields.io/github/commit-activity/y/lspcontainers/lspcontainers.nvim)
- [dundalek/lazy-lsp.nvim](https://github.com/dundalek/lazy-lsp.nvim) ![](https://img.shields.io/github/stars/dundalek/lazy-lsp.nvim) ![](https://img.shields.io/github/last-commit/dundalek/lazy-lsp.nvim) ![](https://img.shields.io/github/commit-activity/y/dundalek/lazy-lsp.nvim)

### LSP Feature Extension UI

- [kkharji/lspsaga.nvim](https://github.com/kkharji/lspsaga.nvim) ![](https://img.shields.io/github/stars/kkharji/lspsaga.nvim) ![](https://img.shields.io/github/last-commit/kkharji/lspsaga.nvim) ![](https://img.shields.io/github/commit-activity/y/kkharji/lspsaga.nvim)
- [glepnir/lspsaga.nvim](https://github.com/glepnir/lspsaga.nvim) ![](https://img.shields.io/github/stars/glepnir/lspsaga.nvim) ![](https://img.shields.io/github/last-commit/glepnir/lspsaga.nvim) ![](https://img.shields.io/github/commit-activity/y/glepnir/lspsaga.nvim)
- [folke/trouble.nvim](https://github.com/folke/trouble.nvim) ![](https://img.shields.io/github/stars/folke/trouble.nvim) ![](https://img.shields.io/github/last-commit/folke/trouble.nvim) ![](https://img.shields.io/github/commit-activity/y/folke/trouble.nvim)
  - [folke/lsp-colors.nvim](https://github.com/folke/lsp-colors.nvim) ![](https://img.shields.io/github/stars/folke/lsp-colors.nvim) ![](https://img.shields.io/github/last-commit/folke/lsp-colors.nvim) ![](https://img.shields.io/github/commit-activity/y/folke/lsp-colors.nvim)
  - [EthanJWright/toolwindow.nvim](https://github.com/EthanJWright/toolwindow.nvim) ![](https://img.shields.io/github/stars/EthanJWright/toolwindow.nvim) ![](https://img.shields.io/github/last-commit/EthanJWright/toolwindow.nvim) ![](https://img.shields.io/github/commit-activity/y/EthanJWright/toolwindow.nvim)
- [ray-x/navigator.lua](https://github.com/ray-x/navigator.lua) ![](https://img.shields.io/github/stars/ray-x/navigator.lua) ![](https://img.shields.io/github/last-commit/ray-x/navigator.lua) ![](https://img.shields.io/github/commit-activity/y/ray-x/navigator.lua)
- [gfanto/fzf-lsp.nvim](https://github.com/gfanto/fzf-lsp.nvim) ![](https://img.shields.io/github/stars/gfanto/fzf-lsp.nvim) ![](https://img.shields.io/github/last-commit/gfanto/fzf-lsp.nvim) ![](https://img.shields.io/github/commit-activity/y/gfanto/fzf-lsp.nvim)
- [RishabhRD/nvim-lsputils](https://github.com/RishabhRD/nvim-lsputils) ![](https://img.shields.io/github/stars/RishabhRD/nvim-lsputils) ![](https://img.shields.io/github/last-commit/RishabhRD/nvim-lsputils) ![](https://img.shields.io/github/commit-activity/y/RishabhRD/nvim-lsputils)

#### Diagnostics

- [jose-elias-alvarez/null-ls.nvim(Diagnostics)](https://github.com/jose-elias-alvarez/null-ls.nvim) ![](https://img.shields.io/github/stars/jose-elias-alvarez/null-ls.nvim) ![](https://img.shields.io/github/last-commit/jose-elias-alvarez/null-ls.nvim) ![](https://img.shields.io/github/commit-activity/y/jose-elias-alvarez/null-ls.nvim)
- [onsails/diaglist.nvim](https://github.com/onsails/diaglist.nvim) ![](https://img.shields.io/github/stars/onsails/diaglist.nvim) ![](https://img.shields.io/github/last-commit/onsails/diaglist.nvim) ![](https://img.shields.io/github/commit-activity/y/onsails/diaglist.nvim)
- [lithammer/nvim-diagnosticls](https://github.com/lithammer/nvim-diagnosticls) ![](https://img.shields.io/github/stars/lithammer/nvim-diagnosticls) ![](https://img.shields.io/github/last-commit/lithammer/nvim-diagnosticls) ![](https://img.shields.io/github/commit-activity/y/lithammer/nvim-diagnosticls)
- [kaputi/e-kaput.nvim](https://github.com/kaputi/e-kaput.nvim) ![](https://img.shields.io/github/stars/kaputi/e-kaput.nvim) ![](https://img.shields.io/github/last-commit/kaputi/e-kaput.nvim) ![](https://img.shields.io/github/commit-activity/y/kaputi/e-kaput.nvim)
- [Mofiqul/trld.nvim](https://github.com/Mofiqul/trld.nvim) ![](https://img.shields.io/github/stars/Mofiqul/trld.nvim) ![](https://img.shields.io/github/last-commit/Mofiqul/trld.nvim) ![](https://img.shields.io/github/commit-activity/y/Mofiqul/trld.nvim)
- [Maan2003/lsp_lines.nvim](https://github.com/Maan2003/lsp_lines.nvim) ![](https://img.shields.io/github/stars/Maan2003/lsp_lines.nvim) ![](https://img.shields.io/github/last-commit/Maan2003/lsp_lines.nvim) ![](https://img.shields.io/github/commit-activity/y/Maan2003/lsp_lines.nvim)
- [Kasama/nvim-custom-diagnostic-highlight](https://github.com/Kasama/nvim-custom-diagnostic-highlight) ![](https://img.shields.io/github/stars/Kasama/nvim-custom-diagnostic-highlight) ![](https://img.shields.io/github/last-commit/Kasama/nvim-custom-diagnostic-highlight) ![](https://img.shields.io/github/commit-activity/y/Kasama/nvim-custom-diagnostic-highlight)
- [cseickel/diagnostic-window.nvim](https://github.com/cseickel/diagnostic-window.nvim) ![](https://img.shields.io/github/stars/cseickel/diagnostic-window.nvim) ![](https://img.shields.io/github/last-commit/cseickel/diagnostic-window.nvim) ![](https://img.shields.io/github/commit-activity/y/cseickel/diagnostic-window.nvim)
- [zbirenbaum/neodim](https://github.com/zbirenbaum/neodim) ![](https://img.shields.io/github/stars/zbirenbaum/neodim) ![](https://img.shields.io/github/last-commit/zbirenbaum/neodim) ![](https://img.shields.io/github/commit-activity/y/zbirenbaum/neodim)
- [WhoIsSethDaniel/toggle-lsp-diagnostics.nvim](https://github.com/WhoIsSethDaniel/toggle-lsp-diagnostics.nvim) ![](https://img.shields.io/github/stars/WhoIsSethDaniel/toggle-lsp-diagnostics.nvim) ![](https://img.shields.io/github/last-commit/WhoIsSethDaniel/toggle-lsp-diagnostics.nvim) ![](https://img.shields.io/github/commit-activity/y/WhoIsSethDaniel/toggle-lsp-diagnostics.nvim)
- [casonadams/simple-diagnostics.nvim](https://github.com/casonadams/simple-diagnostics.nvim) ![](https://img.shields.io/github/stars/casonadams/simple-diagnostics.nvim) ![](https://img.shields.io/github/last-commit/casonadams/simple-diagnostics.nvim) ![](https://img.shields.io/github/commit-activity/y/casonadams/simple-diagnostics.nvim)
- [stefanwatt/lsp-lines.nvim](https://github.com/stefanwatt/lsp-lines.nvim) ![](https://img.shields.io/github/stars/stefanwatt/lsp-lines.nvim) ![](https://img.shields.io/github/last-commit/stefanwatt/lsp-lines.nvim) ![](https://img.shields.io/github/commit-activity/y/stefanwatt/lsp-lines.nvim)

#### Definition, Reference

- [rmagatti/goto-preview](https://github.com/rmagatti/goto-preview) ![](https://img.shields.io/github/stars/rmagatti/goto-preview) ![](https://img.shields.io/github/last-commit/rmagatti/goto-preview) ![](https://img.shields.io/github/commit-activity/y/rmagatti/goto-preview)
- [ojroques/nvim-lspfuzzy](https://github.com/ojroques/nvim-lspfuzzy) ![](https://img.shields.io/github/stars/ojroques/nvim-lspfuzzy) ![](https://img.shields.io/github/last-commit/ojroques/nvim-lspfuzzy) ![](https://img.shields.io/github/commit-activity/y/ojroques/nvim-lspfuzzy)
- [wiliamks/nice-reference.nvim](https://github.com/wiliamks/nice-reference.nvim) ![](https://img.shields.io/github/stars/wiliamks/nice-reference.nvim) ![](https://img.shields.io/github/last-commit/wiliamks/nice-reference.nvim) ![](https://img.shields.io/github/commit-activity/y/wiliamks/nice-reference.nvim)
- [gbrlsnchs/telescope-lsp-handlers.nvim](https://github.com/gbrlsnchs/telescope-lsp-handlers.nvim) ![](https://img.shields.io/github/stars/gbrlsnchs/telescope-lsp-handlers.nvim) ![](https://img.shields.io/github/last-commit/gbrlsnchs/telescope-lsp-handlers.nvim) ![](https://img.shields.io/github/commit-activity/y/gbrlsnchs/telescope-lsp-handlers.nvim)
- [edolphin-ydf/goimpl.nvim](https://github.com/edolphin-ydf/goimpl.nvim) ![](https://img.shields.io/github/stars/edolphin-ydf/goimpl.nvim) ![](https://img.shields.io/github/last-commit/edolphin-ydf/goimpl.nvim) ![](https://img.shields.io/github/commit-activity/y/edolphin-ydf/goimpl.nvim)

#### Code action

- [jose-elias-alvarez/null-ls.nvim(Code actions)](https://github.com/jose-elias-alvarez/null-ls.nvim) ![](https://img.shields.io/github/stars/jose-elias-alvarez/null-ls.nvim) ![](https://img.shields.io/github/last-commit/jose-elias-alvarez/null-ls.nvim) ![](https://img.shields.io/github/commit-activity/y/jose-elias-alvarez/null-ls.nvim)
- [kosayoda/nvim-lightbulb](https://github.com/kosayoda/nvim-lightbulb) ![](https://img.shields.io/github/stars/kosayoda/nvim-lightbulb) ![](https://img.shields.io/github/last-commit/kosayoda/nvim-lightbulb) ![](https://img.shields.io/github/commit-activity/y/kosayoda/nvim-lightbulb)
- [weilbith/nvim-code-action-menu](https://github.com/weilbith/nvim-code-action-menu) ![](https://img.shields.io/github/stars/weilbith/nvim-code-action-menu) ![](https://img.shields.io/github/last-commit/weilbith/nvim-code-action-menu) ![](https://img.shields.io/github/commit-activity/y/weilbith/nvim-code-action-menu)
- [RishabhRD/lspactions](https://github.com/RishabhRD/lspactions) ![](https://img.shields.io/github/stars/RishabhRD/lspactions) ![](https://img.shields.io/github/last-commit/RishabhRD/lspactions) ![](https://img.shields.io/github/commit-activity/y/RishabhRD/lspactions)
- [nyarthan/telescope-code-actions.nvim](https://github.com/nyarthan/telescope-code-actions.nvim) ![](https://img.shields.io/github/stars/nyarthan/telescope-code-actions.nvim) ![](https://img.shields.io/github/last-commit/nyarthan/telescope-code-actions.nvim) ![](https://img.shields.io/github/commit-activity/y/nyarthan/telescope-code-actions.nvim)
- [aznhe21/actions-preview.nvim](https://github.com/aznhe21/actions-preview.nvim) ![](https://img.shields.io/github/stars/aznhe21/actions-preview.nvim) ![](https://img.shields.io/github/last-commit/aznhe21/actions-preview.nvim) ![](https://img.shields.io/github/commit-activity/y/aznhe21/actions-preview.nvim)

#### Hint

- [jubnzv/virtual-types.nvim](https://github.com/jubnzv/virtual-types.nvim) ![](https://img.shields.io/github/stars/jubnzv/virtual-types.nvim) ![](https://img.shields.io/github/last-commit/jubnzv/virtual-types.nvim) ![](https://img.shields.io/github/commit-activity/y/jubnzv/virtual-types.nvim)
- [lvimuser/lsp-inlayhints.nvim](https://github.com/lvimuser/lsp-inlayhints.nvim) ![](https://img.shields.io/github/stars/lvimuser/lsp-inlayhints.nvim) ![](https://img.shields.io/github/last-commit/lvimuser/lsp-inlayhints.nvim) ![](https://img.shields.io/github/commit-activity/y/lvimuser/lsp-inlayhints.nvim)
- [simrat39/inlay-hints.nvim](https://github.com/simrat39/inlay-hints.nvim) ![](https://img.shields.io/github/stars/simrat39/inlay-hints.nvim) ![](https://img.shields.io/github/last-commit/simrat39/inlay-hints.nvim) ![](https://img.shields.io/github/commit-activity/y/simrat39/inlay-hints.nvim)
- [Daniel-Esteban/nvim-inlay-hints](https://github.com/Daniel-Esteban/nvim-inlay-hints) ![](https://img.shields.io/github/stars/Daniel-Esteban/nvim-inlay-hints) ![](https://img.shields.io/github/last-commit/Daniel-Esteban/nvim-inlay-hints) ![](https://img.shields.io/github/commit-activity/y/Daniel-Esteban/nvim-inlay-hints)
- [phenax/nvim-extra-codelens](https://github.com/phenax/nvim-extra-codelens) ![](https://img.shields.io/github/stars/phenax/nvim-extra-codelens) ![](https://img.shields.io/github/last-commit/phenax/nvim-extra-codelens) ![](https://img.shields.io/github/commit-activity/y/phenax/nvim-extra-codelens)

#### Hover Doc

- [jose-elias-alvarez/null-ls.nvim(Hover)](https://github.com/jose-elias-alvarez/null-ls.nvim) ![](https://img.shields.io/github/stars/jose-elias-alvarez/null-ls.nvim) ![](https://img.shields.io/github/last-commit/jose-elias-alvarez/null-ls.nvim) ![](https://img.shields.io/github/commit-activity/y/jose-elias-alvarez/null-ls.nvim)
- [tamago324/lsp-preview-hover-doc.nvim](https://github.com/tamago324/lsp-preview-hover-doc.nvim) ![](https://img.shields.io/github/stars/tamago324/lsp-preview-hover-doc.nvim) ![](https://img.shields.io/github/last-commit/tamago324/lsp-preview-hover-doc.nvim) ![](https://img.shields.io/github/commit-activity/y/tamago324/lsp-preview-hover-doc.nvim)
- [amrbashir/nvim-docs-view](https://github.com/amrbashir/nvim-docs-view) ![](https://img.shields.io/github/stars/amrbashir/nvim-docs-view) ![](https://img.shields.io/github/last-commit/amrbashir/nvim-docs-view) ![](https://img.shields.io/github/commit-activity/y/amrbashir/nvim-docs-view)
- [xiyaowong/link-visitor.nvim](https://github.com/xiyaowong/link-visitor.nvim) ![](https://img.shields.io/github/stars/xiyaowong/link-visitor.nvim) ![](https://img.shields.io/github/last-commit/xiyaowong/link-visitor.nvim) ![](https://img.shields.io/github/commit-activity/y/xiyaowong/link-visitor.nvim)

#### Rename

- [smjonas/inc-rename.nvim](https://github.com/smjonas/inc-rename.nvim) ![](https://img.shields.io/github/stars/smjonas/inc-rename.nvim) ![](https://img.shields.io/github/last-commit/smjonas/inc-rename.nvim) ![](https://img.shields.io/github/commit-activity/y/smjonas/inc-rename.nvim)

### LSP Status

- [j-hui/fidget.nvim](https://github.com/j-hui/fidget.nvim) ![](https://img.shields.io/github/stars/j-hui/fidget.nvim) ![](https://img.shields.io/github/last-commit/j-hui/fidget.nvim) ![](https://img.shields.io/github/commit-activity/y/j-hui/fidget.nvim)
- [nvim-lua/lsp-status.nvim](https://github.com/nvim-lua/lsp-status.nvim) ![](https://img.shields.io/github/stars/nvim-lua/lsp-status.nvim) ![](https://img.shields.io/github/last-commit/nvim-lua/lsp-status.nvim) ![](https://img.shields.io/github/commit-activity/y/nvim-lua/lsp-status.nvim)
- [arkav/lualine-lsp-progress](https://github.com/arkav/lualine-lsp-progress) ![](https://img.shields.io/github/stars/arkav/lualine-lsp-progress) ![](https://img.shields.io/github/last-commit/arkav/lualine-lsp-progress) ![](https://img.shields.io/github/commit-activity/y/arkav/lualine-lsp-progress)
- [doums/lsp_spinner.nvim](https://github.com/doums/lsp_spinner.nvim) ![](https://img.shields.io/github/stars/doums/lsp_spinner.nvim) ![](https://img.shields.io/github/last-commit/doums/lsp_spinner.nvim) ![](https://img.shields.io/github/commit-activity/y/doums/lsp_spinner.nvim)
- [aznhe21/lsp-query-format.nvim](https://github.com/aznhe21/lsp-query-format.nvim) ![](https://img.shields.io/github/stars/aznhe21/lsp-query-format.nvim) ![](https://img.shields.io/github/last-commit/aznhe21/lsp-query-format.nvim) ![](https://img.shields.io/github/commit-activity/y/aznhe21/lsp-query-format.nvim)

### Local LSP Config

- [tamago324/nlsp-settings.nvim](https://github.com/tamago324/nlsp-settings.nvim) ![](https://img.shields.io/github/stars/tamago324/nlsp-settings.nvim) ![](https://img.shields.io/github/last-commit/tamago324/nlsp-settings.nvim) ![](https://img.shields.io/github/commit-activity/y/tamago324/nlsp-settings.nvim)
- [zhang-stephen/nvim-lsp-loader](https://github.com/zhang-stephen/nvim-lsp-loader) ![](https://img.shields.io/github/stars/zhang-stephen/nvim-lsp-loader) ![](https://img.shields.io/github/last-commit/zhang-stephen/nvim-lsp-loader) ![](https://img.shields.io/github/commit-activity/y/zhang-stephen/nvim-lsp-loader)

## Disable/Enable

- [adoyle-h/lsp-toggle.nvim](https://github.com/adoyle-h/lsp-toggle.nvim) ![](https://img.shields.io/github/stars/adoyle-h/lsp-toggle.nvim) ![](https://img.shields.io/github/last-commit/adoyle-h/lsp-toggle.nvim) ![](https://img.shields.io/github/commit-activity/y/adoyle-h/lsp-toggle.nvim)

## Pre-configuration

- [junnplus/nvim-lsp-setup](https://github.com/junnplus/nvim-lsp-setup) ![](https://img.shields.io/github/stars/junnplus/nvim-lsp-setup) ![](https://img.shields.io/github/last-commit/junnplus/nvim-lsp-setup) ![](https://img.shields.io/github/commit-activity/y/junnplus/nvim-lsp-setup)
- [VonHeikemen/lsp-zero.nvim](https://github.com/VonHeikemen/lsp-zero.nvim) ![](https://img.shields.io/github/stars/VonHeikemen/lsp-zero.nvim) ![](https://img.shields.io/github/last-commit/VonHeikemen/lsp-zero.nvim) ![](https://img.shields.io/github/commit-activity/y/VonHeikemen/lsp-zero.nvim)

## Backwards Compatibility

- [weilbith/nvim-lsp-bacomp](https://github.com/weilbith/nvim-lsp-bacomp) ![](https://img.shields.io/github/stars/weilbith/nvim-lsp-bacomp) ![](https://img.shields.io/github/last-commit/weilbith/nvim-lsp-bacomp) ![](https://img.shields.io/github/commit-activity/y/weilbith/nvim-lsp-bacomp)
