# NvChad custom config for Go development

Based on [@dreamsofcode-io](https://github.com/dreamsofcode-io/neovim-go-config) [vudeo](https://www.youtube.com/watch?v=i04sSQjd-qo)


## Install tools

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
