# Code-alpha-
Packet capturing using dcapy using root kali
scapy
ls()
pkts = sniff(iface ="eth0", count=3)
pkts[0]
pkts[1]
pkts[2]
pkts.show()
hexdump(pkts[0])

