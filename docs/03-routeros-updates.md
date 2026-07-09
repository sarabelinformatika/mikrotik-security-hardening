# RouterOS Updates

## Keeping RouterOS Secure

Keeping MikroTik RouterOS up to date is one of the most effective ways to reduce security risks.

Every software platform contains bugs, implementation flaws, and security vulnerabilities. As new issues are discovered, MikroTik regularly releases updates that improve stability, resolve defects, and address security-related problems.

Running an outdated RouterOS version unnecessarily increases the organization's attack surface.

Software maintenance should therefore be considered a core component of every security strategy rather than an optional administrative task.

---

# Why Updates Matter

RouterOS updates provide much more than new features.

Regular updates may include:

- security vulnerability fixes;
- authentication improvements;
- networking protocol enhancements;
- performance optimizations;
- bug fixes;
- hardware compatibility improvements;
- stability improvements.

Organizations that delay updates often expose themselves to publicly known vulnerabilities that attackers can easily identify and exploit.

---

# Risks of Running Outdated RouterOS Versions

Outdated devices may suffer from:

- publicly documented vulnerabilities;
- unsupported software versions;
- reduced compatibility with modern technologies;
- software defects affecting stability;
- weaker security mechanisms.

Internet-wide scanning systems continuously identify vulnerable RouterOS versions.

Attackers frequently prioritize known vulnerabilities because they require significantly less effort than discovering new ones.

---

# Establish an Update Policy

Software updates should follow a documented maintenance process.

A typical update policy includes:

- regular review of available RouterOS releases;
- testing updates before production deployment;
- scheduling maintenance windows;
- creating backups before every upgrade;
- verifying successful upgrades;
- monitoring system health after updates.

A structured process significantly reduces operational risk.

---

# Stable vs Testing Releases

Organizations should understand the difference between release channels.

### Stable

Recommended for production environments.

Stable releases undergo extensive testing and are intended for long-term operational reliability.

---

### Testing

Designed for evaluation purposes.

Testing releases may include new functionality but can also introduce unexpected issues.

Business-critical environments should generally avoid deploying testing releases unless specific features require them.

---

# Backup Before Every Upgrade

Every RouterOS upgrade should begin with a verified backup.

Recommended backup procedures include:

- configuration export;
- encrypted binary backup;
- secure off-device storage;
- version tracking;
- restoration testing.

Backups are only valuable if they can be successfully restored.

---

# Verify the Upgrade

An update should never be considered complete immediately after installation.

Administrators should verify:

- RouterOS version;
- package integrity;
- interface status;
- routing functionality;
- VPN connectivity;
- firewall operation;
- monitoring systems;
- logging functionality;
- backup schedules.

Verification ensures that normal business operations continue without interruption.

---

# Maintenance Windows

Software updates should be performed during planned maintenance windows whenever possible.

Benefits include:

- reduced business impact;
- easier rollback planning;
- improved communication with users;
- lower operational risk;
- controlled troubleshooting.

Unplanned updates during business hours may increase service disruption.

---

# Long-Term Maintenance

RouterOS maintenance should be viewed as an ongoing lifecycle.

Organizations should regularly:

- review firmware versions;
- monitor security advisories;
- retire unsupported hardware;
- document maintenance activities;
- verify backup integrity;
- assess operational risks.

Security is maintained through continuous improvement rather than occasional intervention.

---

# Best Practices

- Keep RouterOS up to date.
- Use Stable releases for production.
- Test upgrades before deployment.
- Always create backups before updates.
- Verify all critical services after upgrading.
- Maintain documented update procedures.
- Schedule regular maintenance windows.

---

# Common Mistakes

Avoid the following practices:

- postponing updates indefinitely;
- upgrading without backups;
- updating production devices without testing;
- ignoring firmware compatibility;
- failing to verify services after upgrades;
- lacking a documented maintenance process.

---

# Key Takeaways

- RouterOS updates are a fundamental security control.
- Delayed updates increase organizational risk.
- Every upgrade should follow a documented process.
- Stable releases are recommended for production environments.
- Backups and post-upgrade verification are essential components of secure maintenance.

---

## Further Reading

- [Threat Model](02-threat-model.md)
- [User Management](04-user-management.md)
- [Service Hardening](05-service-hardening.md)

---

**Next Chapter →**

[User Management](04-user-management.md)
