# Flux Security

This document defines security reporting, handling, disclosure, and audit information for the Flux project and community.

Also see our [Flux Security documentation](https://fluxcd.io/flux/security) landing page for an overview of project security information geared toward end users.

## Security Process

### Report a Vulnerability

We're very thankful for – and if desired happy to credit – security researchers and users who report vulnerabilities to the Flux community.

- To make a report please email the private security list at <cncf-flux-security@lists.cncf.io> with the details.
  We ask that reporters act in good faith by not disclosing the issue to others.
- You may, but are not required to, encrypt your email to this list using the PGP keys of Security Team members, listed below.
- The Security Team will fix the issue as soon as possible and coordinate a release date with you.
- You will be able to choose if you want public acknowledgement of your effort and how you would like to be credited.

### Security Team

Current Security Team members:

| Name | GitHub | Key URL | Fingerprint |
| -- | -- | -- | -- |
| Scott Rigby | [@scottrigby](https://github.com/scottrigby) | <https://keybase.io/r6by/pgp_keys.asc> | 208D D36E D5BB 3745 A167 43A4 C7C6 FBB5 B91C 1155 |
| Hidde Beydals | [@hiddeco](https://github.com/hiddeco) | <https://keybase.io/hidde/pgp_keys.asc> | C910 7A9B 55A4 DD77 062B 9731 B6E3 6A6A C54A CD59 |
| Matheus Pimenta | [@matheuscscp](https://github.com/matheuscscp) | <https://keybase.io/matheuscscp/pgp_keys.asc> | B404 C733 A16F 589B 592A 4FD7 86D8 78C7 79EB 9A95 |
| Stefan Prodan | [@stefanprodan](https://github.com/stefanprodan) | <https://keybase.io/stefanprodan/pgp_keys.asc> | 613B F2C4 D985 BBCB 1474 123F 5A00 A045 0068 3EBD |

### Handling

- All reports are thoroughly investigated by the Security Team.
- Any vulnerability information shared with the Security Team will not be shared with others unless it is necessary to fix the issue.
  Information is shared only on a need to know basis.
- As the security issue moves through the identification and resolution process, the reporter will be notified.
- Additional questions about the vulnerability may also be asked of the reporter.
- Note that while Flux is very active it is a vendor-neutral CNCF project maintained by volunteers, not by a single company. As such, security issue handling is done on a best-effort basis.
  Talk to us if you are interested in getting involved with this work! :-)

### Disclosures

Vulnerability disclosures are emailed to the Flux Dev mailing list <https://lists.cncf.io/g/cncf-flux-dev> and announced publicly.
Disclosures will contain an overview, details about the vulnerability, a fix that will typically be an update, and optionally a workaround if one is available.

We will coordinate publishing disclosures and security releases in a way that is realistic and necessary for end users.
We prefer to fully disclose the vulnerability as soon as possible once a user mitigation is available.
Disclosures will always be published in a timely manner after a release is published that fixes the vulnerability.

## Advisories

The Flux security team publishes its advisories directly into the affected repositories.
The main exception to this rule is flux2, which aggregates the CVEs across all Flux components (CLI and controllers).

The existing advisories can be found below:
- https://github.com/fluxcd/flux2/security/advisories
- https://github.com/fluxcd/kustomize-controller/security/advisories
- https://github.com/fluxcd/source-controller/security/advisories

## Audits

- In 2021 there was a security assessment and fuzzer development of the `fluxcd` repositories made by Ada Logics and funded by the CNCF.
- For a summary, please see [this blog post](https://fluxcd.io/blog/2021-11-10-flux-security-audit/)
- For all details, please read the [audit full technical report](https://fluxcd.io/FluxFinalReport-v1.1.pdf)
