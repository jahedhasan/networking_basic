# Basic Network Troubleshooting Tools         


### Command-Line Tools        
On Windows PCs, the command prompt can be accessed by searching for it in the start menu or by typing `cmd` into the Run window. On a Linux system, you can press `Ctrl + Alt + T` to open the command line.        


The following commands can be entered into the command prompt one at a time to reveal specific information about the network status:       

`*` **ping** — A TCP/IP utility that transmits a datagram to another host, specified in the command. If the network is functioning properly, the receiving host returns the datagram.     
`*` **tracert/traceroute** —A TCP/IP utility that determines the route data takes to get to a particular destination. This tool can help you to determine where you are losing packets in the network, helping to identify problems.    
`*` **nslookup** — A DNS utility that displays the IP address of a hostname or vice versa. This tool is useful for identifying problems involving DNS name resolution.     
`*` **ipconfig** — A Windows TCP/IP utility that verifies network settings and connections. It can tell you a host’s IP address, subnet mask and default gateway, alongside other important network information.      
`*` **ifconfig** — A Linux or UNIX TCP/IP utility that displays the current network interface configuration and enables you to assign an IP address to a network interface. Like ipconfig on Windows, this command will tell you vital information about the network and its status.      
`*` **iptables** — A Linux firewall program that protects a network. You can use this tool if you suspect that your firewall may be too restrictive or too lenient.    
`*` **netstat** — A utility that shows the status of each active network connection. This tool is useful for finding out what services are running on a particular system.     
`*` **tcpdump** — A utility that is used to obtain packet information from a query string sent to the network interface. It’s available for free on Linux but can be downloaded as a command for Windows.     
`*` **pathping** — A TCP/IP command that provides information about latency and packet loss on a network. It can help you troubleshoot issues related to network packet loss.     
`*` **nmap** — A utility that can scan the entire network for various ports and the services that are running on them. You can use it to monitor remote network connections and get specific information about the network.    
`*` **route** — A command that enables manual updating of the routing table. It can be used to troubleshoot static routing problems in a network.    
`*` **arp** — A utility that supports the Address Resolution Protocol (ARP) service of the TCP/IP protocol suite. It lets the network admin view the ARP cache and add or delete cache entries. It can be used to address problems having to do with specific connections between a workstation and a host.     
`*` **dig** — A Linux or UNIX command-line tool that will display name server information. It can be used to troubleshoot problems in DNS name resolution.            




 Source:  https://www.comptia.org/content/guides/a-guide-to-network-troubleshooting