# Cellenics - Principles and Practices

Last updated: January 27, 2023

## Overview and Mission

This document sets forth the principles and practices of the Cellenics® open source community. The mission of the Cellenics project is to provide and support the open, collaborative development of an open-source platform intended to empower research biologists to analyze single-cell RNA sequencing (scRNA-seq) datasets.

This document describes the "ways of working" for the Cellenics project and the mechanisms for community contributions to the Cellenics codebase.

## Maintainers

The Cellenics maintainers (the "Maintainers") are the primary technical decision-makers of the Cellenics project and codebase. The Maintainers are the individuals set forth in [maintainers.md](./maintainers.md). The Maintainers may from time to time, and with the approval of Harvard (as the host of the Cellenics project), add new Maintainers based on individuals who have demonstrated contributions to the project's source code, documentation and other materials.

The Maintainers will act in accordance with the mission of the Cellenics project to oversee:

* the technical direction of the project and its codebase;
* engagement with technical contributors from the broader community; and
* decision-making about technical considerations, such as:
  - the project's release process and cadence;
  - the features and bug fixes that will be addressed; and
  - the pull requests that will be merged into the the project's codebase.

The Maintainers will aim to make decisions by consensus wherever possible, with discussions held in open and transparent public comments, e.g. in Issue and Pull Request threads on GitHub.

If the Maintainers cannot reach consensus on a particular issue, the Maintainers may resolve conflicts pursuant to majority vote; provided, that where multiple Maintainers are employed by the same organization, company or group of related entities, such Maintainers shall together cast at most one vote.

In the event of a matter which may raise concerns regarding Harvard's non-profit mission, legal or liability risks, or other such institutional concerns, Harvard may resolve matters and conflicts in its discretion to address such concerns. For the avoidance of doubt, unless explicitly permitted by Harvard in writing, the Maintainers may _not_ incur or purport to incur obligations or commitments on behalf of Harvard.

## Contributions

Members of the broader community may contribute to the Cellenics project, such as by filing Issues and by submitting Pull Requests.

Pull Requests contributed to the Cellenics project must include Developer Certificate of Origin (DCO) sign-off statements, as more fully described in the "Licensing" section below.

The Maintainers may from time to time specify additional processes and technical requirements in a Cellenics repo for contributions, as documented in a CONTRIBUTING.md or similar file.

## Policies

The Cellenics project is hosted and supported by Harvard Medical School's Department of Biomedical Informatics, and will be operated in accordance with Harvard University's non-profit purpose and mission. Participants in the Cellenics project should not act in any manner that is inconsistent with Harvard University's non-profit, tax-exempt status or purpose.

The Cellenics project shall operate in a fully open and transparent manner at all times; provided that, from time to time, Harvard legal counsel may be consulted by Maintainers who are Harvard personnel in a private manner in order to seek legal guidance regarding the operation of the project.

All outputs of the Cellenics project shall be made available to the public under the open source licenses set forth in the "Licensing" section below.

The Cellenics project shall be operated in a manner that is open to all contributors (individual, corporate and organizational) who comply with the policies and ways of working for the Cellenics community. The Maintainers and other contributors should not exclude any participant for any reason other than those that are reasonable, documented and applied on a non-discriminatory basis to all community participants.

Cellenics is a registered trademark of President and Fellows of Harvard College. Usage of the Cellenics trademark shall be subject to trademark usage guidelines as set forth by Harvard from time to time.

The project has adopted the [Contributor Covenant, version 2.1](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) as its Code of Conduct. All community participants must abide by the Code of Conduct in their interactions with the Cellenics community. The Maintainers will serve as the community leaders for purposes of enforcement of the Code of Conduct.

## Licensing

### Project License

As used herein, "Project License" means the open source software license applicable to the Cellenics codebase, as follows:

* the [GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.html), for R code that utilizes dependencies under the GPL-3.0 license; and
* the [MIT license](https://spdx.org/licenses/MIT.html), for the remainder of Cellenics.

See [licensing.md](./licensing.md) for more detailed information.

### Contributions to Cellenics

For each contribution to Cellenics following the adoption of this Principles and Practices document, the copyright in the contribution will be retained by the copyright holder. The contribution will be licensed, not assigned, to the project and the broader community.

Each contribution to Cellenics is to be contributed under the Project License for the corresponding part of the Cellenics codebase.

Each contribution must be accompanied by a [Developer Certificate of Origin (DCO)](https://developercertificate.org) sign-off statement in the message body for each commit. The DCO sign-off statement should be in the standard form commonly used by other open source projects, as follows:

```
    Signed-off-by: CONTRIBUTOR NAME <EMAIL ADDRESS>
```

The project will adopt tooling to assist in checking for the presence of DCO sign-off statements in contributed pull requests.

### Dependencies and Licenses

Cellenics utilizes a variety of install-time dependencies that are not distributed as part of the Cellenics source code. These dependencies are licensed under various licenses, including permissive, weak copyleft and strong copyleft licenses.

The Maintainers will adopt processes to help with checking compatibility of dependencies' licenses with the Project Licenses and with the mission of the project.

If a proposed contribution would introduce a license for a dependency or modify the nature of its usage in a way that could result in a potential compatibility concern, the Maintainers should mark the contribution as "pending review". Maintainers who are Harvard personnel may then privately consult with Harvard legal counsel for guidance prior to taking action on the proposed contribution.

### Disclaimer

The Cellenics project does not provide legal advice, and all Cellenics content is subject to the disclaimers of warranties and liability set forth in the applicable license texts. You should consult with your own legal counsel if you have questions regarding licenses and license compatibility.

## Miscellaneous

This Principles and Practices document may be updated by Harvard from time to time. Questions about this document should be addressed to: ccbhelp@hms.harvard.edu
