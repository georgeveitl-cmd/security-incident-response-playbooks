# Phishing Incident Response Playbook

## Overview

Phishing attacks attempt to trick users into revealing credentials or installing malicious software. This playbook outlines the investigation and response process.

## Detection

Phishing incidents may be detected through:

• User reports  
• Email security alerts  
• Suspicious login activity following a phishing email

## Investigation Steps

1. Identify the affected user account.
2. Review email headers and sender domain.
3. Determine whether credentials were entered into a phishing site.
4. Review authentication logs for suspicious login activity.
5. Check for unusual mailbox activity or rule creation.

## Containment

• Disable compromised accounts if necessary.  
• Reset user credentials.  
• Revoke active sessions.  
• Block malicious sender domains.

## Remediation

• Remove malicious emails from user mailboxes.
• Re-enable accounts after security validation.
• Provide user awareness training if necessary.

## Post-Incident Actions

• Update phishing detection rules.
• Document incident timeline.
• Review security controls to prevent recurrence.

## MITRE ATT&CK Mapping

Technique: Phishing (T1566)
