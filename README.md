# Packet_Sniffer
A Packet sniffer — also known as a packet analyzer, protocol analyzer or network analyzer — is a piece of hardware or software used to monitor network traffic. 
Sniffers work by examining streams of data packets that flow between computers on a network as well as between networked computers and the larger Internet.

### How To Run
1. Navigate to the **packet-sniffer** project folder.
2. Within the Terminal, type the following:
   ```shell
    ifconfig 
    ```
4. With the Command Line,  open pointing to the packet sniffer directory, type the following command and press <kbd>Enter</kbd>
    ```shell
    gcc -o sniffer packet_sniifer.c -lpcap 
    ```
5. To Run, type:
   ```shell
    sudo ./sniffer [enp0s25 or eth0 or wlo1]
    ```
