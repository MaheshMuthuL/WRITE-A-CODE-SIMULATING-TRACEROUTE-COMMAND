# WRITE-A-CODE-SIMULATING-TRACEROUTE-COMMAND
WRITE A CODE SIMULATING TRACEROUTE COMMAND

EXP: 4(b)

DATE:

AIM:

To write the python program for simulating Traceroute command

ALGORITHM:

1. Start the program.
2. Get the frame size from the user.
3. To create the frame based on the user request.
4. To send frames to server from the client side.
5. If your frames reach the server, it will send ACK signal to client
otherwise it will sendNACK signal to client.
6. Stop the program


PROGRAM:
```
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
OUTPUT:
![4b](https://github.com/MaheshMuthuL/WRITE-A-CODE-SIMULATING-TRACEROUTE-COMMAND/assets/135570619/d73213b7-51e0-4f41-a318-bfa90df995b1)





RESULT:

Thus, the python program for simulating Traceroute command was successfully executed.
