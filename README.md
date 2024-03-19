# Simple-chat-rooms

基于TCP/IP协议的WINSOCKET2编程的简易聊天室

使用protobuf序列化传输

protoc编译指令:

```bash
protoc chatroom.proto --cpp_out=.
```

cpp编译指令:

```bash
g++ server.cpp chatroom.pb.cc -o server.exe -lws2_32 -I.
```
