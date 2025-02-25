# 23071A3241-os-11
Distributed Chat Application using Sockets This project demonstrates a distributed chat application using UNIX domain sockets for local communication and Internet domain sockets for network communication.
Usage
1. Compile the Code
bash
Copy
# UNIX Domain Server and Client
gcc unix_server.c -o unix_server -lpthread
gcc unix_client.c -o unix_client

# Internet Domain Server and Client
gcc internet_server.c -o internet_server -lpthread
gcc internet_client.c -o internet_client
2. Run the Servers
bash
Copy
# Start the UNIX Domain Server
./unix_server

# Start the Internet Domain Server
./internet_server
3. Run the Clients
bash
Copy
# Connect to the UNIX Domain Server
./unix_client

# Connect to the Internet Domain Server
./internet_client
