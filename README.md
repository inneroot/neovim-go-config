# NvChad custom config for Go development

Based on [@dreamsofcode-io](https://github.com/dreamsofcode-io/neovim-go-config) video - [The perfect Neovim setup for Go](https://www.youtube.com/watch?v=i04sSQjd-qo)

## Install Neovim

[Neovim docs](https://github.com/neovim/neovim/wiki/Installing-Neovim)

## Install NvChadi

[NvChad docs](https://nvchad.com/docs/quickstart/install)

## Clone go dev config repo to custom NvChad folder

```
git clone git@github.com:inneroot/neovim-go-config.git ~/.config/nvim/lua/custom
```

## Install Go tools

```bash
go install github.com/incu6us/goimports-reviser/v3@latest
go install mvdan.cc/gofumpt@latest
go install github.com/segmentio/golines@latest
go install github.com/go-delve/delve/cmd/dlv@latest
```

## Install treesitter fo go

open nvim

```
:TSInstall go
```
