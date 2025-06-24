# 1st-cs-task
Port scaning using nmap and performing tcp scan and packets capturing using wire shark
install nmap
ifconfig
192.168.1.0/24
nmap -sS 192.168.1.0/24
Nmap scan report for 192.168.1.10
PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
tcp.port == 80 || tcp.port == 22

Starting Nmap 7.94 at 2025-06-24 10:00 IST
Nmap scan report for 192.168.1.1
Host is up (0.0040s latency).
Not shown: 997 closed ports
PORT     STATE SERVICE
80/tcp   open  http
443/tcp  open  https
8080/tcp open  http-proxy

Nmap scan report for 192.168.1.5
Host is up (0.0020s latency).
Not shown: 995 closed ports
PORT     STATE SERVICE
22/tcp   open  ssh
139/tcp  open  netbios-ssn
445/tcp  open  microsoft-ds
3389/tcp open  ms-wbt-server
5357/tcp open  wsdapi

Nmap scan report for 192.168.1.10
Host is up (0.0050s latency).
All 1000 scanned ports on 192.168.1.10 are closed

Nmap done: 256 IP addresses (3 hosts up) scanned in 6.23 seconds
