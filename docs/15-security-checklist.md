# Security Checklist

> *Security is not measured by the technologies an organization deploys, but by the consistency with which security practices are applied. This checklist summarizes the key recommendations presented throughout this guide and provides a practical framework for reviewing the security posture of a MikroTik RouterOS environment.*

---

## Purpose

This checklist is intended to support periodic security reviews of MikroTik RouterOS deployments.

Rather than serving as a compliance framework, it provides a practical reference for verifying that essential security principles have been implemented consistently across the infrastructure.

Organizations should adapt these recommendations according to their business requirements, operational risks, and regulatory obligations.

---

# System Maintenance

Verify that:

- [ ] RouterOS is running a supported Stable release.
- [ ] Device firmware is current.
- [ ] Software updates are reviewed regularly.
- [ ] Maintenance activities are documented.
- [ ] Unsupported hardware has been identified.

---

# User Management

Verify that:

- [ ] Default accounts have been reviewed.
- [ ] Every administrator has an individual account.
- [ ] Administrative permissions follow the Principle of Least Privilege.
- [ ] Strong password policies are enforced.
- [ ] Administrative accounts are reviewed periodically.
- [ ] Unused accounts have been removed.

---

# Service Hardening

Verify that:

- [ ] Unnecessary services are disabled.
- [ ] Management services are restricted.
- [ ] Administrative interfaces are not publicly exposed.
- [ ] Discovery protocols have been reviewed.
- [ ] Remote administration follows organizational policies.

---

# Firewall

Verify that:

- [ ] Firewall rules follow a Default Deny philosophy.
- [ ] Rules are documented.
- [ ] Temporary rules have been removed.
- [ ] Administrative traffic is protected.
- [ ] Network segmentation has been implemented.
- [ ] Firewall policies are reviewed regularly.

---

# VPN

Verify that:

- [ ] VPN access follows business requirements.
- [ ] Administrative VPN access is protected.
- [ ] Authentication methods have been reviewed.
- [ ] VPN users receive only required access.
- [ ] VPN activity is monitored.

---

# WireGuard

Verify that:

- [ ] Key pairs are securely managed.
- [ ] Obsolete peers have been removed.
- [ ] Access permissions are reviewed.
- [ ] Key management procedures are documented.

---

# IPv6

Verify that:

- [ ] IPv6 firewall policies exist.
- [ ] IPv6 services have been reviewed.
- [ ] Network segmentation applies to IPv6.
- [ ] IPv6 traffic is monitored.

---

# Monitoring

Verify that:

- [ ] Critical infrastructure is monitored.
- [ ] Alerts are meaningful.
- [ ] Capacity trends are reviewed.
- [ ] Monitoring dashboards are maintained.
- [ ] Critical services generate alerts.

---

# Logging

Verify that:

- [ ] Centralized logging is implemented.
- [ ] Administrative activity is logged.
- [ ] Time synchronization is accurate.
- [ ] Log retention policies are documented.
- [ ] Logs are reviewed regularly.

---

# Backup

Verify that:

- [ ] Backups complete successfully.
- [ ] Recovery procedures are documented.
- [ ] Backup integrity is verified.
- [ ] Restoration testing is performed.
- [ ] Backup repositories are protected.

---

# Maintenance

Verify that:

- [ ] Routine maintenance schedules exist.
- [ ] Documentation is current.
- [ ] Configuration reviews are performed.
- [ ] Capacity planning is reviewed.
- [ ] Administrative access is audited.

---

# Incident Response

Verify that:

- [ ] Incident response procedures are documented.
- [ ] Escalation paths are defined.
- [ ] Recovery priorities are documented.
- [ ] Security incidents are reviewed.
- [ ] Lessons learned are incorporated into operational processes.

---

# Final Review

Before considering the infrastructure adequately protected, verify that:

- [ ] Security controls follow the Principle of Least Privilege.
- [ ] Defense in Depth has been implemented.
- [ ] Administrative access is appropriately restricted.
- [ ] Monitoring and logging provide sufficient visibility.
- [ ] Backup and recovery capabilities have been validated.
- [ ] Operational procedures are documented and reviewed regularly.

---

## Conclusion

Security is not a destination.

It is an ongoing operational discipline that combines technology, people, and well-defined processes.

Organizations that regularly review their infrastructure against a structured security checklist are better prepared to reduce operational risk, respond to changing threats, and maintain resilient network environments over time.

This checklist should be used as part of a continuous improvement process rather than a one-time audit exercise.

---

## Further Reading

- [RouterOS Updates](03-routeros-updates.md)
- [Firewall Best Practices](06-firewall-best-practices.md)
- [VPN Security](07-vpn-security.md)
- [Monitoring](10-monitoring.md)
- [Incident Response](14-incident-response.md)

---

**Back to the beginning →**

[Introduction](01-introduction.md)
