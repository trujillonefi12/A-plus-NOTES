# A+ 1201 notes 
This are the notes for taking my A+ certification test


Laptops
Lithium Ion / Lithium Ion polymer 
charging the battery will not affect capacity
Keyboard
Memory Module - small outline (SO-Dimm)
ssd or magnetik disk m.2
wireless network 802.11

'cellular' phones
networks   
SIM carrier and user 
Esim
GPS created by us department of defense.
COPE device
Company owned personally enabled
MDM 
seems to be to for the mobile device manager for controlling phones (something like ninja)


2.1 Introduction to IP
A series of moving vans through ethernet,dsl, or cables
TCP or UDP packets 
Client -> Ethernet Header - Ethernet Payload - Ethernet Trailer -> Server
Client -> Ethernet Header - IP - Ethernet Payload - Ethernet Trailer -> Server
Client -> Ethernet Header - IP | TCP - TCP Payload - Ethernet Trailer -> Server

Transmission Control Protocol like a phone call
Reliable delivery because it has ACKowledge

User datagram Protocol
unreliable delivery
Connectionless, everything is just sent. Real time 
DHCP automatically assign IP addresses // TFTP small data across the network
IP address / Port name where is the information sent
Non-ephemeral ports - permanent ports
any value between 0-65535 they are for communication

Port Numbers
FTP tcp/20 data transfer
tcp/21 control 
SSH tcp/22 secure shell encrypted communication
tcp/23 telnet
SMTP tcp/25 mail transfer send
Receive email POP3 tcp/110 IMAP tcp/143 internet message access 
DNS udp/53 
DHCP udp/67, udp/68 requires a server
http tcp/80 - https tcp/443
dynamic pooled
Server Message Block netbios udp/137 tcp/139
Ldap lightweight directory access tcp/389
RDP tcp/3389

2.2 Wireless Tesch
802.11 networks 
ac wifi 5
ax wifi 6 
 be wifi 7
 
RFID 
- Access badges 
- Inventory/assembly
-PEt/animal id
- Anyhthing that needs to be tracked

NFC
Two way communication (paying) 
card identification

2.3 Network Services
Fileshare
Mail server
Syslog - log files
Web Server 
Authentication server
database server
NTP server - network time protocol / NTP client in pc's
Spam gateways
All in one security appliance firewall,spam filter, url filterut, utm,vpn endpoint
Load balancer for fault tolerance
Proxy server intermediate server 
SCADA/ICS - systems to control and data acquisition
legacy systems - old important stuff
IoT internet of things
Appliances , air control, smart devices
 
2.4 DNS domain name system **
nslookup anywebsite
some ip addresses that will serve if some of them fall down.
query will come to the DNS server and then look for that configuration.
a record for ipv4 
aaaa for ipv6 TTL time to live
MX records 
DKIM record
spf - sender policy framework ou can create a dns record for txt to be more safe
Dmarc - like authentication ? 
	DHCP dynamic host configuration protocol with Dora
	A device sends a broadcast over udp/68 to the DCHP server and then the server makes and offer 
the device accepts it and sends back an ack to lock in the lease of that ip address. Seems like you
dont really need to be connected already to broadcast. It has a DHCP scope for many ip addresses
Pools from IP addresses where the server can choose from. You can specify the range within the submask.
LANs
Broadcast domain
VLAN better use of switches. Many vlans in one switch. Youll have to use a router bc broadcast domain?
VPN encryots information concentrator encrypts and decrypts the information for it to be safe.
Site to site vpn 

2.5 Network Devices
Routers OSI lvl 3 switches one ip subnet to another

Switches many ports 
Unmanaged switches - no management protocols
Managed Switches - VLAN support, traffic support, redundancy support
access points gives more space 
Cable infraestucture 
Firewalls could act as proxy filters traffic by port number encrypts traffic formof and on
Power over Ethernet 
Cable modem DOCSIS devices coax cable
The complete quote reads as follows:

ONT big cable
2.6 IPv4 IPv6
4 32 bits 4 octects 1 byte 0-255 / RFC 1918
6 128 bits 16 bytes 
Assigninng Ip adrress

