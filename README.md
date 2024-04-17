# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

- `Step 1:` Install kali linux either in partition or virtual box or in live mode
- `Step 2:` Investigate on the various categories of tools as follows.
-  `Step 3:` Open terminal and try execute some kali linux commands

### DEVELOPED BY : Gumma Dileep Kumar
### REGISTER NO : 212222240032
## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![ethical_4 1](https://github.com/gummadileepkumar/ARP-Attack-and-Network-Sniffing/assets/118707761/8c41b8de-6906-4daa-abad-acc3a28b74a9)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![ethical_4 2](https://github.com/gummadileepkumar/ARP-Attack-and-Network-Sniffing/assets/118707761/10b4e04b-fa73-45a0-898d-0f3040d907c7)


 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![ethical_4 3](https://github.com/gummadileepkumar/ARP-Attack-and-Network-Sniffing/assets/118707761/286c46a2-c39a-48ea-adb8-a40c9e93ec9a)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![ethical_4 4](https://github.com/gummadileepkumar/ARP-Attack-and-Network-Sniffing/assets/118707761/0645264f-feb4-44c3-b942-fbdbbbd4e38e)


Invoke the wireshark and examine the various menus  and controls of the tool:

![ehical_4 5](https://github.com/gummadileepkumar/ARP-Attack-and-Network-Sniffing/assets/118707761/9f9fe704-067a-46cc-ba95-2571b99f6237)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
