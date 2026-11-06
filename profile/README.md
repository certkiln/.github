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

- **x509 certificates**: self-service issuing and revocation from your own root or intermediate CA, with per-template key usage/EKU control
- **SSH certificates**: user certificates with per-template validity and KRL revocation, instead of scattered `authorized_keys`
- **Login and access**: LDAP/AD, OIDC, SAML, and local accounts, with optional Duo MFA for local and LDAP logins and RBAC scoped per CA or per template
- **Key escrow and recovery**: opt-in per template, with each recovery approved by someone other than the requester
- **Revocation and operations**: CRL, OCSP, audit logging, encrypted backups, and renewal reminders (email or a Slack-compatible webhook)
- **Automation and key storage**: API tokens for scripted issuance, and PKCS#11 HSM support for CA keys

> **Status:** pre-1.0, no stable release yet, so expect breaking changes. The
> source repository is currently private, and planned work is tracked in its
> roadmap. Follow this organization to keep up.

**Found a bug or have an idea?** [Open an issue](https://github.com/certkiln/.github/issues/new/choose).

**Reporting a security issue?** Please don't open a public issue. See our
[security policy](https://github.com/certkiln/.github/blob/main/SECURITY.md).
