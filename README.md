# Cisco
Codes
en
conf t
hostname Arlegui
enable secret cisco
line con 0
password cisco
login
logging synchronous
line con 0 4
password cisco
logging sync
exit
int s0/0/1
ip address 192.168.1.0 255.255.255.0
no shut
exit
int g0/0
ip address 192.168.1.254 255.255.255.0
no shut
exit
