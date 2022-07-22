freeBSD 64bit
install as VM

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
`em0`
```
Enter the LAN interface name or 'a' for auto-detection
```
just `enter`  
You have IP of web interface

user: `admin`
password: `pfsense`