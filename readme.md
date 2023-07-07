# Monolith Responsible Disclosure

We look forward to working with the security community to find vulnerabilities in order to keep our businesses and customers safe.

Please submit reports to <responsible-disclosure@monolith.xyz>.

## Response Targets

We will make a best effort to meet the following SLAs for hackers participating in our program:

| Type of Response| SLA in business days |
| --- | --- |
| First Response | 7 days |
| Time to Triage | 7 days |
| Time to Resolution | depends on severity and complexity |

We’ll try to keep you informed about our progress throughout the process.

## Disclosure Policy

* Follow HackerOne's [disclosure guidelines](https://www.hackerone.com/disclosure-guidelines).
* If and when we do disclose a report, it will be mutually agreed upon with the hacker. We reserve the right to deny any request for public disclosure.

## Program Rules

* Please provide detailed reports with reproducible steps. If the report is not detailed enough to reproduce the issue, we won't be able to triage.
* Submit one vulnerability per report, unless you need to chain vulnerabilities to provide impact.
* When duplicates occur, we'll only engage with the first report that was received (provided that it can be fully reproduced).
* Multiple vulnerabilities caused by one underlying issue will be treated as one valid report.
* Social engineering (e.g. phishing, vishing, smishing) is prohibited.
* Make a good faith effort to avoid privacy violations, destruction of data, and interruption or degradation of our service. Only interact with accounts you own or with explicit permission of the account holder.

## Scope

| Asset name | Type | Coverage | CVSS |
| --- | --- | --- | --- |
| **\*.production.tkn.zone**<br>Backend services for our Monolith product are provided under this domain. | Wildcard | In scope | Critical |
| **https://github.com/tokencard/contracts/**<br>Smart contracts under https://github.com/tokencard/contracts/tree/master/contracts and previous released versions, excluding mocks and other test contracts. | Source code | In scope | Critical |
| **io.tokencard.app.android**<br>This is our Monolith mobile app for Android. You can find it at https://play.google.com/store/apps/details?id=io.tokencard.app.android. | Android: Play Store | In scope | Critical |
| **lt.tokencard.monolith-ios**<br>This is our Monolith mobile app for iOS. You can find it at https://apps.apple.com/us/app/monolith-ethereum-wallet/id1631556490. | iOS: App Store | In scope | Critical |
| **monolith.xyz**<br>This is a marketing website only. We'll only consider vulnerabilities that lead to misleading content being shown. This means clickjacking, framing and similar attack vectors are out of scope. | Domain | In scope | High |

## Out of scope vulnerabilities

When reporting vulnerabilities, please consider (1) attack scenario / exploitability, and (2) security impact of the bug. The following issues are considered out of scope:

* For our marketing websites we'll only consider vulnerabilities that lead to misleading content being shown. This means clickjacking, framing and similar attack vectors are out of scope.
* Content and services provided by third-parties (such as Zendesk, Automattic or Medium) are excluded, even if available under a subdomain of monolith.xyz.
* Mocks and other test contracts in https://github.com/tokencard/contracts/tree/master/contracts.
* Missing best practices, for example with HTTP headers, TLS configuration, SPF/DKIM/DMARC records, cookie settings, etc.
* Vulnerabilities due to OS exploits, device jailbreaks, outdated or unpatched software on customer devices.
* Attacks requiring MITM or physical access to a customer's device.
* Any activity that could lead to the disruption of our service (DoS).
* Rate limiting or brute-force issues on non-authentication endpoints.
* Open redirects, unless an additional security impact can be demonstrated.
* Previously known vulnerable libraries without a working Proof of Concept.
* Issues that require unlikely user interaction.

## Safe Harbor

Any activities conducted in a manner consistent with this policy will be considered authorized conduct and we will not initiate legal action against you. If legal action is initiated by a third party against you in connection with activities conducted under this policy, we will take steps to make it known that your actions were conducted in compliance with this policy.

Thank you for helping keep Monolith and our users safe!

