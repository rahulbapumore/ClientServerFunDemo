# ClientServerFunDemo
These are simple client server demo applications made in delphi(Windows Application). For Client application i have used TWSocket and for server Application i have used TWSocketServer components in delphi.

To be able to use these applications on same machine(Client and server run on same machine) or on different machine(Client is run on one machine and server is run on another machine) in both cases you need to configure your pc with lan setting give some ip(192.168.2.something) to your pc where you run your client and you have to compulsory give ip(192.168.2.233) another pc where you run server application.And main thing if you are running clients and server on different machine then you need to be connected by lan only.

One thing you can do give your own pc 192.168.2.233 ip and then you can run client and server on same machine.

I have uploaded 2 zip files.In both .pas file contains all source code needed.I hope you know about delphi and how to open .dpr project files in delphi.

for any issue , concern mail me at rahulbapumore@gmail.com.

In Client application there is textbox where you can enter only 3 things otherwise no output is generated.
1)enter text 'IP'. when you enter ip and click on send button .server rerurns server ip address to client.
2)enter text 'Hostname'. when you enter Hostname and click on send button .server rerurns server hostname  to client.
3)you have to enter fully qualified text file name with path of text file on server then it will return you text file on server on your pc in E:\ path.but your pc must have E drive and file with same name on server will be created in e drive.

and from server you can broadcast message to all clients connected

and GUI is very simple you will get to know when you will run .exes files

thanks
