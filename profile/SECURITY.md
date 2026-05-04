# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in a Moss Apps project, please report it privately rather than opening a public issue.

**Report via GitHub:** Use the "Report a vulnerability" button on the repository's Security tab, or email a maintainer directly.

We will acknowledge your report within **48 hours** and provide a timeline for resolution within **5 days**.

## Supported Versions

Only the latest release of each project receives security patches. Older versions are not supported unless explicitly stated in the project's documentation.

## Scope

Security reports are in scope for all repositories under the [moss-apps](https://github.com/moss-apps) organization. The following areas are of particular interest:

- Encryption weaknesses in Locker's vault implementation
- Audio stack vulnerabilities in Flick Player's Rust-based UAC 2.0 layer
- Data leaks or unintended network access by any Moss Apps software

## Disclosure

We follow coordinated disclosure. After a fix is released, we will publicly acknowledge the vulnerability and credit the reporter (unless you prefer to remain anonymous).

## Safe Harbor

We consider security research conducted in good faith to be authorized and will not pursue legal action against researchers who follow this policy. Do not access or modify data belonging to other users, degrade services, or exfiltrate data beyond what is necessary to demonstrate the vulnerability.
