# tcpheart
gcc hb_client.c tcp_client.c util.c -o client
gcc hb_server.c tcp_server.c util.c -o server
gcc vrc.c tcp_client.c util.c -o client
gcc vrs.c tcp_server.c util.c readvrec.c readn.c  -o server

go build TcpServer.go 
./TcpServer
使用 命令 
112233445566 get file network
112233445566 get inform
112233445566 get command ls
112233445566 set command 

cp js  /usr/lib/   

客户端使用
arm-linux-gcc tcp_hb.c tcp_client.c util.c b64.c -o tcpReport -I./jsonarm/include/json-c/  -L./jsonarm/lib -lm -ljson-c


arm-linux-gcc tcp_hb.c tcp_client.c util.c b64.c libjson-c.a -o tcpReport  -I./jsonarm/include/json-c/ -I/home/sintai/srcsintai/include -L/home/sintai/srcsintai/linuxlib -lotns -liconv -lsqlite3 -lm



./tcpReport 127.0.0.1 8880

