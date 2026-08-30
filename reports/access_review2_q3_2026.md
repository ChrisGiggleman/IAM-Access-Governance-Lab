## Finding 002 — Terminated User with Active Access

**User:** Liam Lewis
**User ID:** U015
**Department:** Sales
**Role:** Sales Representative
**Account Status:** Terminated

**Assignment ID:** A026
**Resource:** CRM
**Access Level:** Standard
**Access Source:** Role-Based
**Approved By:** U005 — Olivia Wilson, Sales Manager
**Granted Date:** 2024-01-15
**Assignment Status:** Active

## Observation

Liam Lewis is identified as a terminated employee, but his CRM access assignment remains active.

Unlike an unusual cross-department entitlement, active access associated with a confirmed terminated identity represents an immediate access-control and deprovisioning concern.

## Immediate Response

* Verify the termination against the authoritative HR or offboarding record.
* If termination is confirmed, disable or restrict the identity according to organizational policy.
* Revoke active sessions or remaining application access where authorized.
* Prevent additional access while the deprovisioning failure is investigated.

## Investigation Steps

* Review the original termination and offboarding request.
* Confirm the effective termination date.
* Review deprovisioning tickets and workflow records.
* Determine whether the CRM entitlement was missed during offboarding.
* Identify whether any additional active groups, applications, licenses, or permissions remain assigned.
* Determine whether the failure resulted from a manual processing error, incomplete request, workflow failure, or other control gap.
* Verify that all required access has been removed after remediation.

## Risk Assessment

**Risk Level:** High

A terminated identity retaining active application access creates a significant security risk because a former employee may still be able to access organizational systems or data.

If credentials or active sessions remain usable, the account could also be used by an unauthorized party.

## Recommended Action

After termination is confirmed:

1. Disable or restrict the identity according to policy.
2. Revoke remaining CRM access and active sessions.
3. Review the account for additional active entitlements.
4. Complete the required deprovisioning process.
5. Retain or delete the account according to organizational retention policy.
6. Document the cause of the deprovisioning failure.
7. Escalate the control gap to the appropriate IAM, security, or management team for review.

## Review Status

**Remediation Required — Confirm Termination and Revoke Access**
