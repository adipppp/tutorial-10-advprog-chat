# tutorial-10-advprog-chat

## Reflection
### Experiment 2.1

#### Server
![server.png](assets/server.png)

#### Client 1
![client_1.png](assets/client_1.png)

#### Client 2
![client_2.png](assets/client_2.png)

#### Client 3
![client_3.png](assets/client_3.png)

### Experiment 2.2
In the tutorial, we modified the client file to connect to the endpoint with port 8080. Since we are going to connect to port 8080, we need to make sure that the server listens to that port as well. We modified the `TcpListener::bind` associated function to take a `String` argument that represents the endpoint with port 8080. This tells the server to bind to the endpoint with port 8080 before listening to it. Since we only modified the port, the protocol remains unchanged. Thus, we are still using WebSocket protocol for our chat program.


### Experiment 2.3
I put my username in the string literals printed to the console on both server and client files.
