# DataCommProject
Course project for data communication

Team Members: Arjun Joshi (B17CS008) and Ayush Saxena (B17CS010).

Steps:

1) Clone the repository.
2) Run server in a terminal first by typing python server.py
3) Then run client in a different terminal by typing python client.py
4) Write the message you want to send from client to server.


The program will send the message from client to server. It first converts the message to binary. Then divides the binary message into frames. Then sends these frames individually, with using crc (Cyclic Redundancy Check) on each frame so as to check if each frame is sent and recieved correctly. The recieved data after Cyclic Redundancy Check is then decoded and joined together to form the original message.

