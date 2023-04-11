# opensourceprojects
// First of all install WireShark on Linux or Windows, but i am using WireShark on Linux OS.
Commands To Capture Packets Using Wire Shark 

//To find network with ip address
Search with :  ip addr == 192.168.154.132

//To search network with destination address
Search with : ip.dest == 192.168.154.132

Note: 192.168.154.132 is my Ip address in case of your system it may be different

//To search with source address in Wireshark
 we can search withip src == 192.168.88.128
 
//To capture TCP packets
you can also search packets like jst search TCP and you will get all the packets comming from TCP Protocols.

//To Capture UDP Protocols packets.
You can find network with UDP protocols jst write UDP and you will see all the networks related to UDP protocols.

//For HTTP you can do http and press enter and you will get packets coming from http is being generated.

There are various features like filter, capture , change color of your network interface.

You can also capture packets of different OSI model. It is jst below the Lower interface of wireshark.

//If you would like to assigned network then you can also do that.
Open Kali Linux terminal and assigned some network with the help of ping command.
Ping 8.8.8.8 
After that if you would like to access this then, go to filter and assigned ip of 8.8.8.8 and press enter.
// you will see the network you assigned is being captured.


