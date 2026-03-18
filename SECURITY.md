# Security Policy

## Introduction

Fenstream Technology Group Ltd is committed to maintaining the security and integrity of all Open Source repositories and Software Projects owned and maintained by us and our subsidiaries. This policy defines how security vulnerabilities should be reported, triaged, remediated, and disclosed.

This notice applies to all GitHub Repositories and related release artifacts owned and maintained by **Fenstream Technology Group Ltd** and its subsidiaries **Abbeygate IT Services Ltd** and **DinoHosting (UK) Ltd**.  

Our security and engineering teams review and triage all reported vulnerabilities.

## Scope

This policy applies to all repositories governed by the Group Policy Baseline.

In scope:

- Source code and release artifacts published in governed repositories
- Official project documentation and configuration examples published in governed repositories
- Supported release versions listed below

Out of scope:

- Third-party services, tools, infrastructure or systems outside group control
- Forks or mirrors not maintained by group organisations
- Social engineering, physical intrusion, spam, or denial-of-service testing

## Reporting a Vulnerability

Report suspected vulnerabilities **privately**. Do not create public issues for security findings.

**Preferred channels:**

- GitHub Security Advisory (“Report a vulnerability”) in the affected repository
- Email: opensource_security@fenstreamtech.group
- Optional profile: `http://fenstreamtech.group/.well-known/security.txt`

Please include:

- affected repository, component, and version/commit
- vulnerability description and impact
- clear reproduction steps
- non-destructive proof-of-concept
- logs/screenshots where relevant

## Response Targets

For valid reports:

- acknowledgement: within 2 business days
- initial triage: within 5 business days
- remediation plan or status update: within 10 business days

Complex issues may require additional time; periodic updates will be provided.

## Handling and Disclosure

Process:

1. intake and validation
2. severity assessment (CVSS-informed)
3. remediation planning
4. fix development and verification
5. coordinated disclosure

Severity guide:

- Critical/High: expedited response and patching
- Medium: scheduled in upcoming maintenance/security release
- Low: backlog-prioritized remediation

## Researcher Conduct Requirements

Testing must not:

- violate law or policy
- access or retain unnecessary data
- alter or destroy data
- disrupt service availability
- use destructive/high-intensity scanning
- involve social engineering, phishing, or physical intrusion
- include extortion or payment demands

## Safe Harbor

Good-faith research performed in line with this policy will be treated as authorized activity under this program.

## Related

- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [SUPPORT.md](SUPPORT.md)
