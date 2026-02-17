# Network Investigation Report (Sample)

## Investigation Summary
Detected unusual outbound DNS traffic from endpoint during packet analysis.

## Tools Used
- Wireshark
- TCP/IP packet filtering
- DNS query analysis

## Investigation Steps
- Filtered DNS traffic
- Reviewed repeated external queries
- Identified abnormal request frequency
- Checked destination domains

## Findings
Traffic pattern indicated potential command-and-control style communication.

## MITRE ATT&CK Mapping
T1071 - Application Layer Protocol

## Recommended Actions
- Block suspicious domains
- Monitor endpoint activity
- Increase DNS visibility
