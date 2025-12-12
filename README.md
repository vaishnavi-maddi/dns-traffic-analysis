# dns-traffic-analysis

This lab captures and analyzes DNS queries and responses using Wireshark. It demonstrates how domain names are resolved and why DNS traffic is important for cybersecurity and SOC investigations.

# Process
Started packet capture on interface ens33
Visited clean test sites:
  - example.com
  - neverssl.com
  - bbc.co.uk
# Applied filters:
- dns
- dns.flags.response == 0 (queries)

Saved filtered capture as dns-traffic-s.pcapng
