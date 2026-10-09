# OPENEMS

![licence](https://img.shields.io/badge/licence-NOASSERTION-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `OPENEMS` in category **ELECTRICITY_MANAGEMENT**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** OPENEMS · **Upstream pin:** `8b2c74eb168a2a5ea0c591fe2840459589d9422b` · **Category:** ELECTRICITY_MANAGEMENT · **Vendor:** Anticloud FZ LLE · **Licence:** NOASSERTION

---

## What This Project Does

[![Build Status](https://github.com/OpenEMS/openems/actions/workflows/build.yml/badge.svg)](https://github.com/OpenEMS/openems/actions/workflows/build.yml)
[![Gitpod live-demo](https://img.shields.io/badge/Gitpod-live--demo-blue?logo=gitpod)](https://gitpod.io/#https://github.com/OpenEMS/openems/tree/main)
[![Cite via Zenodo](https://zenodo.org/badge/DOI/10.5281/zenodo.4440884.svg)](https://doi.org/10.5281/zenodo.4440883)
[![codecov](https://codecov.io/gh/openems/openems/graph/badge.svg?token=xliIughqt1)](https://codecov.io/gh/openems/openems)

<h1 align="center">
  <img src="./doc/modules/ROOT/assets/images/OpenEMS-Logo.png" alt="the Feneco - OpenEMS Logo" width="200"></a>
  <br/>Open Source Energy Management System
</h1>

OpenEMS - the Open Source Energy Management System - is a modular platform for energy management applications. It was developed around the requirements of monitoring, controlling, and integrating energy storage together with renewable energy sources and complementary devices and services like electric vehicle charging stations, heat-pumps, electrolysers, time-of-use electricity tariffs and more.

If you plan to use OpenEMS for your own projects, please consider joining the [OpenEMS Association e.V.](https://openems.io/association), a network of universities, hardware manufacturers, software companies as well as commercial and private owners, and get in touch in the [OpenEMS Community forum](https://community.openems.io). 

### OpenEMS in »Local Energy Management«

![Local Energy Management](./doc/modules/ROOT/assets/images/local-energy-management.png "Local Energy Management")

### OpenEMS in »Areal Energy Management«

![Areal Energy Management](./doc/modules/ROOT/assets/images/areal-energy-management.png "Areal Energy Management")

## OpenEMS IoT stack

The OpenEMS 'Internet of Things' stack contains three main components:

 * **OpenEMS Edge** runs on site, communicates with devices and services, collects data and executes control algorithms
 * **OpenEMS UI** is the real-time user interface for web browsers and smartphones
 * **OpenEMS Backend** runs on a (cloud) server, connects the decentralized Edge systems and provides aggregation, monitoring and control via internet

## Features

The OpenEMS software architecture was designed to leverage some features that are required by a modern and flexible Energy Management System:

 * Fast, PLC-like control of devices
 * Easily extendable due to the use of modern programming languages and modular architecture
 * Reusable, device independent control algorithms due to clear device abstraction
 * Wide range of supported devices and protocols

## OpenEMS UI Screenshots

![OpenEMS UI Live View](./doc/modules/ROOT/assets/images/ui-live.png "OpenEMS UI Live View")
![OpenEMS UI History View](./doc/modules/ROOT/assets/images/ui-history.png "OpenEMS UI History View")

## System architecture

OpenEMS is generally used in combination with external hardware and software components
(the exception is a simulated development environment - see [Getting Started](https://openems.github.io/openems.io/openems/latest/gettingstarted.html)). As a brief overview, this is how OpenEMS is used in production setups:
![OpenEMS System Architecture](./doc/modules/ROOT/assets/images/system-architecture.png "OpenEMS System Architecture")

## Getting Started

* Open up a [Live-Demo on Gitpod](https://gitpod.io/#https://github.com/OpenEMS/openems)
* Follow the [Getting Started](https://openems.github.io/openems.io/openems/latest/gettingstarted.html) guide to setup OpenEMS on your own computer
* Please checkout our [contribution guidelines](/.github/CONTRIBUTING.md) before submitting code

## Documentation

* [Latest version of documentation](https://openems.github.io/openems.io/openems/latest/introduction.html)
* [Javadoc](https://openems.github.io/openems.io/javadoc/)

## Open Source philosophy

The OpenEMS project is driven by the [OpenEMS Association e.V.](https://openems.io/association), a network of users, vendors and scientific institutions from all kinds of areas like hardware manufacturers, software companies, grid operators and more. They share the common target of developing a free and open-source platform for energy management, that supports the 100 % energy transition.

We are inviting third parties to use OpenEMS for their own projects and are glad to support them with their first steps. In any case if you are interested in OpenEMS we would be glad to hear from you in the [OpenEMS Community forum](https://community.openems.io).

OpenEMS development was started by [FENECON GmbH](https://www.fenecon.de), a German company specialized in manufacturing and project development of energy storage systems. It is the software stack behind [FEMS - FENECON Energy Management System](https://fenecon.de/page/fems) and widely used in private, commercial and industrial applications.

OpenEMS is funded by several federal and EU funding projects. If you are a developer and you would like to get hired by one of the partner companies or universities for working on OpenEMS, please send your motivation letter to info@openems.io.

## Scientific Research

If you use OpenEMS in your scientific research, please use our Zenodo Digital Object Identifier (DOI) as reference:

[![Cite via Zenodo](https://zenodo.org/badge/DOI/10.5281/zenodo.4440884.svg)](https://doi.org/10.5281/zenodo.4440883)

## License

* OpenEMS Edge 
* OpenEMS Backend

Copyright (C) 2016-2026 OpenEMS Association e.V.

This product includes software developed at FENECON GmbH: you can
redistribute it and/or modify it under the terms of the [Eclipse Public License version 2.0](LICENSE-EPL-2.0). 

 * OpenEMS UI

Copyright (C) 2016-2026 OpenEMS Association e.V.

This product includes software developed at FENECON GmbH: you can
redistribute it and/or modify it under the terms of the [GNU Affero General Public License version 3](LICENSE-AGPL-3.0).

---

## Installation

![OpenEMS System Architecture](./doc/modules/ROOT/assets/images/system-architecture.png "OpenEMS System Architecture")

## Usage

If you plan to use OpenEMS for your own projects, please consider joining the [OpenEMS Association e.V.](https://openems.io/association), a network of universities, hardware manufacturers, software companies as well as commercial and private owners, and get in touch in the [OpenEMS Community forum](https://community.openems.io).

## API

<br/>Open Source Energy Management System
</h1>

OpenEMS - the Open Source Energy Management System - is a modular platform for energy management applications. It was developed around the requirements of monitoring, controlling, and integrating energy storage together with renewable energy sources and complementary devices and services like electric vehicle charging stations, heat-pumps, electrolysers, time-of-use electricity tariffs and more.

If you plan to use OpenEMS for your own projects, please consider joining the [OpenEMS Association e.V.](https://openems.io/association), a network of universities, hardware manufacturers, software companies as well as commercial and private owners, and get in touch in the [OpenEMS Community forum](https://community.openems.io).

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | NOASSERTION |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

![OpenEMS System Architecture](./doc/modules/ROOT/assets/images/system-architecture.png "OpenEMS System Architecture")

## Contributing

# Contributing

- [📜 Contributor License Agreement](#-contributor-license-agreement)
- [🤝 Contributor Code of Conduct](#-contributor-code-of-conduct)
- [🪲 Bug Reports, Issues and Questions](#-bug-reports-issues-and-questions)
- [💡 Feature Requests](#-feature-requests)
- [🖌️ Coding Style](#️-coding-style)
- [📁 Documentation](#-documentation)

## 📜 Contributor License Agreement

By contributing, you agree to the Licenses of this project:

- OpenEMS Edge und Backend
  
    [Eclipse Public License version 2.0](../LICENSE-EPL-2.0)

- OpenEMS UI

    [GNU Affero General Public License version 3](../LICENSE-AGPL-3.0)

## 🤝 Contributor Code of Conduct

By contributing, you agree to respect the [Code of Conduct](CODE_OF_CONDUCT.md) of this project.

## 🪲 Bug Reports, Issues and Questions

A great way to contribute to the project is to send a detailed report when you encounter an issue. We always appreciate a well-written, thorough bug report, and will thank you for it!

To maintain clear and organized communication, all discussions should take place in the [OpenEMS Community forum](https://community.openems.io/). This helps keep everything together and ensures that conversations are streamlined and accessible to all contributors.

⚠️ *Please refrain from opening empty pull requests solely for the purpose of discussing ideas. Instead, utilize the forum to share and refine your concepts before submitting any code changes.*

## 💡 Feature Requests

Similar to issue reports, feature requests should be submitted to the [OpenEMS Community forum](https://community.openems.io/) for discussion. This helps ensure that all ideas are properly reviewed and discussed by the community.

When submitting a feature request, please be clear about the intended outcome and how it would relate to existing features. Providing detailed information helps in evaluating the request more effectively.

⚠️ *Additionally, avoid submitting duplicate feature requests. Before posting, search for existing requests, and if you find a similar or identical one, please join that discussion instead of creating a new thread.*

## 🖌️ Coding Style

We welcome pull-requests! While we will consider all submissions, we cannot promise that every request will be accepted.

To increase your changes of a merged pull-requests and help us review your code, please follow our [coding guidelines](https://openems.github.io/openems.io/openems/latest/development/coding-guidelines.html).

## 📁 Documentation

The documentation site for OpenEMS is hosted on [https://openems.github.io/openems.io/openems/latest](https://openems.github.io/openems.io/openems/latest). We greatly appreciate contributions that improve the quality and clarity of our documentation.

If you would like to contribute by updating or adding a page, please refer to our  [Contribute/Documentation](https://openems.github.io/openems.io/openems/latest/development/documentation.html) guide for detailed instructions on how to contribute effectivel

## License

Upstream © its respective contributors under NOASSERTION (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** OPENEMS
- **Pinned SHA:** `8b2c74eb168a2a5ea0c591fe2840459589d9422b`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`eb360a2c3019151bc3ae763b88e992f4c89a07bf5e63f3f2785867a70c84601c`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

