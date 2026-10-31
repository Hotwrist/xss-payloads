# XSS Payloads

A community-oriented collection of Cross-Site Scripting (XSS) testing references, including HTML tags, event handlers, and payload examples for web application security research.

This repository brings together useful XSS testing material from existing security references and my own additions, with the goal of making common XSS testing resources easier to organize and access.

## Contents

| Directory | Description |
|---|---|
| [`tags/`](tags/) | HTML and SVG tags relevant to XSS testing. |
| [`events/`](events/) | Event-handler attributes used in XSS research and testing. |
| [`payloads/`](payloads/) | XSS payload examples for authorized security assessments. |

## Purpose

This collection is intended to support:

- Web application penetration testing.
- Bug bounty research within authorized program scope.
- XSS vulnerability discovery and validation.
- Security training and educational labs.
- Understanding HTML parsing, browser behavior, and input handling.
- Research into output encoding, sanitization, and XSS prevention.

The collection is a reference for security researchers, not a guarantee that any particular payload will work in a given application or browser.

## Sources and Attribution

A substantial portion of the material in this repository is derived from or inspired by the **PortSwigger XSS Cheat Sheet**, maintained by PortSwigger Research.

Additional entries and original contributions are included by the repository maintainer.

Primary reference:

- [PortSwigger Cross-Site Scripting (XSS) Cheat Sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet)
- [PortSwigger XSS Cheat Sheet on GitHub](https://github.com/PortSwigger/xss-cheatsheet)

Please consult the original resources for the latest updates, technical explanations, browser compatibility information, and contributor acknowledgements.

This repository is an independent collection and is not an official PortSwigger project. Attribution does not imply endorsement by PortSwigger.

Where applicable, third-party material remains subject to its original licensing and reuse terms. See [SOURCES.md](SOURCES.md) for provenance and attribution details.

## Contributions

Contributions are welcome!

You can contribute by:

- Submitting new, responsibly documented XSS test cases.
- Correcting outdated or inaccurate entries.
- Adding browser compatibility notes.
- Improving categorization and documentation.
- Suggesting improvements through GitHub Issues or Pull Requests.

When contributing, please provide the source of any third-party material and identify your original additions.

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

## Responsible Use

This repository is intended for authorized security testing, education, and defensive research.

Only test systems you own or have explicit permission to assess. Follow the applicable bug bounty program rules, scope restrictions, and responsible disclosure requirements.

Do not use these resources to access unauthorized data, compromise accounts, or harm other people or systems.

## Maintainer

Maintained by **Redhound**, a security researcher at Stodachon.

Contributions, corrections, and constructive feedback are welcome.

---

**Disclaimer:** This repository is provided for educational and security research purposes. The maintainer makes no guarantees regarding the effectiveness, compatibility, or suitability of individual entries for any particular testing environment.