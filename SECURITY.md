# Security Policy

Certkiln manages certificates and private keys, so we take security reports
seriously and appreciate responsible disclosure.

## Supported versions

Certkiln is in early development and has no stable release yet. Security fixes
go to the latest version on the default branch. This section will list
supported release lines once versioned releases begin.

## Reporting a vulnerability

**Please do not report security vulnerabilities in public issues, discussions,
or pull requests.**

Email **security@certkiln.dev** with a description of the issue, steps to
reproduce, affected versions, and the potential impact. This is the
reliable path — GitHub's private vulnerability reporting (Security tab →
**Report a vulnerability**) isn't available on every repository (it
requires the repository to be public), so don't assume that button is
there before falling back to email.

If a repository does have private vulnerability reporting enabled, using
it instead of email is also fine — either reaches the maintainers
privately.

## What to expect

- **Acknowledgement** within 5 business days.
- **An initial assessment** (confirmed, needs more information, or not a
  vulnerability) within 14 days.
- **Coordinated disclosure:** we'll agree on a disclosure timeline with you,
  publish a GitHub Security Advisory once a fix is available, and credit you
  unless you'd rather stay anonymous.

## Scope

In scope: the Certkiln application, its official container images, and the
code in repositories under the [certkiln](https://github.com/certkiln)
organization.

Out of scope: vulnerabilities in third-party dependencies that have no
Certkiln-specific impact (please report those upstream), and findings that
require a compromised host or administrator account.
