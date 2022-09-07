**The following is a general description of each experiment.**

1. **Environment construction:** Build the attack machine and target machine environment in virtual machine, the attack machine is Kali OS, the target machine is windows 2008 OS, use various tools of Kali to attack the target machine, and observe the real-time ip change of the attack machine and target machine.

2. **Wireshark packet sniffing and analysis:** Use the protocol analysis tool Wireshark to capture and analyze the IP datagram packet format, and visualize the specific transmission process of the data. Analyze the captured packets to consolidate the knowledge of Ethernet II packets, ARP packets and IP and ICMP packets. Intercept TCP packet header information and understand that the fields in the header such as serial number and acknowledgement number are the basis of a reliable TCP connection. Understand the TCP connection establishment and release mechanism by analyzing the three handshake establishment and release process of Wireshark connections. Use Wireshark to listen to ICMP packets, analyze the main functions of the ping program and tracert program, and analyze the interrelationship between its MAC frames, IP packets, and ICMP packets for any ICMP packet caught. Use Wireshark to listen to arp packets and analyze the contents of arp request and reply packets.


3. **Use Nmap command tool to scan network protocols:** use Nmap command tool to scan network protocols (TCP/TCP indirect/UDP), use netstat, arp, nslookup commands to view network status.


4. **Using driftnet to intercept image data stream:** learn to enable linux virtual machine configuration kali in Windows system and use kali tool ettercap to implement real ARP spoofing operation and can actually intercept the image data stream of the attacking machine. In-depth understanding of the basic operation of computer network ARP spoofing attack, master the principle and efficacy of computer network ARP attack.


5. **Realize phishing:** learn to enable linux virtual machine configuration windows 2008 in Windows system and use kali tool ettercap to realize real DNS spoofing operation and be able to do real phishing. Understand the basic operation of DNS spoofing attacks on computer networks, implement DNS spoofing + website cloning to achieve website phishing attacks, and use social engineering attack tools.


6. **denial of service attacks:** learn the principles of denial of service attacks. Install siege & t50 on the attacking machine to perform distributed denial of service attack on the target machine; master some usage of hping3, siege and t50, and think about the possibility of using it as a DDOS attack. Finally, run wireshark on the attack machine and listen to the TCP protocol of the target machine.


7. **buffer overflow attack:** learn the principle of buffer overflow attack. A buffer overflow is a situation where a program attempts to write data to a buffer beyond a pre-allocated fixed length. This vulnerability can be exploited by a malicious user to alter the flow control of a program or even execute arbitrary pieces of code. This vulnerability occurs due to a temporary shutdown of the data buffer and return address, and the overflow can cause the return address to be rewritten. The buffer overflow attack is implemented in the Kali machine using the given shellcode and exploit.c.
