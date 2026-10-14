<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/certkiln/.github/main/profile/assets/certkiln-logo-dark.png">
    <img alt="Certkiln" src="https://raw.githubusercontent.com/certkiln/.github/main/profile/assets/certkiln-logo-light.png" width="320">
  </picture>
</p>

<p align="center"><b>Simple, self-hosted certificate management for x509 and SSH.</b></p>

---

Certkiln is a web app for issuing and managing certificates without a PKI
team. Self-host it, point it at your directory, and start issuing.

**Working today**

- 🔥 **x509 certificates**: self-service issuing, renewal, and revocation from your own root or intermediate CA, with per-template key usage/EKU control
- 🔑 **SSH certificates**: short-lived user and host certificates instead of scattered `authorized_keys`
- 🔐 **LDAP/AD and OIDC login**, with RBAC scoped per CA or per template — local accounts work standalone too
- 🗝️ **Key escrow + recovery**: opt-in per template, gated behind a second admin's approval
- 📋 **CRL + OCSP**, audit logging, and renewal reminders (email or a Slack-compatible webhook) out of the box

**On the roadmap** — SAML, ACME-compatible issuance, Kubernetes/Helm, and
more: see the [main repo's ROADMAP](https://github.com/certkiln/certkiln/blob/master/ROADMAP.md).

> **Status:** pre-1.0, no stable release yet — expect breaking changes.
> Watch this organization to follow along.

**Reporting a security issue?** Please don't open a public issue. See our
[security policy](https://github.com/certkiln/.github/blob/main/SECURITY.md).
