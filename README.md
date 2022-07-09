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

