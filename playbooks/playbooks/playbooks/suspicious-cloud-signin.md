# Suspicious Cloud Sign-in Investigation

## Overview

Suspicious sign-in events may indicate credential compromise or attacker reconnaissance.

## Detection

Alerts may originate from:

• Cloud identity protection tools
• SIEM alerts
• Impossible travel detections

## Investigation Steps

1. Identify the user account involved.
2. Review login IP address and geolocation.
3. Compare with the user's normal login behavior.
4. Check for MFA authentication events.
5. Investigate additional activity after login.

## Containment

• Require password reset.
• Revoke access tokens.
• Apply conditional access restrictions.

## Remediation

• Confirm the legitimacy of the login.
• Update detection policies if necessary.
