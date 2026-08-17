# SOC Home Lab — Active Directory, Detection & SIEM

## Overview

This project documents a virtual Security Operations Center (SOC)
environment built using VMware Workstation.

The lab simulates a small enterprise environment containing:

- Windows Server Domain Controller
- Windows endpoint
- Kali Linux attack machine
- Splunk SIEM

The goal is to simulate security activity, collect endpoint and
authentication telemetry, develop detections, and investigate
security events.

## Lab Architecture

| System | Role |
|---|---|
| Windows Server | Active Directory / DNS / Domain Controller |
| Windows 10 | Windows Endpoint |
| Kali Linux | Attack Simulation |
| Splunk Server | SIEM / Log Analysis |

## Active Directory

Domain: `soclab.local`

The Windows Server provides:

- Active Directory Domain Services
- DNS
- Global Catalog
- User and computer management
- Authentication services

## Security Monitoring

The Windows environment is monitored using:

- Windows Security Event Logs
- Sysmon
- PowerShell logging
- Splunk Universal Forwarder
- Splunk Enterprise

## Objectives

- Build a virtual SOC environment
- Deploy Active Directory
- Monitor Windows endpoints
- Collect security telemetry
- Simulate authorized security activity
- Create Splunk detections
- Investigate suspicious activity
- Map findings to MITRE ATT&CK
- Develop SOC investigation skills

## Technologies

- VMware Workstation
- Windows Server
- Active Directory Domain Services
- DNS
- Windows 10
- Kali Linux
- Splunk Enterprise
- Sysmon
- Splunk Universal Forwarder
- Windows Event Logs
- PowerShell