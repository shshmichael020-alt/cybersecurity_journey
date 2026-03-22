# Nmap Basic Scan

## What I Did
I performed a basic scan on a target system to identify open ports and services.

## Commands Used
nmap scanme.nmap.org  
nmap -F scanme.nmap.org  

## Observation
The initial scan took longer to complete, so I used a faster scan option to get results more efficiently.

## What I Found
- The host is active  
- Most ports are filtered  
- Port 22 is open and running SSH  

## What I Understand
The system appears to be secured since most ports are filtered. Only SSH service is accessible, which is used for remote access.

## What I Learned
- How to perform a basic Nmap scan  
- Difference between normal and fast scan  
- Meaning of open and filtered ports  

## Screenshot
![Scan Output 1](nmap-outputd1.1.png.png)
![Scan Output 2](nmap-output.pngd1.2.png)
