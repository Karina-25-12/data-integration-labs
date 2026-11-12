# Lab 01 – Open Source Project Analysis

**Project:** Requests  
**Repository:** [psf/requests](https://github.com/psf/requests)  
**Course:** Data Integration  
**Date:** 2026-11-12

## 1. Project Overview

Requests is an open-source HTTP library for Python.

It makes it easier to communicate with websites and
web APIs. Developers can use Requests to send HTTP
requests, retrieve data and process responses.

The project is hosted in the GitHub organization of
the Python Software Foundation (PSF).

**Sources:**
- [Requests repository](https://github.com/psf/requests)
- [Requests documentation](https://requests.readthedocs.io/en/latest/)

## 2. Licence

### Which licence does the project use?

Requests uses the **Apache License, Version 2.0**.

**Source:**
[Requests LICENSE](https://github.com/psf/requests/blob/main/LICENSE)

### Is the licence permissive or copyleft?

Apache 2.0 is a **permissive open-source licence**.

It allows users to use, copy, modify and distribute
the software, including for commercial purposes.

Unlike strong copyleft licences, Apache 2.0 does
not require all derivative software to be released
under the same licence.

### What if I copy code into my own project?

If I copy code from Requests, I must:

1. Include a copy of the Apache 2.0 licence.
2. Preserve applicable copyright and attribution
   notices.
3. State significant changes made to copied files.
4. Preserve relevant notices from the NOTICE file
   when required by the licence.

I should also check whether other licence
conditions apply to my own project.

**Sources:**
- [Requests licence](https://github.com/psf/requests/blob/main/LICENSE)
- [Requests NOTICE](https://github.com/psf/requests/blob/main/NOTICE)
- [Apache 2.0 licence](https://www.apache.org/licenses/LICENSE-2.0)

## 3. What Machines See – GitHub API

GitHub provides repository metadata through
its REST API.

The field `license.spdx_id` identifies the
detected licence using an SPDX identifier.

### 3.1 Requests

**API:**
https://api.github.com/repos/psf/requests

**SPDX ID:** `Apache-2.0`

**Explanation:**

GitHub recognizes the Requests licence as
Apache License 2.0, a standard permissive
open-source software licence.

### 3.2 My Lab Repository

**API:**
https://api.github.com/repos/YOUR-USERNAME/data-integration-labs

**Expected SPDX ID:** `MIT`

**Explanation:**

If my repository contains the MIT licence
created in Task 2, GitHub should recognize
it as MIT, another permissive licence.

**Verification:** Replace YOUR-USERNAME with
the actual account name and confirm the API value.

### 3.3 Our World in Data – CO2 Data

**API:**
https://api.github.com/repos/owid/co2-data

**SPDX ID:** To be confirmed from the API.

**Explanation:**

The repository README describes Creative
Commons attribution requirements for
Our World in Data materials.

Third-party datasets retain their own
licence conditions.

The API's detected licence must be checked
separately because the README's licence
statement and GitHub's automatic detection
are not necessarily identical.

**Source:**
[CO2 Data README](https://github.com/owid/co2-data)

### What do null and NOASSERTION mean?

`null` means GitHub did not detect a readable
licence file.

`NOASSERTION` means GitHub found licence
information but could not identify it as
one standard SPDX licence.

In both cases, the actual licence text must
be examined before using the material.

## 4. Community Files

The Requests repository provides all four
community resources required in this task.

| File | Available? | Purpose |
|------|------------|---------|
| README | Yes | Explains the project |
| LICENSE | Yes | Defines usage rights |
| CONTRIBUTING | Yes | Explains how to contribute |
| CODE_OF_CONDUCT | Yes | Defines community rules |

The contributing instructions and code of
conduct are linked from the repository.

**Sources:**
- [README](https://github.com/psf/requests)
- [LICENSE](https://github.com/psf/requests/blob/main/LICENSE)
- [Contributing guide](https://github.com/psf/requests/blob/main/docs/dev/contributing.rst)
- [Community standards](https://github.com/psf/requests/community)

## 5. People and Governance

### Who develops Requests?

Requests is developed by an open-source
community of contributors and maintainers.

The contributing guide identifies the primary
maintainers as:

- Nate Prewitt
- Ian Cordasco
- Seth Michael Larson

### How many contributors are there?

The exact number should be read from GitHub's
Contributors view.

**Source:**
[Contributors](https://github.com/psf/requests/graphs/contributors)


According to Trendshift, Requests has 663
contributors (source checked in November 2026).

This figure may differ from GitHub's current
contributor statistics.

**Source:**
[Requests on Trendshift](https://trendshift.io/repositories/2695)


### Who decides what gets merged?

The project maintainers make the final
decision about accepting contributions.

Pull requests must pass code review before
they are merged.

The contributing guide also explains that
the maintainers may reject contributions
that do not fit the project's goals.

**Source:**
[Contributor's Guide](https://github.com/psf/requests/blob/main/docs/dev/contributing.rst)

## 6. Money and Funding

Requests is developed as an open-source
community project and is hosted under the
Python Software Foundation's GitHub organization.

The repository displays a Sponsor button.

The Python Software Foundation accepts
financial support through donations and
sponsorships, including individual and
corporate contributions.

Requests is also featured on the PSF
sponsorship page.

This does not prove that every contributor
is paid or that donations are allocated
directly to Requests development.

The precise division between paid work,
voluntary work and company-supported work
is not publicly quantified in these sources.

**Sources:**
- [PSF GitHub Sponsors](https://github.com/sponsors/psf)
- [Python Software Foundation](https://www.python.org/psf/)
- [Requests repository](https://github.com/psf/requests)

## 7. Project Activity

**Date checked:** 2026-11-12

| Metric | Result |
|--------|--------|
| Latest release | 2.34.2 |
| Release date | 2026-05-14 |
| Open issues | 163 |
| Open pull requests | 88 |

These numbers represent a snapshot.
Issues and pull requests change over time.

GitHub's repository API field
`open_issues_count` includes both open
issues and open pull requests.

To get the separate values, I use the
Issues and Pull requests tabs.

**Sources:**
- [Releases](https://github.com/psf/requests/releases)
- [Release history](https://github.com/psf/requests/blob/main/HISTORY.md)
- [Open issues](https://github.com/psf/requests/issues)
- [Open pull requests](https://github.com/psf/requests/pulls)
- [GitHub API](https://api.github.com/repos/psf/requests)

## 8. My Way In – Contributing

### How can I contribute?

According to the Requests contributing guide,
a code contribution should follow these steps:

1. Read the contributing guidelines.
2. Fork the repository.
3. Run the existing tests.
4. Write tests for the intended change.
5. Implement the change.
6. Run the test suite again.
7. Submit a pull request to the main branch.
8. Respond to feedback from the maintainers.

All pull requests require code review before
they can be merged.

The repository currently restricts pull
request creation to collaborators, so
external contributors should follow the
project's current access rules and contact
the maintainers where necessary.

### Are there good first issues?

At the time of inspection, the GitHub
Contribute page did not list any issues
marked `good first issue`.

However, the contributing guide welcomes
new contributors and encourages them to
contact a maintainer for guidance.

**Sources:**
- [Contributing guide](https://github.com/psf/requests/blob/main/docs/dev/contributing.rst)
- [Contribute page](https://github.com/psf/requests/contribute)
- [Pull requests](https://github.com/psf/requests/pulls)

## 9. Conclusion

Requests is an example of a mature
open-source software project.

Its Apache 2.0 licence allows broad reuse
while requiring preservation of legal notices.

Its development is organized through a
community of contributors and a smaller
group of maintainers.

The project demonstrates that open source
does not mean the absence of rules.

Licensing, governance, code review, testing
and community standards are important
parts of maintaining open-source software.
