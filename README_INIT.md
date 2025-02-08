# INIT

## Prepare

事前にGoをlocalにinstallしておいてください．

`open https://go.dev/dl/`

## STEP

| # | STEP NAME                          | Command                                     |
|---|------------------------------------|---------------------------------------------|
| 1 | Create empty directory             | `mkdir {Project Root}`                      |
| 2 | Move project root.                 | `cd {Project Root}`                         |
| 3 | Init go project                    | `go mod init sample-go`                     |
| 4 | Add library. Library name is `gin` | `go get -u github.com/gin-gonic/gin`        |
| 5 | Add File                           | `touch main.go` and See [commit](#9dd1ea9d) |
