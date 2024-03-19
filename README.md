# UDP Chat Application
The UDP Chat Application is a straightforward chat program enabling users to exchange messages over a local network using the User Datagram Protocol (UDP). It comprises two Java files: UDPClient.java for the client-side and UDPServer.java for the server-side.

## Table of Contents
Installation
Usage
Error Handling
License
Contributing
Acknowledgments
## Installation
- Install Java version 15 or higher.
- Clone the project.
- Run locally.
## Server
- Compile and run UDPServer.java on the machine designated as the server, which listens on port 12345 by default.
- Ensure the server is operational and ready to accept incoming client connections.
## Client
- Compile and run UDPClient.java on each client machine.
- Upon prompt, provide a unique username for identification.
- Start sending and receiving messages with other connected clients on the network.
## Usage
Once the server and clients are configured:

- Enter a username to initiate message exchange in the chat window.
- To send a message, type it in the input text field and press "Send" or hit Enter.
- To exit the chat, type "/quit" and press "Send" to remove yourself from the chat and close the client application.
## Error Handling
- If either the server or any client encounters an error during execution, error messages will be logged to the console for troubleshooting.
- Both client and server applications handle common exceptions and provide feedback in case of issues.
## License
This project is released under the MIT License.
