forked from [ankscircle](https://github.com/ankscircle/Distributed-FileSystem) 

1. We have the following files:  
  a. dfsserver.c (The Master Server Program)  
  b. dfsclient.c (The Client Program)  
  c. dfsslaveserver.c (The Slave Server Program)  
  d. Makefile  
  e. Enhancement  
  f. README.md

2. The dfsslaveserver.c needs to be invoked first, followed by dfsserver.c and then dfsclient.c 

3. The syntax to invoke the Distributed file system is:  
  a. for dfsserver.c   
  Syntax:    
  `./dfsserver <port-number-to-connect-to-client> <port-number-to-connect-to-slave-server> <slave-server-hostname>`  

  b. for dfsclient.c  
  Syntax: 
  `./dfsclient <port-number=to-connect-to-dfsserver> <dfsserver-hostname> -s <mountpoint> `

  c. for dfsslaveserver.c  
  Syntax: 
  `./dfsslaveserver <port-number-to-connect-to-dfsserver> `
  
4. Create a file named .logging in present working directory of server

