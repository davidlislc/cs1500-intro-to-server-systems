# netutils

**1. Which modern command replaces the legacy 'ifconfig' for managing network interfaces in Linux?**

- A) netstat
- B) ip
- C) dig
- D) ss

**2. What is the primary function of the 'lo' interface?**

- A) Connecting to a local area network
- B) Internal communication within the host
- C) Bridging Docker containers
- D) Managing wireless connections

**3. Which command would you use to display all network interfaces and their assigned IP addresses?**

- A) ip r
- B) ss -l
- C) ip a
- D) dig -x

**4. What is the default Maximum Transmission Unit (MTU) size for the loopback interface as shown in the materials?**

- A) 1500
- B) 65536
- C) 1460
- D) 9000

**5. Which command is used specifically to show the routing table?**

- A) ip addr add
- B) ss -tulpn
- C) ip r
- D) ip link set

**6. What does the 'dynamic' flag next to an IPv4 address indicate?**

- A) The IP was assigned manually
- B) The IP changes every time the system reboots
- C) The IP was assigned by DHCP
- D) The IP is part of a virtual bridge

**7. If you see 'state DOWN' on a Docker bridge interface like 'docker0', what does it likely mean?**

- A) The Docker service is crashed
- B) No containers are currently attached to that network
- C) The physical cable is unplugged
- D) The IP address is conflicting

**8. Which command correctly adds a temporary IP address to the 'ens160' interface?**

- A) ip link set ens160 192.168.1.100/24
- B) ip addr add 192.168.1.100/24 dev ens160
- C) ss -add 192.168.1.100/24 ens160
- D) ip route add 192.168.1.100/24 via ens160

**9. What is the purpose of the 'ss' command?**

- A) System Shutdown
- B) Socket Statistics
- C) Secure Shell
- D) Subnet Scanner

**10. Which 'ss' flag is used to display the process (PID/Name) using a specific socket?**

- A) -n
- B) -l
- C) -p
- D) -t

**11. To show only listening TCP ports without resolving names (numeric only), which command is correct?**

- A) ss -ltn
- B) ss -u
- C) dig +tcp
- D) ip link show

**12. Which command replaces the legacy 'netstat' tool?**

- A) ip
- B) ss
- C) dig
- D) ping

**13. What does the 'dig' command primarily perform?**

- A) Disk usage analysis
- B) DNS lookups
- C) Interface configuration
- D) Routing table edits

**14. How do you perform a reverse DNS lookup (IP to hostname) using 'dig'?**

- A) dig -rev [IP]
- B) dig -x [IP]
- C) dig -lookup [IP]
- D) dig -a [IP]

**15. Which special DNS domain is used exclusively for reverse lookups?**

- A) local.arpa
- B) dns.google
- C) in-addr.arpa
- D) ip6.arpa

**16. Which command is used to bring a network interface named 'ens160' online?**

- A) sudo ip route add ens160 up
- B) sudo ip link set ens160 up
- C) sudo ip addr up ens160
- D) ss -up ens160

**17. What does a '/24' subnet mask translate to in standard decimal notation?**

- A) 255.255.0.0
- B) 255.0.0.0
- C) 255.255.255.0
- D) 255.255.255.255

**18. Which command adds a default gateway of 192.168.1.1?**

- A) ip addr add default via 192.168.1.1
- B) ip route add default via 192.168.1.1
- C) ss -gateway 192.168.1.1
- D) dig gateway 192.168.1.1

