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
