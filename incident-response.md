# Incident Response Recommendations

## Incident Classification

**Incident Type:** Phishing / Credential Harvesting Attempt

**Severity:** High

## Immediate Response

### 1. Quarantine the Email

Remove the phishing email from the employee's mailbox and search for
copies of the message in other employee mailboxes.

### 2. Block the Indicators

Security administrators should block identified malicious or suspicious
domains and URLs through available email security, DNS, web filtering,
and endpoint security controls.

### 3. Determine Whether the Link Was Accessed

Review available security logs to determine whether the employee or other
users accessed the suspicious URL.

### 4. Determine Whether Credentials Were Submitted

If the employee entered credentials into the suspected phishing page,
treat the account as potentially compromised.

### 5. Reset Potentially Compromised Credentials

Require a password reset and revoke active sessions or authentication
tokens when appropriate.

### 6. Verify Multi-Factor Authentication

Confirm that MFA is enabled and that no unauthorized authentication
methods or devices have been added to the account.

### 7. Review Account Activity

Investigate recent authentication activity, mailbox activity, and other
available security logs for suspicious behavior.

## Communication

Notify affected employees about the phishing attempt and provide
guidance on how to identify similar messages.

## Long-Term Recommendations

The organization should consider:

- Security awareness training
- Phishing simulations
- Email filtering
- MFA enforcement
- Conditional access policies
- Domain reputation filtering
- User phishing-reporting tools
- Centralized security logging
- Regular review of account activity

## Incident Closure Criteria

The incident can be considered resolved after:

1. The phishing email has been removed or quarantined.
2. Relevant indicators have been blocked where appropriate.
3. Potentially affected accounts have been investigated.
4. Compromised credentials have been reset.
5. Suspicious authentication activity has been ruled out or remediated.
6. Affected users have been notified.
7. Relevant findings have been documented.
