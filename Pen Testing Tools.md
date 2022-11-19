# 1. Nmap

1.1 Sub-net scan, it's using the ICMP ping protocol to see whether it responds.


 

Nmap is checking the most common services to see if they’re open on the host. It does this by starting to open a connection to the service, and then closing it down before the connection is complete. This is called a TCP SYN ping, and it works by sending an empty TCP packet with the SYN flag set and waiting for the host to respond with the standard SYN-ACK response. While a normal connection would be completed by sending back an ACK, Namp instead cancels the connection before it complete.
