# MikroTik Security Hardening Guide

> Enterprise MikroTik RouterOS security hardening guide, operational best practices and security checklist for business environments.

![License](https://img.shields.io/badge/License-MIT-green.svg)
![RouterOS](https://img.shields.io/badge/RouterOS-v7-blue)
![Documentation](https://img.shields.io/badge/Documentation-In%20Progress-orange)

---

## Overview

Securing a MikroTik RouterOS device requires much more than changing the default password or applying a few firewall rules.

This project is a comprehensive security hardening guide for MikroTik RouterOS, focusing on operational best practices, defense-in-depth principles, and long-term maintainability rather than copy-and-paste configurations.

The guide is intended for system administrators, IT professionals, MSPs, consultants, and organizations that rely on MikroTik devices in business environments.

---

## Goals

This repository aims to help organizations:

- Improve the security of MikroTik RouterOS deployments.
- Reduce the attack surface.
- Implement security best practices.
- Strengthen remote access security.
- Improve monitoring and incident detection.
- Develop a long-term security strategy.
- Build secure and maintainable network infrastructures.

---

## Who is this guide for?

This guide is intended for:

- System Administrators
- Network Engineers
- Managed Service Providers (MSPs)
- IT Consultants
- Small and Medium-sized Businesses (SMBs)
- Enterprise IT Teams
- Anyone responsible for MikroTik RouterOS security

---

## What this guide is **not**

This repository intentionally avoids:

- Ready-to-use production configurations
- Customer-specific RouterOS exports
- Copy-and-paste firewall rules
- One-size-fits-all security recommendations

Every organization has different business requirements, network architectures, compliance obligations, and risk profiles.

Instead, this guide explains **why** security controls matter and **how** they should be implemented as part of an overall security strategy.

---

# Documentation

| Chapter | Description |
|---------|-------------|
| [01 - Introduction](docs/01-introduction.md) | Introduction and security philosophy |
| [02 - Threat Model](docs/02-threat-model.md) | Understanding the modern threat landscape |
| [03 - RouterOS Updates](docs/03-routeros-updates.md) | Keeping RouterOS secure |
| [04 - User Management](docs/04-user-management.md) | Accounts, authentication and permissions |
| [05 - Service Hardening](docs/05-service-hardening.md) | Reducing the attack surface |
| [06 - Firewall Best Practices](docs/06-firewall-best-practices.md) | Firewall design principles |
| [07 - VPN Security](docs/07-vpn-security.md) | Secure remote connectivity |
| [08 - WireGuard](docs/08-wireguard.md) | WireGuard security recommendations |
| [09 - IPv6 Security](docs/09-ipv6-security.md) | IPv6 security considerations |
| [10 - Monitoring](docs/10-monitoring.md) | Monitoring RouterOS environments |
| [11 - Logging](docs/11-logging.md) | Logging and audit trails |
| [12 - Backup Strategy](docs/12-backup.md) | Backup and recovery planning |
| [13 - Maintenance](docs/13-maintenance.md) | Secure operational maintenance |
| [14 - Incident Response](docs/14-incident-response.md) | Responding to security incidents |
| [15 - Security Checklist](docs/15-security-checklist.md) | Enterprise security checklist |

---

# Security Principles

This guide follows several core security principles:

- Defense in Depth
- Least Privilege
- Secure by Default
- Continuous Monitoring
- Regular Maintenance
- Risk-based Decision Making
- Operational Simplicity

---

# Future Topics

Additional documentation may include:

- High Availability
- Routing Security
- VLAN Security
- Zero Trust Networking
- Multi-factor Authentication
- SIEM Integration
- Certificate Management
- Secure Remote Administration
- Automation
- Compliance

---

# Contributing

Contributions are welcome.

If you discover inaccuracies, outdated information, or would like to improve this guide, feel free to open an Issue or submit a Pull Request.

---

# License

This project is licensed under the MIT License.

---

# About SARABEL Informatika

SARABEL Informatika provides professional IT infrastructure services, network administration, cybersecurity consulting, monitoring solutions, virtualization, backup strategies, and enterprise IT operations for businesses.

Our mission is to help organizations build secure, reliable, and maintainable IT environments through practical expertise and modern technologies.
