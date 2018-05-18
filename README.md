# Zabbix-UCS
UCS Manager Templates for Zabbix

Using https://github.com/cavaliercoder/mib2zabbix, I downloaded and converted the entirety of the MIB base for Cisco's UCS Manager. See Cisco's Documentation: https://www.cisco.com/c/en/us/td/docs/unified_computing/ucs/sw/mib/b-series/b_UCS_MIBRef/UCS_MIBRef_chapter_01000.html 

The Templates currently are a raw conversion.  In future commits, I'm going to update had modified templates. The conversion process moved the structure over and is about 90% useable, but further optimization is required, which needs to be done by hand.
 
Hoping the community will contribute additional use cases (ideally modifications to triggers, items, and Discovery Rules and associated Item Prototypes). In my case, my UCS infrastructure is al
l SAN Booting, my Authentication is via LDAP, and as such, can only test/optimize for those functions. 
