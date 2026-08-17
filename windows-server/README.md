# Windows Server

## Role

Windows Server acts as the Domain Controller for:

`soclab.local`

## Services

- Active Directory Domain Services
- DNS
- Global Catalog

## Security Monitoring

The server will be monitored using:

- Windows Security Event Logs
- Sysmon
- PowerShell logging
- Splunk Universal Forwarder

## Purpose

The server provides the identity infrastructure used by the
SOC lab and generates authentication and directory-related
security telemetry.
