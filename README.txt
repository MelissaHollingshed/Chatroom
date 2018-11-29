Melissa Hollingshed 
14198590
Computer Networks



--- Running the Program / Sample Run ---

This chatroom requires that you use the credentials.txt file which will hold all user name and passwords in this doc. This chatroom is built by using the language Python so it's recommended you use terminal or the like. 

With this set up, you can run the program as such:

python Server.py

# run this second step for as many clients as you want
python Client.py <server_ip_address>

The IP address will be whatever ip network you are connected to at that moment. 

--
EXAMPLE
--
# on computer A
python Server.py

# on computer B
python python Client.py 192.168.1.5
>New user? click "y", click any other button for no: n
continue
>LOGIN!
>Username: Tom
>Password: Tom11
>Welcome to simple chat server!
>Offline Messages:
>No offline messages
>logout

---
COMMANDS 
Once logged in... 
SENDALL
>sendall a message 
Will send a message to all users 

WHO
>who
Will list all online users 

SEND
>send Tom
Sends direct message 

LOGOUT
>logout
Will logout 


There is also extra features like blocking, getting p2p information, etc that is not relevant to the second part of this lab. If you'd like to play with my code you can read the code for further documentation. 



