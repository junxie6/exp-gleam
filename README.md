# exp-gleam

```
$ go get github.com/chrislusf/gleam/flow
$ go get github.com/chrislusf/gleam/distributed/gleam

$ gleam master --address="192.168.6.20:45326"

$ GRPC_GO_REQUIRE_HANDSHAKE=off gleam agent --dir="/home/jun/tmp/exp-gleam" --master="192.168.6.20:45326" --host="192.168.6.22" --port=45327
$ GRPC_GO_REQUIRE_HANDSHAKE=off gleam agent --dir="/home/jun/tmp/exp-gleam" --master="192.168.6.20:45326" --host="192.168.6.24" --port=45327

$ GRPC_GO_REQUIRE_HANDSHAKE=off go run main.go -distributed
```
