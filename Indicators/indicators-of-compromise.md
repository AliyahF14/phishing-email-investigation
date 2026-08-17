# Indicators of Compromise (IOCs)

## Incident

Phishing email impersonating Microsoft 365 Security.

## Identified Indicators

| Type | Indicator | Assessment |
|---|---|---|
| Email Address | security@microsoft-365support.com | Suspicious sender domain |
| Domain | microsoft-365support.com | Potential Microsoft impersonation |
| URL | https://microsoft365-security-verification.example/login | Suspicious account-verification URL |
| URL Path | /login | Potential credential-harvesting destination |
| Social Engineering | 24-hour account suspension warning | Urgency/fear tactic |
| Social Engineering | Request for account verification | Potential credential theft |

## Threat Intelligence Results

### VirusTotal

Result: Item not found.

No existing VirusTotal detection information was available for the
simulated URL.

### ICANN Lookup

Result: Not available.

The `.example` domain used in this simulation is not a registered
production domain.

## Analyst Note

The indicators above are associated with a simulated phishing scenario.
They should not be interpreted as evidence of an active real-world
malicious campaign.
