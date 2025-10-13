# Code of Conduct

### Purpose

This project exists to provide a secure, reproducible, and transparent Linux From Scratch ecosystem. Supply-chain safety is critical. All contributors, maintainers, CI systems, mirrors, and bottle package uploaders are bound by this Code of Conduct.

### Scope

This Code applies to:

- Contributions (code, docs, packages, reviews, issues, PRs)
- Communication (mailing lists, chats, meetings, mirrors)
- Automated systems (CI, bots, uploaders, signing keys)

### Mandatory Rules

Professional conduct: Discussions focus on technical issues. No harassment, personal attacks, or discriminatory behavior.

### Security & reproducibility:

- All bottle packages must be reproducible, signed, and verified.
- Build scripts must include license, source URL, and reproducible-build metadata.
- No binary blobs without source and license.

## Release process:

- No direct push to main. All commits require review and CI pass.
- All releases are signed and tagged.
- Keys must be registered in the maintainer registry and rotated every 12 months.
- Zero tolerance for doxxing, harassment, or distribution of malware.

Dependency policy:

- Minimize runtime dependencies.
- Block unlicensed or vulnerable transitive dependencies.

Reporting Violations

- Security issues: Send encrypted report to [security@zraxyl.eu]. Use the template in CONDUCT_REPORT.md.
- Conduct issues: Email [coc@zraxyl.eu] or file a private issue tagged coc-report.
- Confidentiality: Reporter identity is confidential unless consent is given.

Enforcement

- Minor infractions → private warning + correction.
- Repeated infractions → suspension of merge/upload rights (7–30 days).
- Severe violations (malware, harassment, supply-chain attack) → immediate suspension of keys, removal of uploaded packages, mirror notification, public disclosure if applicable.

Appeals: Send to [coc@zraxyl.eu] within 14 days. Appeals are reviewed by the Governance Board.

Duties:

- Enforce this Code of Conduct
- Approve/revoke maintainer keys
- Oversee incident triage and remediation
- Publish anonymized incident summaries
- Decisions require majority vote.

Privacy

- Only minimum data required for investigations is stored.
- Reports are handled confidentially and shared only with the Governance Board.
- All public disclosures are anonymized unless reporters consent to attribution.
- Maintainer key registry contains only technical identifiers (key ID, expiry, contact alias).

Amendments

This Code may be updated by Developer Board vote. Contributors will be notified through release notes and repository announcements.
