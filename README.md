# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![image](https://github.com/user-attachments/assets/7117e48a-8db9-4fb9-8460-49ac074856d2)

## OUPUT - ARP
![image](https://github.com/user-attachments/assets/47b5e306-919f-4f96-b4d5-10a20f154ec9)

## PROGRAM - RARP
![image](https://github.com/user-attachments/assets/d26e6ddb-5ad6-4e45-bd63-f3c22a75e25f)

## OUPUT -RARP
![image](https://github.com/user-attachments/assets/0b48c070-8210-439a-bf70-4f8b98ea6b60)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
