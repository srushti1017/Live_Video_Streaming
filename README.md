# Live_Video_Streaming
# Hey Learners I am here with the new code for creating a live video stream in which socket programming is used. 

# Socket programming :
The way of establishing the connection between the two softwares by using sockets where as sockets connect the software either between the two different computers or the same computer. Here we are going to establish connection between thw two softwares of the same computer..

# Required modules which we are going to import :

    import socket 
    import cv2 
    import pickle
    import struct
    
   Socket module is used to establish the connection , cv2 module is used to capture the video , pickle module is used to serialize the object hierarchy this will done by the dumps() that means object is saved on the disk function of this module then by using struct packing and unpacking will be done.

# NOTE :
Here sever accepts the client request by using port number and IP address of the client , so once the server accept the request and connect to the server but if 2nd time client send the request from same port number at that time server deny the request so for this we have change the port number.
