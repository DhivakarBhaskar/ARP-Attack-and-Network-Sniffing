# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
```
ipconfig
arp -a
```
## OUTPUT:
<img width="1182" height="891" alt="image" src="https://github.com/user-attachments/assets/64fc14b2-dd60-4a27-afd1-7cfb1ff9f694" />


From Parrot OS issue the command :
<img width="1066" height="816" alt="image" src="https://github.com/user-attachments/assets/b2bd8aa7-a97c-4bcf-80fe-cd6800434ef1" />
<img width="775" height="157" alt="image" src="https://github.com/user-attachments/assets/ac732e2a-d057-441f-b6aa-931ee21eae9d" />
<img width="771" height="112" alt="image" src="https://github.com/user-attachments/assets/a8294bdb-272c-4fd7-877a-612d0fd1c31c" />

dsniff:
dsniff is a collection of network auditing and traffic analysis tools used to examine network traffic.

Install dsniff using:
```
sudo apt update
sudo apt install dsniff -y
```
```
dsniff -h
dpkg -L dsniff
```
## OUTPUT:

<img width="965" height="887" alt="image" src="https://github.com/user-attachments/assets/67d6531c-6165-4e96-ad76-79f9083e4474" />

Metasploit Framework:
Metasploit is a penetration-testing framework used for security testing and vulnerability assessment.

Open Metasploit using:
 
msfconsole

<img width="777" height="702" alt="image" src="https://github.com/user-attachments/assets/2ca6b339-c7ac-496e-8abe-3b1f17c99340" />
```
search type:auxiliary ftp
```

<img width="537" height="402" alt="image" src="https://github.com/user-attachments/assets/a1acbb68-b82d-4ac9-afdf-2459b1239e0a" />


Invoke the wireshark and examine the various menus  and controls of the tool:
```
sudo wireshark
```
<img width="541" height="492" alt="image" src="https://github.com/user-attachments/assets/01d33fce-2819-4ead-97d6-91cb9b98af7b" />

<img width="540" height="337" alt="image" src="https://github.com/user-attachments/assets/2fb76e37-2bd4-4a5b-b810-6e4651822037" />
ARP packet:
<img width="541" height="536" alt="image" src="https://github.com/user-attachments/assets/3651241d-9f33-4d79-a4c2-378542c23d03" />
Ettercap:
Ettercap is a network security tool that supports active and passive network analysis and host discovery.

Open Ettercap using:
```
sudo ettercap -G
```
Explore the following menus:

Sniff
Hosts
Targets
View
Plugins
Examine the graphical interface and network analysis features.
<img width="540" height="332" alt="image" src="https://github.com/user-attachments/assets/5162fa0f-391d-41e7-9b74-fbe9a2334f4e" />
tcpdump:
tcpdump is a command-line network packet analyzer used to capture and examine network traffic.

Check the installed version using:
```
tcpdump --version
```
```
sudo tcpdump -D
```
<img width="780" height="350" alt="image" src="https://github.com/user-attachments/assets/bfb2c1b9-850b-46b9-bd1f-d36f0072645c" />
Capture ARP packets on the active interface using:
```
sudo tcpdump -i enp0s3 arp
```
OUTPUT:
![Uploading image.png…]()

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
