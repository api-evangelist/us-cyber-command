# US Cyber Command (us-cyber-command)

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
