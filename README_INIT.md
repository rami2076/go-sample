# INIT

## Prepare

事前にGoをlocalにinstallしておいてください．

`open https://go.dev/dl/`

## STEP

| # | STEP NAME                          | Command                                                                                                                       |
|---|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| 1 | Create empty directory             | `mkdir {Project Root}`                                                                                                        |
| 2 | Move project root.                 | `cd {Project Root}`                                                                                                           |
| 3 | Init go project                    | `go mod init sample-go`                                                                                                       |
| 4 | Add library. Library name is `gin` | `go get -u github.com/gin-gonic/gin`                                                                                          |
| 5 | Add File                           | `touch main.go` and See [commit](https://github.com/rami2076/go-sample/blob/9dd1ea9dad9b5870ec79c4efc7f42636ad5789c2/main.go) |
| 6 | Run Go file                        | `go run main.go`                                                                                                              |
| 7 | Access to processing go server.    | `curl -i localhost:8080/ping`                                                                                                 |
