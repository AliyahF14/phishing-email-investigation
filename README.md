Phishing Email Threat Investigation & Incident Response
**Overview**
This project is a simulated cybersecurity investigation involving a suspected phishing email impersonating Microsoft 365 Security.

The investigation demonstrates a structured approach to identifying phishing indicators, analyzing suspicious email characteristics, performing basic threat-intelligence research, assessing potential risk, and developing incident-response recommendations.

>**Disclaimer:** This project is a controlled simulation created for educational and portfolio purposes. No real organization, employee, credentials, or malicious infrastructure were involved.

**Scenario**
An employee at Northstar Financial Services received an email claiming to be from Microsoft 365 Security.

The message warned that the employee’s Microsoft 365 account would be suspended within 24 hours unless they completed an account-verification process through an included link.

The objective of the investigation was to determine whether the message represented a phishing attempt and document the appropriate security response.

**Investigation Objectives**
The investigation focused on:

Identifying suspicious characteristics within the email
Analyzing the sender address and domain
Examining the included URL
Performing basic threat-intelligence research
Identifying indicators of compromise
Assessing potential security risks
Developing incident-response recommendations
Documenting findings using a structured security-investigation format

**Tools & Technologies**
GitHub
VirusTotal
ICANN Lookup
Web-based threat-intelligence resources
Markdown
Security investigation and incident-response methodology

**Investigation Process**
The investigation followed a simplified security-analysis workflow:

'''text
Identify
   ↓
Preserve Evidence
   ↓
Analyze Sender
   ↓
Analyze URL & Domain
   ↓
Perform Threat Intelligence Checks
   ↓
Identify Indicators
   ↓
Assess Risk
   ↓
Recommend Response
   ↓
Document Findings
'''

**Key Findings**
Several characteristics indicated that the message was suspicious:

1. Sender Impersonation
The sender used:

security@microsoft-365support.com

The domain was designed to appear associated with Microsoft while not representing an official Microsoft domain.

2. Urgency
The message stated that the employee’s account would be suspended within 24 hours.

This creates pressure for the recipient to act quickly rather than independently verify the request.

3. Fear-Based Messaging
The email warned that failure to verify the account could result in loss of access to email, files, and Microsoft 365 services.

4. Suspicious Verification URL
The email directed the recipient to:

https://microsoft365-security-verification.example/login

The URL was designed to resemble a Microsoft security-verification page.

5. Potential Credential Harvesting
The /login URL path and account-verification scenario indicate the potential for credential harvesting if the message were part of a real phishing campaign.

**Threat Intelligence Results**
VirusTotal
The simulated URL was submitted to VirusTotal.

Result: Item not found.

No existing VirusTotal detection information was available for the simulated URL.

The absence of threat-intelligence detections was not treated as evidence that the URL was safe.

ICANN Lookup
The simulated domain was checked using ICANN Lookup.

Result: Not available.

The .example domain used in this simulation is reserved for documentation/testing purposes and does not represent a real production domain.

**Risk Assessment**
Overall Risk: High

If a recipient interacted with a real phishing page and submitted credentials, potential consequences could include:

- Account compromise
- Unauthorized access to business information
- Exposure of email communications
- Access to business documents
- Internal phishing propagation
- Further compromise of organizational resources
  
Potential risk-reduction controls include:

- Multi-factor authentication
- Email filtering
- Security awareness training
- Phishing-reporting mechanisms
- Domain and URL filtering
- Centralized security logging
- Monitoring for suspicious authentication activity

**Incident Response Recommendations**
Recommended response actions include:

1. Quarantine and remove the phishing message.
2. Search for additional copies of the message.
3. Block confirmed malicious indicators where appropriate.
4. Determine whether the suspicious URL was accessed.
5. Determine whether credentials were submitted.
6. Reset potentially compromised credentials.
7. Revoke active sessions or authentication tokens when appropriate.
8. Verify that MFA is enabled.
9. Review authentication and account activity.
10. Notify affected employees.
11. Document the incident and lessons learned.

**Indicators of Compromise**
Type

Indicator

Assessment

Email Address

security@microsoft-365support.com

Suspicious sender domain

Domain

microsoft-365support.com

Potential Microsoft impersonation

URL

https://microsoft365-security-verification.example/login

Suspicious verification URL

URL Path

/login

Potential credential-harvesting destination

Social Engineering

24-hour suspension warning

Urgency tactic

Social Engineering

Account verification request

Potential credential theft

**Skills Demonstrated**
- Cybersecurity
- Phishing analysis
- Social-engineering analysis
- Threat intelligence
- Indicator identification
- Risk assessment
- Incident response
- Security documentation
  
Technical
- Domain analysis
- URL analysis
- Threat-intelligence research
- GitHub
- Markdown
  
Professional
- Evidence-based analysis
- Technical documentation
- Security recommendations
- Incident communication
- Analytical reasoning
  
  **Project Structure**
phishing-email-investigation/
│
├── README.md
│
├── evidence/
│   └── email-sample.txt
│
├── indicators/
│   └── indicators-of-compromise.md
│
├── investigation-notes.md
├── risk-assessment.md
├── incident-response.md
└── conclusion.md

**Conclusion**
The investigation determined that the simulated email displayed multiple characteristics consistent with a phishing attempt, including brand impersonation, urgency, fear-based messaging, a suspicious sender domain, and an external account-verification URL.

The investigation also demonstrated the importance of evaluating multiple sources of evidence rather than relying on a single threat-intelligence result.

This project represents a controlled simulation and is intended to demonstrate foundational cybersecurity investigation, analysis, documentation, and incident-response skills.

Author
Aliyah Flowers

Entry-Level Cybersecurity Professional


