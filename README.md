#Task1:  Scan Local Network for Open Ports

## Objective
Scan the local network for open ports using Nmap and analyze results.

## Tools Used
- Nmap (for port scanning)
- Wireshark (for packet capture)
- Kali Linux

##  What I Did
- Scanned IP range: 192.168.184.0/24 using a TCP SYN scan
- Found one open port: 53/tcp (DNS service)
- Captured packets using Wireshark and filtered TCP SYN packets
- Identified potential risks from open DNS port 
- Documented the entire process in a `.docx` report

## Files Included
- `Theertha-A_Task1.pdf`: Final report with screenshots
- `nmap_scan_result.txt`: Raw Nmap output
- `nmap_scan_capture.pcapng`: Wireshark capture file