10.0.0.0/8
	->Range: 10.0.0.0 → 10.255.255.255
172.16.0.0/12
	->Range 172.31.255.255
192.168.0.0/16
	->Ramge 192.168.255.255

APIPA 
169.254.0.0/16
	-> range 164.254.255.255

169.254.0.0/16
2.7 Internet Connection Types
satellite networking a lot of latency 
rain fade 
Fibrt
cellular networks
cable television 
Wireless internet service provider WISP
NETWORK TYPES
Local Area Network 
Virtual Local Area network
Wide area network (lans acrross distance)
Personal area networka
Wireless lan wlan

2.8 Network tools
cable crimper
modular conectors
Wifi analyzer to check the health, frequencies/channels who's connected
Tone generator is to find the end of the cables with the tone probe
Punch down tool 
cable tester- to check the pins
Taps and port mirrors SPAN swtiched port analyzer

3.1 Display types

Liquid crystal display - light shines through liquid crystals. TN (Twisted nomatic not good colors) (ips in plane switching excellent color ) 
Organic light emitting diode - no backlight its the same oght emitting diodes.
Mini LED mini liquid 
Touchscreen - digitezer converts the input to coordinates 
Backlight and inverter 
depending on the LCD displays if its fluorecscent or not, it may or not need a inverter
if it uses Direct current from the laptop or alternating current, if its alternating current
and fluorecent it will for surely need a inverter
pixel density



NOTES: AMDV is a setting for virtualization allowance in the AMD chips or cpu's
        VDI Virtual desktop Infraestructure -. dektop as a service
WIFI NOTES : 802.11ax - wifi 6 = 2.4ghz and 5 ghz
             Wifi 6E - 6ghz 
			 
			 POWER ON SELF TEST POST CARD
			 
			 Optical Network Terminal is used to convert from fiber to copper
			 

		
3.2 network cable categories
coaxial  f-connector
shiielded twisted pair cable 
utp
Plenum space 
Structured cabling standards
International ISO/IEC 11801 cabling standards 
t568a - b the b usually uses b

FIBER OPTIC not copper- many kilometers without regenerating the singal
Types of optic fiber connectors - SC (subscriber connector)
									ST (Straight tip (bayonet function))
									LC (lucent connector)
									
or a lot of interferance. There are many types of fiber optics. Its basically a 
light or a laser reflecting it.
Multimode fiber about 2 km in legnght
Singlemode fiber 100km
Video Cables
Universal serial bus usb 1.1 - 2.0 - 3.0 
Standard A plug 
Stnadrd B plug printer
micro b
king usb-c
thunderbolt
SATA serial atattachment  

Memory types 3.3
RAM 
SSD HDD
DIMM dual inline memory moduel
Even parity in bits in the memory

3.4
Hard DISK DRIVE hdd - spinnning platter - spindle - actuator to move the arm and the head
SSD solid state drives 
Pcie express could also be used for ssds
nvme  m.2 interface 
SAS drive are different in the connectors or interface
optical drive or cd

3.5 MOBOS
atx - mini atx - itx
PCI was an old version of PCIexpress i beleive express is 40gb and pci 20
thunderbolt 4 is 40
PCIexores
m.2
headers to get lights up or usbs


3.7 Multifunction devices
Firmware for every device, and printer drivers
PCL or Postscript which is the languiage that printers use.
MOstly printers
Duplex process both sides of the page. Orientation.
badging. audit logs for printer security. 
Flatbed scannner

3.8 Laser printers
Laser printer calibration for toner.

4.1 Virtualization
The hypervisor is what cibstrls everything there can be type 1 which is bare metal or type 2 which is virtualized. 
Containerization is another type of testing apps within the same os

4.2 Cloud DEployment
Public - everyone on the internet 
Private - your own virtualizesd
Hybrid -  mix of them i guess some services public and some private
community 
IaaS
Paas
Saas

INTERNAL/PRIVATE cloud
external/public cloud ... metered / nonmetereed


TROUBLESHOOTING 
POST 
