next-gen firewall

freeBSD 64bit
install as VM
give it 2 NIC:
	bridged (or NAT) for connection with WAN
	NAT (or host-only) network for LAN

### First installation try - partitioning automatically using BIOS
remember to delete optic installation drive (after installation ofc)
(ZFS has some other method accessing MBR than BIOS and UEFI)

First start:
```
Should VLANs be set up now? em0: link state changed to UP
```
`n`
```
Enter the WAN interface name or 'a' for auto-detection
```
`em0` (bridged NIC)
```
Enter the LAN interface name or 'a' for auto-detection
```
`em1` (LAN NIC)
You have IP of web interface

user: `admin`
password: `pfsense`

`2) Set Interface(s) IP address`
to set LAN NIC IP address, gateways and turn on DHCP


