# PRODIGY_CS_05
NETWORK PACKET ANALYZER
This tool capture and analyze the network packets in a simple way we can call it a sniffer tool. With packet sniffer tool, you can knowthe following:

Source and Destination MAC addresses,
VLAN tagging,
EtherType,
IP Headers [eg: IPv6, IPv4],
Source and Destination IP addresses, 
Port Number of your destination, 
Destination port number,
Service Identifier, 
Flag Type, 
Packet Examination,
MAC address of the sender,
Protocol Headers,
Payload data

These are some of the attributes we can know and there are many more attributes we can know by using this packet sniffer tool. 
Example:
          Ether / IPv6 / TCP 2405:201:c01e:8822:e85f:bece:f8b9:b8f1:50725 > 2606:4700:9ae3:ac57:edae:b54:a5d5:4e6e:https PA / Raw
» Breakdown of Network Packet Components:

➡ Ether: Ethernet frame header with source/destination MAC addresses, EtherType, VLAN tagging.

➡ IPv6: IPv6 header with source/destination addresses, traffic class, flow label, payload length, next header, hop limit.

➡ TCP: TCP header with source/destination port, sequence/acknowledgment number, flags, window size, checksum, urgent pointer.

➡ 2405:201:c01e:8822:e85f:bece:f8b9:b8f1:50725: Source IPv6 address.

➡ 2606:4700:9ae3:ac57:edae:b54:a5d5:4e6e: Destination IPv6 address.

➡ https: Destination port 443, commonly used for HTTPS.

➡ PA: TCP flags PUSH and ACK, indicating data transmission and acknowledgment.

➡ Raw: Packet examined in raw or unprocessed format.
