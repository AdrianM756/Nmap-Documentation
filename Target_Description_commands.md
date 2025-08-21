Here are some of the commands and parameters for nmap.

## Target Description

On this section, you can Define exactly which IPs, ranges, or subnets to scan.
<br>

| Command | Description |
|--------|-------------|
| `nmap <IP Address>` | Scan a single IP address. |
| `nmap <IP Address>/Subnet` | Scan a subnet. |
| `nmap <IP Address range>` | Scan an IP range (e.g., `192.168.1.1-254`). |
| `nmap <domain>` | Scan a domain (e.g., `google.com`). |
| `nmap iL <filename>` | Scan IP addresses listed in a file (e.g., `IP_Address_List.txt`). |
| `nmap iR <number>` | Scan a random set of IP addresses. |
| `nmap -exclude <IP Address>` | Exclude specific IP addresses from the scan. |


***NOTE:*** By default, running this commands will also scan all the available ports of your target IP Address, IP Range, or Subnet.




