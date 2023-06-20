# WSL 4 error on file with dependencies with another files within the same package

## How to run

1. Install wsl v4

```shell
go install github.com/bombsimon/wsl/v4/cmd...@master
```

2. With wsl v4 run:

```shell
wsl main.go
```

It would fail on v4 but if you install wsl v3 it works.
