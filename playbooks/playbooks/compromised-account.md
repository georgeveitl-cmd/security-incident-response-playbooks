# Compromised Account Investigation

## Overview

Compromised accounts are one of the most common entry points for attackers. Early detection and response are critical to limiting impact.

## Indicators

Possible signs of compromise include:

• Impossible travel login activity  
• Unusual login locations  
• Privilege escalation activity  
• Unrecognized MFA approvals  

## Investigation Steps

1. Review authentication logs.
2. Identify suspicious IP addresses or login locations.
3. Check for newly assigned privileges.
4. Review recent password resets or MFA changes.
5. Examine access to sensitive systems or data.

## Containment

• Disable the account temporarily.
• Force password reset.
• Revoke active sessions.
• Review conditional access policies.

## Remediation

• Restore account access after validation.
• Monitor for repeated suspicious activity.
• Investigate affected resources.

## MITRE ATT&CK Mapping

Technique: Valid Accounts (T1078)
