# Nmap Cheatsheet

Nmap is a network scanning tool used to discover hosts, services, open ports, and possible vulnerabilities.

## Basic Scans

- `nmap 192.168.1.1` — scans a single target
- `nmap 192.168.1.0/24` — scans a network range
- `nmap -sV 192.168.1.1` — detects service versions
- `nmap -O 192.168.1.1` — detects operating system
- `nmap -A 192.168.1.1` — aggressive scan

## Port Scanning

- `nmap -p 22 192.168.1.1` — scans one port
- `nmap -p 1-1000 192.168.1.1` — scans port range
- `nmap -p- 192.168.1.1` — scans all ports

## Cybersecurity Use

Nmap helps security professionals identify exposed services, misconfigurations, and possible attack surfaces during authorized security testing.

## Important Note

Only scan systems you own or have permission to test.
