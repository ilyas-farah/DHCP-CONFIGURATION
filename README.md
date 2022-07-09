# DHCP-CONFIGURATION
DHCP CONFIGURATION
------------------
DHCP Configuration 1
------------------
R1
-------
int g0/0/0
ip address 10.1.1.1 255.255.255.0
no shutdown

DHCP Configuration 2
---------------------
R1
----
ip dhcp pool internal
network 10.1.1.0 255.255.255.0
default-router 10.1.1.1
![DHCP LAB](https://user-images.githubusercontent.com/106605770/178120489-764e41c5-87bf-45f6-b319-761929c28971.PNG)
