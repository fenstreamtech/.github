# Security Policy

## 1. Purpose

Abbeygate IT is committed to maintaining the security and integrity of the **macOS-Clearance-Kit** project.  
This policy defines how security vulnerabilities should be reported, triaged, remediated, and disclosed.

## 2. Scope

This policy applies to:

- Source code and release artifacts published in this repository
- Official project documentation and configuration examples
- Supported release versions listed below

This policy does not apply to:

- Third-party services, tools, or infrastructure outside project control
- Forks or downstream distributions not maintained by Abbeygate IT
- Social engineering, physical intrusion, spam, or denial-of-service testing

## 3. Supported Versions

Security updates are provided for actively maintained versions only.

| Version | Supported |
| --- | --- |
| Latest stable release | Yes |
| Previous minor release | Yes |
| Older releases | No |
| Development branches | Best effort |

## 4. Reporting a Vulnerability

Please report vulnerabilities **privately** and do not disclose details publicly before remediation.

### Preferred reporting channels

- **GitHub Security Advisory**: Use “Report a vulnerability” in this repository
- **Email**: `github.project.security@abbeygate-it.co.uk`

### Information to include

- Description of the vulnerability and potential impact
- Affected versions, commits, and environment details
- Clear reproduction steps and proof-of-concept (if available)
- Suggested remediation or mitigation (optional)

## 5. Response Service Levels

For valid reports, our target response timeline is:

- **Acknowledgement**: within 2 business days  
- **Initial triage**: within 5 business days  
- **Remediation plan or status update**: within 10 business days  

Complex issues may require additional time. We will provide periodic updates until closure.

## 6. Triage and Remediation Process

All reports are handled through a structured workflow:

1. Intake and validation
2. Severity classification (CVSS-informed)
3. Risk assessment and prioritization
4. Remediation development and internal testing
5. Patch/release preparation
6. Coordinated disclosure

Typical prioritization:

- **Critical / High**: expedited handling and urgent patching
- **Medium**: addressed in next scheduled security or maintenance release
- **Low**: remediated according to product roadmap and risk profile

## 7. Coordinated Disclosure

We support responsible disclosure and request that reporters:

- Allow reasonable time for remediation before public disclosure
- Avoid publishing exploit details before fixes or mitigations are available
- Coordinate publication timelines with maintainers where possible

Reporter recognition will be provided (with consent).

## 8. Safe Harbor

If you act in good faith and follow this policy, Abbeygate IT will not pursue legal action for security research that:

- Avoids privacy violations, data corruption, and service disruption
- Does not involve unauthorized persistence or lateral movement
- Is limited to what is necessary to demonstrate the vulnerability
- Is promptly reported through approved private channels

## 9. Security Best Practices for Users

Users should:

- Keep deployments on supported versions
- Apply updates promptly
- Follow least-privilege and credential hygiene practices
- Monitor release notes and advisories for security updates

## 10. Dependency and Supply Chain Security

The project aims to reduce supply-chain risk through:

- Ongoing dependency review and updates
- Monitoring of relevant vulnerability advisories
- Use of repository security tooling where appropriate

## 11. Policy Changes

This policy may be updated periodically to reflect operational, legal, or security requirements.  
Material changes will be published in this repository.

---

For security concerns, use private reporting channels only. Public vulnerability reports may be closed without detail to protect users.
