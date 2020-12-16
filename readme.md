
Netty beginner log...

#1.Time service & client

##1.1. start service 
java -cp .\target\netty-beginner.jar cn.net.mysoft.rpc.nettyexperience.svr.TimeServer

##1.2. start client
java -jar .\target\netty-beginner.jar 127.0.0.1 8082

#2. Echo service & test

##2.1. start service
java -cp .\target\netty-beginner.jar cn.net.mysoft.rpc.nettyexperience.svr.EchoServer

##2.2. start client
telnet 127.0.0.1 8081

#3. Discard service & test

##3.1. start service
java -cp .\target\netty-beginner.jar cn.net.mysoft.rpc.nettyexperience.svr.DiscardServer

##3.2. start client
telnet 127.0.0.1 8080"# netty-study" 
