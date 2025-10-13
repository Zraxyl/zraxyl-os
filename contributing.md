# Contributing to Zraxyl OS

Thank you for contributing to Zraxyl OS. This guide outlines the process for submitting code, packages, and documentation in a secure, reproducible, and policy-compliant way.

## Before You Start

### 1. Read the Code of Conduct
    All contributors must follow [CODE_OF_CONDUCT.md]. Violations may result in suspension of merge/upload rights or removal of contributions.

### 2. Set Up Your Environment

    - Clone this project in a reproducible environment.
    - Ensure you can build and test bottle packages locally.
    - Register your maintainer key in the official registry [MAINTAINER_KEY_REGISTRY_URL].

### 3. Check Existing Issues & Packages
    Avoid duplicating work. Search open issues and PRs first.

---

## Contributions

### Code and Documentation

- Fork the repository and work in a feature branch.
- Run all tests locally before submitting a PR
- Include meaningful commit messages and changelog entries.
- PRs must pass CI, static analysis, and reproducible build checks.

## Bottle Packages

- Each package must include:

    - Source URL
    - SPDX license tag
    - Deterministic build script (human-readable)
    - Reproducible-build hash
    - ```manifest.bottle.sig``` signed with your maintainer key

- No binary blobs without upstream source and license.
- Verify reproducibility locally before submitting a PR.
- Submit any vulnerabilities privately following [security@zraxyl.eu].

---

## Pull Request Checklist

1. Branch is up-to-date with main.
2. Commit messages are clear and reference issues if applicable.
3. Tests run successfully in your environment.
4. bottle packages pass reproducibility checks and signature verification.
5. Code review is requested, and maintainers are assigned.
6. CoC compliance confirmed by submitting contributor.

### Contributor Confirmation Snippet:

```
By submitting this PR, I confirm:
- I have the right to submit the code/package.
- All license information is accurate (SPDX compliant).
- Build scripts and bottle manifests follow reproducible-build instructions.
- I have read and agree to CODE_OF_CONDUCT.md.
```

---

## Reporting Issues

- Security vulnerabilities: Private report to [security@zraxyl.eu].
- Conduct concerns: Private report to [coc@zraxyl.eu].

---

## Review and Merge

- PRs are reviewed by at least one Governance Board member.
- CI must pass reproducibility, signature, and security checks.
- Merges require signed commit or merge tag.

---

## Appeals

- Denied contributions or enforcement actions may be appealed to [coc@zraxyl.eu] within 14 days.
- Governance Board decisions are final after review.

---
