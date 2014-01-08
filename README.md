[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=dontmind&url=https://github.com/bk138/Multicast-Client-Server-Example&title=Multicast-Client-Server-Example&language=&tags=github&category=software) 

This is a simple educational example of a multicast 
client and server, running under UNIX and Win32.

To compile, use

    ./autogen.sh && ./configure && make
    
    
Example usage:

    ./server 225.0.0.1 8888 1000 2000
    
    ./client 225.0.0.1 8888 1000
    
