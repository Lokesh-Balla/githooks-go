# githooks-go

pre-commit git hooks for Golang projects

## Prerequisites

- goimports
- gofmt

```bash
# installing goimports
$ go install golang.org/x/tools/cmd/goimports@latest

# installing gofumpt
$ go install mvdan.cc/gofumpt@latest
```

## copying the git hook

```bash
# clone the repo
git clone --depth=1 https://github.com/Lokesh-Balla/githooks-go.git

# copy githooks from githooks folder to git repository
$ cd githooks-go
$ chmod +x githooks/*
$ cp githooks/* <project_directory>/.git/hooks/
```
