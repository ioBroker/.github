# Security Policy

This policy applies to every repository of the ioBroker organization that has no `SECURITY.md` of its own.

## Reporting a vulnerability

Please do **not** report a security vulnerability in a public issue, a pull request, the forum or a chat. Report it privately instead:

1. **GitHub (preferred):** open the **Security** tab of the affected repository and click **Report a vulnerability**. The report and the discussion about it stay private until an advisory is published.
2. **E-mail:** if you have no GitHub account, write to [info@iobroker.net](mailto:info@iobroker.net) with `Security` in the subject.

Reports in English or German are welcome. Please include:

- the affected repository and version, e.g. js-controller 7.2.5
- what the vulnerability is and what an attacker can do with it
- the steps to reproduce it, or a proof of concept
- whether it is already publicly known or being exploited

## What happens next

- **Within 3 working days** we confirm that we received your report.
- **Within 14 days** you get a first assessment: whether we consider it a vulnerability, how severe it is, and what we do next.
- While we work on a fix, we keep you informed.
- **Coordinated disclosure:** we publish a GitHub security advisory, with a CVE where applicable, once a fix is released - at the latest 90 days after your report, unless we agree on something else with you.
- If you wish, we name you in the advisory.

## Scope

- **In scope** are the repositories of the ioBroker organization, among them the js-controller, admin and the adapters maintained here.
- **Adapters in other accounts** are maintained by their authors. Please report a vulnerability in such an adapter to its maintainer, through the Security tab of its repository if it is enabled. If you get no answer within 14 days, report it to us as described above, and we help to coordinate.
- **Publicly known vulnerabilities of third-party dependencies**, e.g. an npm advisory, need no private report: an issue or a pull request with the update is fine. Do report privately if you found that such a vulnerability can be exploited through ioBroker.

## Supported versions

Security fixes are made in the latest release of a repository. A repository that maintains several release lines lists them in its own `SECURITY.md`, e.g. the [js-controller](https://github.com/ioBroker/ioBroker.js-controller/blob/master/SECURITY.md).
