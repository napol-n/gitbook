# Lab: Hacking WordPress (HTB Lab #1)

## Objective
- Exploit vulnerable WordPress instance
- Enumerate users, plugins, themes
- Gain shell access

## Environment Setup
- Kali Linux VM
- WordPress Lab on Docker

## Steps
1. **Reconnaissance**
```bash
nmap -sV -p 80,443 target-ip
wpscan --url http://target-ip --enumerate p
