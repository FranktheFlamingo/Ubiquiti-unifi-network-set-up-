Ubiquiti-unifi-network-set-up-
Configuring a unifi network for radius authentication  via MAC addresses and 802.1 X

#Goal:
Setting up an Home network consisting of three SSID's with different levels of trust and access.

#SSID breakdown:
Personal - full local trust, allow related and established web access, drop all new external request in
IOT - partial local trust, allowed to respond to enter request and talk to other IOT devices ##internally, zero trust to outside network, local IOT network access only
Guest - zero trust to personal network or IOT network, Captiva portal login managed for access.

#Hardware infrastructure:
Switching from Arris 8200 with Linksys MX 4200 Velop mash routers to a Unifi set up in order to have ##more network management ability to achieve this. I've currently kept the Arris 8200 modem but I've ##swapped the link to unit for 2 - Unifi Express – UX units. One operates the gateway and main access ##point for the networks and the other meshes in wirelessly. I've also added a Standard 24 - USW 24 ##switch from ubiquity. has brought a lot of options and opportunities for network security that weren't ##present on my previous system.

#Security protocols:
Radius 802.11X MAC Authentication
Dynamic DNS
Network firewall rules
NTP
Network and device isolation
VLANS
L3 ACL Network Isolation

#To better understand [The OIS Model and the 7 Layers of a Networking](https://www.freecodecamp.org/news/osi-model-networking-layers-explained-in-plain-english/) - Check out this awesome breakdown that is as she puts it "IN PLAIN ENGLISH" 
