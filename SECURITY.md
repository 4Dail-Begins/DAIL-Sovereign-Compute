Sovereign Compute Standard (SCS‑1)
Dynamic Artificial Intelligence Laboratories (DAIL)

Reporting Security or Integrity Issues
Security, integrity, and reproducibility are core principles of SCS‑1. Any suspected vulnerability, implementation weakness, or integrity concern must be reported through the process defined in this document. This ensures that issues are handled responsibly, transparently, and in alignment with sovereign compute requirements.
Reports may include:
• 	Integrity violations in implementations of SCS‑1
• 	Weaknesses in provenance, attestation, or trust‑boundary controls
• 	Reproducibility failures that may indicate tampering or misconfiguration
• 	Architectural or governance gaps that create security exposure
• 	Documentation errors that could lead to insecure implementations
All reports are confidential until reviewed and resolved.

How to Submit a Security Report
Security issues must be submitted through the following channels:
• 	Primary: Email the DAIL Standards Council (DSC) at the designated security reporting address.
• 	Secondary: Open a private security advisory in the repository’s “Security” tab (if enabled).
• 	Not permitted: Public GitHub issues or pull requests for undisclosed vulnerabilities.
A valid report must include:
• 	Description of the issue
• 	Steps to reproduce (if applicable)
• 	Affected section(s) of SCS‑1
• 	Potential impact on sovereignty, integrity, or reproducibility
• 	Any recommended mitigations or observations
Incomplete reports may be returned for clarification.

Response and Disclosure Process
The DAIL Standards Council follows a structured process:
1. 	Acknowledgment
Reporters receive confirmation within a defined response window.
2. 	Assessment
Technical reviewers evaluate severity, scope, and impact.
3. 	Mitigation Planning
The DSC determines required changes to the standard or guidance.
4. 	Resolution
Fixes or clarifications are prepared and reviewed.
5. 	Coordinated Disclosure
Public disclosure occurs only after mitigation is complete and approved.
6. 	Version Update
If the issue affects the standard text, a new version (minor or major) is published and recorded in the CHANGELOG.

Severity Classification
Issues are classified into four categories:
• 	Critical: Compromises sovereignty, integrity, or reproducibility at a systemic level.
• 	High: Affects trust boundaries, attestation, or provenance in a significant way.
• 	Moderate: Impacts governance, documentation, or implementation clarity.
• 	Low: Minor editorial or non‑security‑critical issues.
Severity determines disclosure timing and versioning requirements.

Reporter Expectations and Recognition
Reporters must:
• 	Maintain confidentiality until coordinated disclosure
• 	Avoid exploiting vulnerabilities
• 	Provide accurate, good‑faith information
DAIL may acknowledge contributors publicly after resolution, unless anonymity is requested.

Scope of This Policy
This policy applies to:
• 	Implementations of SCS‑1
• 	Interpretations of SCS‑1 that create security exposure
• 	Documentation or annexes that influence secure deployment
• 	Tools, examples, or reference materials associated with SCS‑1
It does not apply to unrelated systems, infrastructure, or third‑party software.

Amendments to This Policy
Changes to this SECURITY.md follow the same governance and change‑control process as SCS‑1 itself. Amendments require approval from the DAIL Standards Council and must be recorded in the CHANGELOG.
