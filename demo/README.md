Simple Client/Server model communication using protobuf and Go lang

Using Makefile to build and test
> make help
> make dep

Open two terminal and run
> make build_server
> ./server.bin
and in another terminal
> make build_client
> ./clent.bin

or after make dep
we can run server and client, like below too
> go run server/main.go
> go run client/main.go
