# oui_lookup.sh

This script will parse either a single MAC address or a file containing MAC addresses(One MAC per line). You can use a local file with Base16 OUI strings to match, download a file on the fly, or for single MAC addresses you can simply parse a URL hosting an OUI txt file. The end result/output is a vendor name belonging to the OUI portion of the MAC. It is CSV friendly, meaning you can append or prepend a comma(or any string for that matter) with the output (the contents of the original line contaning the MAC is included when parsing a file). 

See help function in script for details.

Sources below are for pre-download of oui files

http://linuxnet.ca/ieee/oui/nmap-mac-prefixes

http://standards-oui.ieee.org/oui.txt
