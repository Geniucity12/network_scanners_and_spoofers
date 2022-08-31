1. the network_scanner is used to discover clients on thesame network as your machine using a python module called SCAPY.
you run the code from the terminal in this form: python network_scanner.py


2. the arp_spoof.py is a program utilising the SCAPY module to become the man in the middle MITM between two networks, it tricks the target machine into thinking the host machine is the router; thereby sending it's packets to the host/attacker machine. The simple way to run this code from ternminal is by calling it; python arp_spoof.py
Ensure to enable port forwarding by using the command:  echo 1 > /proc/sys/net/ipv4/ip_forward

3. the packet_sniffer.py sniffs and filters useful information like emails, usernames and passwordsfrom a target machine 


Remember to use your valid ip and mac addresses!
