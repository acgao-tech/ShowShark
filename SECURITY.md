# Security Policy

## Scope

This repository is the public issue tracker and documentation repository for
ShowShark. It does not contain the ShowShark application source code.

This policy covers security issues in the distributed ShowShark Client,
ShowShark Server, official downloads, update mechanisms, and this repository's
published documentation and media.

Security issues include defects that could enable unauthorized access, privilege
escalation, remote code execution, data exposure, authentication or session
failures, insecure update or distribution behavior, or other compromise of a
user's device, server, media library, account, or network.

For ordinary bugs, crashes, feature requests, or documentation problems without
a security impact, please use public GitHub issues.

## Supported Versions

ShowShark is distributed as current releases rather than long-lived maintenance
branches. Security fixes are made available through the latest official client
and server releases.

| Version or channel | Supported |
| --- | --- |
| Latest ShowShark Client release from the App Store | :white_check_mark: |
| Current ShowShark Client TestFlight beta | :white_check_mark: |
| Latest ShowShark Server release from official ACGAO downloads | :white_check_mark: |
| Older ShowShark Client or Server releases | :x: |
| Unofficial builds, mirrors, forks, or redistributions | :x: |

Users should update to the latest official Client and Server releases before
reporting an issue against an older build, unless the vulnerability prevents
updating or is specific to the update process.

## Reporting a Vulnerability

Please do not open a public GitHub issue for a suspected vulnerability.

Report security vulnerabilities using GitHub's private vulnerability reporting
for this repository:

https://github.com/acgao-tech/ShowShark/security/advisories/new

You can also open the repository's Security tab on GitHub, choose Advisories,
and use Report a vulnerability. If that option is unavailable, use ACGAO's
official support or contact channel and include "ShowShark security
vulnerability" in the subject or first line.

Include as much of the following as you can:

- Affected product: ShowShark Client, ShowShark Server, update or download
  process, repository content, or website/download infrastructure.
- Affected version or build, platform, and operating system version.
- A clear description of the vulnerability and security impact.
- Steps to reproduce, proof-of-concept details, logs, screenshots, or network
  traces when safe to share.
- Whether the issue has been publicly disclosed or shared with anyone else.
- Your preferred contact information and whether you want credit in release
  notes or advisories.

We aim to acknowledge reports within 3 business days. While a report is under
review, we aim to provide a status update at least every 14 days. Accepted
reports will be investigated, prioritized by severity, and fixed in a future
Client, Server, or infrastructure update as appropriate. If a report is
declined, we will explain why when possible.

Please give us a reasonable opportunity to investigate and ship a fix before
public disclosure. Do not access, modify, delete, or disclose data that does not
belong to you, and do not disrupt other users or services while researching or
validating a report.
