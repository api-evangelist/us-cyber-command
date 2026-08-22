# US Cyber Command (us-cyber-command)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

US Cyber Command (USCYBERCOM) is a Unified Combatant Command of the United States Armed Forces responsible for directing, synchronizing, and coordinating cyberspace operations. It defends Department of Defense information networks and prepares to conduct full spectrum military cyberspace operations. USCYBERCOM's Cyber National Mission Force (CNMF) publicly shares unclassified malware samples via VirusTotal and publishes joint cybersecurity advisories with CISA, NSA, FBI, and allied nations.

**URL:** [https://www.cybercom.mil/](https://www.cybercom.mil/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cybersecurity, Federal Government, Military, Threat Intelligence, Defense

## Timestamps

- **Created:** 2024-12-25
- **Modified:** 2026-05-03

## APIs

### CNMF Malware Sharing via VirusTotal

The Cyber National Mission Force (CNMF) shares unclassified malware samples attributed to nation-state threat actors on VirusTotal via the CYBERCOM_Malware_Alert account. Includes samples from Russian, Iranian, and North Korean state-sponsored actors.

**Human URL:** [https://www.virustotal.com/gui/user/CYBERCOM_Malware_Alert/comments](https://www.virustotal.com/gui/user/CYBERCOM_Malware_Alert/comments)

#### Tags:

 - Cybersecurity, Malware, Threat Intelligence, VirusTotal, Federal Government

#### Properties

- [Documentation - CYBERCOM VirusTotal Malware Alert Feed](https://www.virustotal.com/gui/user/CYBERCOM_Malware_Alert/comments)
- [Getting Started - CNMF Malware Sharing Initiative](https://www.cybercom.mil/Media/News/News-Display/Article/1681533/new-cnmf-initiative-shares-malware-samples-with-cybersecurity-industry/)
- [JSONSchema - Malware Sample Schema](json-schema/uscybercom-malware-sample-schema.json)
- [JSONSchema - Threat Actor Schema](json-schema/uscybercom-threat-actor-schema.json)

### USCYBERCOM News and Advisories

Public news releases, advisories, and operational announcements including joint cybersecurity advisories co-published with CISA, NSA, FBI, and Five Eyes allies.

**Human URL:** [https://www.cybercom.mil/Media/News/](https://www.cybercom.mil/Media/News/)

#### Tags:

 - Cybersecurity, Federal Government, Military, Advisories

#### Properties

- [Documentation - USCYBERCOM News](https://www.cybercom.mil/Media/News/)
- [Documentation - Cyber Command Challenge Problems](https://www.cybercom.mil/Portals/56/Documents/Cyber%20Command%20Problem%20Set%203rd%20Edition.pdf)
- [JSONSchema - Cybersecurity Advisory Schema](json-schema/uscybercom-advisory-schema.json)

## Common Properties

- [Website](https://www.cybercom.mil/)
- [Documentation - News and Advisories](https://www.cybercom.mil/Media/News/)
- [Contact USCYBERCOM](https://www.cybercom.mil/About/Contact/)
- [Vocabulary](vocabulary/us-cyber-command-vocabulary.yml)
- [JSON-LD Context](json-ld/us-cyber-command-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| CNMF Malware Sharing Program | The CNMF shares unclassified malware samples on VirusTotal attributed to Russian, Iranian, North Korean, and other state-sponsored threat actors. |
| Joint Cybersecurity Advisories | USCYBERCOM publishes joint advisories with CISA, NSA, FBI, and allied nation cybersecurity agencies on active nation-state threats. |
| Defensive Cyber Operations | USCYBERCOM conducts defensive cyber operations to detect and respond to malicious activity targeting U.S. and partner networks. |
| Cyber Command Challenge Problems | Published guidance identifying high-priority cybersecurity challenges for industry, academia, and government collaboration. |
| Hunt Forward Operations | At partner nation invitation, USCYBERCOM deploys hunt forward teams to identify malicious activity on allied networks. |

## Use Cases

| Name | Description |
|------|-------------|
| Threat Intelligence Enrichment | Security analysts use CNMF VirusTotal uploads to identify state-sponsored malware and update detection rules and IOC databases. |
| Malware Analysis and Attribution | Researchers analyze USCYBERCOM-disclosed malware samples to understand adversary TTPs and develop detection signatures. |
| Cybersecurity Advisory Tracking | Organizations track USCYBERCOM joint advisories to understand active threats and implement recommended mitigations. |
| Defensive Tool Development | Security tool developers use CNMF malware samples to test and improve detection capabilities and antivirus signatures. |
| Government Threat Awareness | Government agencies and critical infrastructure operators monitor USCYBERCOM disclosures for nation-state threat indicators. |

## Integrations

| Name | Description |
|------|-------------|
| VirusTotal | CNMF publishes malware samples to VirusTotal via the CYBERCOM_Malware_Alert account for public analysis and sharing. |
| CISA | USCYBERCOM collaborates with CISA on joint cybersecurity advisories, malware disclosures, and critical infrastructure defense. |
| NSA Cybersecurity Directorate | USCYBERCOM and NSA coordinate on threat intelligence sharing and jointly author advisories on nation-state threats. |
| Five Eyes Alliance | USCYBERCOM partners with UK NCSC, Canadian CCCS, Australian ACSC, and New Zealand NCSC for joint threat intelligence publications. |

## Artifacts

Machine-readable data specifications organized by format.

### JSON Schema

- [Malware Sample Schema](json-schema/uscybercom-malware-sample-schema.json)
- [Cybersecurity Advisory Schema](json-schema/uscybercom-advisory-schema.json)
- [Threat Actor Schema](json-schema/uscybercom-threat-actor-schema.json)

### JSON Structure

- [Malware Sample Structure](json-structure/uscybercom-malware-sample-structure.json)
- [Cybersecurity Advisory Structure](json-structure/uscybercom-advisory-structure.json)
- [Threat Actor Structure](json-structure/uscybercom-threat-actor-structure.json)

### JSON-LD

- [US Cyber Command Context](json-ld/us-cyber-command-context.jsonld)

### Examples

- [Malware Sample Example](examples/uscybercom-malware-sample-example.json)
- [Cybersecurity Advisory Example](examples/uscybercom-advisory-example.json)
- [Threat Actor Example](examples/uscybercom-threat-actor-example.json)

## Vocabulary

- [US Cyber Command Vocabulary](vocabulary/us-cyber-command-vocabulary.yml) — Unified taxonomy mapping 3 resources, 5 actions, 0 workflows, and 4 personas across malware intelligence, threat actor attribution, and cybersecurity advisory dimensions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
