Here are some of the commands and parameters for nmap.

## Target Description

On this section, you can Define exactly which IPs, ranges, or subnets to scan.
<br>

To scan a singling IP Address.
```
nmap <IP Address>
```
<br>

To scan a subnet.
```
nmap <IP Address>/Subnet
```
<br>

To scan an IP range.(ex. 192.168.1.1-254)
```
nmap <IP Address range>
```
<br>

To scan a domain.(ex. google.com)
```
nmap <domain>
```
<br>

```iL``` To scan a an ip address inside a file.(ex. IP_Address_List.txt)
```
nmap iL <name of the text file>
```
<br>

```iR``` To scan random ip address.
```
nmap iR <number of random IP Address>
```
<br>

```-exclude``` To exclude an IP address to scan.
```
nmap -exclude <IP Address that you want exclude>
```
<br>

***NOTE:*** By default, running this commands will also scan all the available ports of your target IP Address, IP Range, or Subnet.




