# Introduction

## Why MikroTik Security Matters

MikroTik RouterOS has become one of the most widely deployed networking platforms in small and medium-sized businesses, educational institutions, Internet Service Providers, hospitality environments, and enterprise branch offices.

Its flexibility, powerful feature set, and competitive pricing make it an excellent choice for professional network deployments.

However, flexibility also introduces responsibility.

A default installation or a poorly maintained RouterOS device may expose unnecessary services, outdated software components, weak authentication mechanisms, or insecure management interfaces. These weaknesses can increase the attack surface and provide opportunities for unauthorized access.

Modern cyber threats continue to evolve.

Organizations are no longer targeted only by skilled attackers. Automated scanning systems continuously search the Internet for vulnerable devices, outdated RouterOS versions, exposed management services, weak credentials, and known vulnerabilities.

For this reason, securing a MikroTik router should never be treated as a one-time configuration task.

Security is an ongoing operational process.

---

# Purpose of this Guide

This guide provides practical security recommendations for deploying and maintaining MikroTik RouterOS in business environments.

Rather than providing copy-and-paste configurations, this documentation explains the reasoning behind each security recommendation.

The objective is to help administrators make informed decisions based on:

- business requirements;
- operational needs;
- risk assessment;
- long-term maintainability;
- security best practices.

---

# Security is a Process

A secure RouterOS deployment is not achieved by applying a single firewall rule or changing the default administrator password.

Effective security combines multiple layers of protection, including:

- secure system configuration;
- access control;
- regular software updates;
- network segmentation;
- VPN security;
- continuous monitoring;
- logging and auditing;
- backup and disaster recovery;
- operational procedures.

Each layer reduces overall organizational risk.

---

# Defense in Depth

This guide follows the principle of **Defense in Depth**.

Instead of relying on one security mechanism, multiple independent protective controls should work together.

Examples include:

- restricting management services;
- applying firewall filtering;
- enforcing strong authentication;
- monitoring suspicious activities;
- maintaining regular backups;
- limiting administrative access;
- documenting operational procedures.

If one control fails, additional layers continue to protect the infrastructure.

---

# Scope

This guide focuses on enterprise and business deployments of MikroTik RouterOS.

Topics include:

- RouterOS hardening
- User and permission management
- Secure remote administration
- Firewall principles
- VPN security
- Logging
- Monitoring
- Maintenance
- Backup strategies
- Incident response

The guide intentionally avoids customer-specific implementations or configuration exports.

---

# Target Audience

This documentation is intended for:

- Network Administrators
- System Administrators
- Managed Service Providers (MSPs)
- IT Consultants
- Enterprise IT Teams
- Small and Medium-sized Businesses

Although the examples are based on MikroTik RouterOS, many security principles described here can also be applied to other enterprise networking platforms.

---

# Guiding Principles

Throughout this guide, every recommendation follows five core principles:

1. Reduce the attack surface.
2. Protect administrative access.
3. Keep systems continuously maintained.
4. Detect problems before they become incidents.
5. Build resilient network infrastructures.

These principles form the foundation of every chapter that follows.

---

## Further Reading

- [Threat Model](02-threat-model.md)
- [RouterOS Updates](03-routeros-updates.md)
- [User Management](04-user-management.md)

---

**Next Chapter →**

[Threat Model](02-threat-model.md)
