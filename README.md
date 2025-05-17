# TCP 3-Way Handshake
In this lab, we analyzed the TCP 3-way handshake process using Wireshark. Wireshark was opened with administrator privileges.

The following command was executed in the Command Prompt to initiate a TCP connection:

![image](https://github.com/user-attachments/assets/66d425e0-a113-4f32-b5b0-decf6969b233)

A Wireshark display filter was applied:

tcp && ip.addr == 142.250.74.142

![image](https://github.com/user-attachments/assets/b1a2068d-6c38-4c82-8ac1-e0443346ea7e)

The three main handshake packets were successfully captured:

[SYN] — Client to server connection request (Frame 1684)

[SYN, ACK] — Server acknowledges and responds (Frame 1685)

[ACK] — Client confirms the connection (Frame 1686)

These packets confirm that a TCP connection was successfully established.

Conclusion:
The TCP 3-way handshake was successfully captured and analyzed.
