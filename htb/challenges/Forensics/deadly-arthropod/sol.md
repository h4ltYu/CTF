
$ tshark -r deadly_arthropod.pcap -T fields -e usb.capdata > out
$ sed -i '/^$/d' out
$ python sol.py
