# ARP Spoofer

The following Python script allows you to spoof the MAC address of a device connected to a network as well as spoofing the MAC address of the router, forcing both devices to update their ip tables so that you can become the man in the middle. This is very useful in penetration testing because it can help mitigate denial of service, man in the middle and session hijacking attacks.

- You will need to install the scapy module before running this script: 

`pip install scapy`

- To run this script: 

`sudo python arp-spoofer.py -t [target-ip] -g [gateway-ip]`

- For more information: 

`python arp-spoofer.py --help`

## Output

![output](./image/output.png)

**Note**: *This script was developed to work on Linux distributions only.*

# Legal Disclaimer

The use of code contained in this repository, either in part or in its totality, for engaging targets without prior mutual consent is illegal. It is the end-user's responsibility to obey all applicable local, state and federal laws.

The use of this code is only endorsed by the developers in those circumstances directly related to educational environments or authorized penetration testing engagements whose declared purpose is that of finding and mitigating vulnerabilities in systems, limiting their exposure to compromises and exploits employed by malicious agents as defined in their respective threat models.