# ClientServerOne

To run this code you must start two terminals one for the server and one for the client. Always start with the server since it is the server the client has to connect to, and not the other way around.
As such:

    go run server/server.go -port 5001

Then start the client at it's own port and choose the same port as the server for the flag -sPort. As such:

    go run client/client.go -cPort 4041 -sPort 5001

Now you are good to tap any key on the keyboard to make the client ask the server for the time.
