# Phishing Email Investigation

## Incident Overview 
A SouthStar Financial Services employee received an email claiming to be from Microsoft 365 Security. The email warned that the employee's account would be suspended unless they completed an immediate security verification.

## Initial Assessment
The email contains several characterisitcs commonly associated with phishing and social engineering.

## Initial Indicators
- Suspicious sender address
- Urgent language
- Threat of account suspension
- Request for immediate account verification
- External verification URL
- Urgent deadline intended to pressure the recipient
- Threat of account suspension
- Microsoft brand impersonation
- External account-verification link
- Potential credential-harvesting attempt 

  ## Investigation Status
  Investigation in progress

## Social Engineering Techniques
The email uses several social engineering techniques
1. **Urgency** - The recipient is given a 24-hour deadline
2. **Fear** - The message threatens loss of account access.
3. **Impersonation** - The sender claims to represent Microsoft 365 Security.
4. **Credential Harvesting** - The recipient is directed to an external verification page that could be designed to collect credentials.

## Threat Intelligence Analysis

The suspicious URL was submitted to VirusTotal for analysis.

### Result

VirusTotal returned "Item not found" for the URL.

### Assessment

No existing VirusTotal detection data was available for the URL. The lack
of threat-intelligence results does not establish that the URL is safe.

The URL remains suspicious based on the surrounding evidence, including
the apparent Microsoft impersonation, urgent account-suspension warning,
and request to complete account verification through an external link.

Because this investigation uses a simulated phishing URL, no attempt was
made to access the destination or submit credentials.

## Domain Investigation

The domain `microsoft365-security-verification.example` was checked using
ICANN Lookup.

### Result

The domain was reported as not available for registration.

### Assessment

The domain does not represent a currently registered public domain.
Because this investigation uses a simulated phishing scenario, the result
cannot be used as evidence of a real-world malicious domain registration.

The domain structure was intentionally designed to resemble a Microsoft
security-related domain and demonstrates how an attacker could use a
lookalike domain to impersonate a trusted organization.
