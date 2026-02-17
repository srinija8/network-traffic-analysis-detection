# Wireshark Investigation Filters

## DNS Analysis
dns

## HTTP Traffic
http

## TCP Traffic
tcp

## Failed Connections
tcp.flags.reset == 1

## Suspicious Ports
tcp.port == 4444

## Filter by IP
ip.addr == 10.0.2.15

## DNS Requests Only
dns.flags.response == 0

## DNS Responses
dns.flags.response == 1

## Follow TCP Stream
Right click packet → Follow → TCP Stream
