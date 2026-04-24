[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# 2026 Annual Review CREDEBL

## Project Health

LF Decentralized Trust CREDEBL [LFX Insights Dashboard](https://insights.lfx.linuxfoundation.org/foundation/lf-decentralized-trust/reports/contributors?project=credebl&bestPractice=false&dateFilters=Last%20Year&dateRange=2024-01-01%20to%202024-12-31&compare=PP&granularity=month&hideBots=true&repository=all)

This project is a new project so the contribution activity is not as high as other projects. However, We have already seen some new contributors started exploring and the PRs are getting through.

## Maintainer Diversity

- Currently all the maintainers are from AYANWORKS and as we have already started receiving the contributions from the community, once we get Major PRs we will start adding more maintainers.
- The MAINTAINERS.md file is up to date and can be found [here](https://github.com/credebl/.github/blob/main/MAINTAINERS.md)

## Project Adoption

Several Government Entities and Enterprise companies are using the CREDEBL project for production use cases.

The following entities are using the project till date:
- DigiYatra Foundation - Used for International Contactless Travel POC - https://www.iata.org/contentassets/a46387f9bc6b42368c0a72664f6f930f/cycle2-attachment-poc.pdf
- https://www.bhutanndi.com - Bhutan NDI for Royal Government of Bhutan.
- https://www.ict.gov.pg/sevis-wallet - SevisPass Digital ID Pilot for Papua New Guinea.
- https://sovio.id - Sovio SaaS

## Goals

### Performance Against Prior Goals

The current project roadmap is public and can be found here: [CREDEBL Roadmap](https://github.com/orgs/credebl/projects/5/views/1)

**Key outcomes delivered in 2025:**
- The weekly community calls are running to have all roadmap and development discussions in the open community.
- After moving into LFDT, team has made a major release [v2.0](https://github.com/credebl/platform/releases/tag/v2.0.0) of the project
  - Following are the minor releases for further enhancements :
    - [v2.1.3](https://github.com/credebl/platform/releases/tag/v2.1.3) - Improved session management, support for multiple email providers.
    - [v2.1.2](https://github.com/credebl/platform/releases/tag/v2.1.2) - Code refactoring and bug fixes
    - [v2.1.1](https://github.com/credebl/platform/releases/tag/v2.1.1) - Enhancements in SSO feature
    - [v2.1.0](https://github.com/credebl/platform/releases/tag/v2.1.0) - OpenTelemetry (OTEL) and Signoz integration for observability
- We delivered an introductory session in OpenWallet Foundation in [Wallet Interop SIG](https://lf-openwallet-foundation.atlassian.net/wiki/spaces/GROUP/pages/130187265/2025-04-07+Wallet+Interop+SIG)
- We participated in the LFX mentorship with following programs:
  - [LFDT - Test coverage and improved documentation for CREDEBL Platform project](https://mentorship.lfx.linuxfoundation.org/project/92df3acf-9c1e-4a27-b9a4-cb5ed4293435)
  - [LFDT - Evaluate use of Unikernals for scaling controller & mediator instances in CREDEBL deployments](https://mentorship.lfx.linuxfoundation.org/project/d501d6f7-b964-44f5-a079-1b20adc4f06a) 
- We delivered session under LFDT India Chapter for building a digital credential solution using CREDEBL
- New TSC nomination completed. Regular meetings will be setup soon.
- Started work on supporting OID4VC/VP implementation with support for SD-JWTs, ISO mDoc & DC-API
- Started work on revocation support for SD-JWT credentials with IETF Token Status List 2021.

### Next Year's Goals

The project has the following goals for the next year:
- Scaling for Mediator & Agents
  - Improve Session management in Credo & Mediator
  - External KMS
  - Message pick-up Repository, Socket Dock
- OpenID4VC 
  - Issuance & Presentation specs
  - SD-JWT, JWT-VC, mDL formats
- Revocation using W3C Status List (BitString)
- Trust Registry Service (ToIP)
- Hedera & Cheqd ledger support
- Cloud Wallet (for holders)
- Wallet Utilities
  - Export wallet from shared agent -> import into a dedicated agent
  - Import X509 based cert/key

### Help Required

LF Decentralized Trust can help with the following:
- Promote the CREDEBL project within the LF Decentralized Trust community
- Help with the workshops and Mentorship Program

## Project Lifecycle Status Recommendation

The CREDEBL is already used in production with large scale deployments at a national level. However, based on the suggestions from TAC, we will focus on increasing the maintainer diversity through LFDT events such as webinars, workshops. Until then, the project can remain in the incubation.
