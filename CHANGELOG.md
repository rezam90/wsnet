language: go
sudo: required
go:
- 1.6
- 1.7
- 1.8
install:
  - go get github.com/gorilla/websocket
script:
  - go test