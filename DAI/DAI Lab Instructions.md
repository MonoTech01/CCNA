# Dynamic ARP Inspection - DAI

# Q&A
How does a switch knows what the correct layer 3 and layer 2 combos for each of the hosts?

It takes info from DHCP snooping!!!!!!

That is why I need to check DHCP snooping to be enabled and see DHCP binding, DAI has something to work with!

Command:

show ip dhcp binding

## 1. Set g3/3 as a trusted port
## 2. Apply DAI for VLAN 30 - Network: 10.16.20.0/24
## 3. Verify

