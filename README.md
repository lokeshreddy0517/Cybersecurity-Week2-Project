# Cybersecurity Week 2 Project

## Project Overview
Hands-on cybersecurity practical exercises covering passive OSINT footprinting and network scanning.

## Tools Used
- Kali Linux
- theHarvester 5.0.0
- Zenmap / Nmap 7.993
- Windows 11
- Git and Python

## Module PM4 – theHarvester

**Objective:** Perform passive information gathering using certificate transparency data.

- Target: `networkwalks.com`
- Source: `crt.sh`
- Activity: Passive collection

**Observed Results:**
- IP addresses: 0
- Email addresses: 0
- People: 0
- Hostnames: 0

## Module PM5 – Zenmap

**Objective:** Perform network scanning and identify open services.

- Target: `127.0.0.1`
- Scan profile: Regular scan
- Host status: Up
- Scan duration: 3.08 seconds

**Observed Open Ports:**

| Port | Service |
|---|---|
| 135/tcp | MSRPC |
| 445/tcp | Microsoft-DS |
| 3306/tcp | MySQL |

997 closed TCP ports were reported.

## Learning Outcomes
- Understanding passive OSINT techniques.
- Practicing network scanning using Zenmap.
- Identifying open ports and services.
- Documenting security observations.

## Disclaimer
This project is for educational purposes. Testing should only be performed on systems and domains for which authorization has been granted.

## Author
Lokesh Reddy

Cybersecurity Learner | Aspiring SOC Analyst
