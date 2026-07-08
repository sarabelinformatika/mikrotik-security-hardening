# Service Hardening

## Reducing the Attack Surface

One of the most effective ways to improve the security of a MikroTik RouterOS device is to reduce its attack surface.

Every enabled service, management interface, or listening port represents a potential entry point for attackers.

The fewer services exposed, the fewer opportunities exist for unauthorized access.

Security hardening should therefore begin by identifying which services are actually required and disabling everything else.

---

# What Is the Attack Surface?

The attack surface represents every point where an attacker could potentially interact with a device.

For RouterOS, this may include:

- management services;
- remote administration interfaces;
- VPN services;
- routing protocols;
- monitoring services;
- APIs;
- discovery protocols.

Not every enabled service is necessary in every deployment.

Each unnecessary service increases overall security risk.

---

# Secure by Default

A secure deployment should expose only the services required for normal business operations.

Rather than enabling features "just in case", organizations should adopt a minimalistic approach.

Ask the following questions:

- Is this service required?
- Who needs access?
- Can access be restricted?
- Is there a more secure alternative?

If the answer is no, the service should remain disabled.

---

# Management Services

Administrative services deserve particular attention.

Examples include:

- WinBox
- SSH
- WebFig
- API
- API-SSL
- FTP
- Telnet

Whenever possible:

- disable unused services;
- restrict management access;
- allow administration only from trusted networks;
- avoid exposing management services directly to the Internet.

Remote administration should always follow the principle of least exposure.

---

# Discovery Protocols

Discovery protocols simplify device management but may also reveal valuable information to attackers.

Depending on the deployment, organizations should review:

- Neighbor Discovery
- MAC WinBox
- MAC Telnet
- Layer 2 discovery services

Limiting discovery to trusted management networks improves overall security.

---

# Remote Administration

Remote management is often necessary but should always be carefully controlled.

Best practices include:

- administrative VPN access;
- trusted management subnets;
- dedicated administrator devices;
- strong authentication;
- continuous logging.

Direct Internet exposure should be avoided whenever practical.

---

# Service Review Process

Enabled services should be reviewed regularly.

Questions administrators should ask include:

- Is this service still required?
- Who uses it?
- Is access properly restricted?
- Is there a safer alternative?
- Is the service monitored?

Regular reviews help eliminate forgotten or obsolete services.

---

# Documentation

Every enabled management service should be documented.

Documentation should include:

- purpose;
- responsible administrator;
- permitted networks;
- authentication method;
- review date.

Good documentation supports troubleshooting, auditing, and long-term maintenance.

---

# Best Practices

- Disable unnecessary services.
- Restrict administrative access.
- Use VPN for remote management.
- Limit discovery protocols.
- Document exposed services.
- Review services regularly.
- Minimize Internet-facing interfaces.

---

# Common Mistakes

Avoid:

- leaving default services enabled;
- exposing WinBox directly to the Internet;
- unrestricted WebFig access;
- unused APIs remaining active;
- forgotten legacy services;
- enabling features without operational need.

Reducing unnecessary services significantly decreases the available attack surface.

---

# Key Takeaways

- Every enabled service increases potential risk.
- Disable anything that is not required.
- Administrative interfaces should never be unnecessarily exposed.
- Regular service reviews improve long-term security.
- A smaller attack surface results in a more resilient RouterOS deployment.
