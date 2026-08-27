# Q3 2026 IAM Access Review

## Review Objective

Review user access assignments against current department, role, account status, and documented business need to identify potentially inappropriate or excessive access.

---

## Finding 001 — Cross-Department Direct Access

**User:** Sarah Miller
**User ID:** U002
**Department:** Human Resources
**Role:** HR Specialist
**Account Status:** Active

**Assignment ID:** A027
**Resource:** Finance System
**Access Level:** Standard
**Access Source:** Direct
**Approved By:** U003 — Michael Davis, Finance Manager
**Granted Date:** 2025-02-10

## Observation

Sarah Miller is an HR Specialist with direct access to the Finance System.

The standard access model for the HR Specialist role includes HR-related systems and Microsoft 365. Finance System access is not part of the standard HR Specialist role.

The presence of this access does not automatically indicate an access-control violation because the assignment may have been granted for a legitimate business reason.

## Investigation Steps

* Review the original access request, approval record, or related ticket.
* Verify the documented business justification for Finance System access.
* Confirm with Michael Davis, Finance Manager, that the access is still required.
* Confirm with Sarah Miller's manager that the access aligns with Sarah's current responsibilities.
* Review whether the direct assignment is permitted under organizational access policy.
* Determine whether the access should remain as an approved exception or be removed.

## Initial Risk Assessment

**Status:** Pending Review

The access represents a potential least-privilege concern because it falls outside Sarah Miller's standard HR role.

No access change should be made solely based on the department mismatch without first validating the business justification and approval history.

## Recommended Action

Retain the access while the review is conducted unless organizational policy or the sensitivity of the Finance System requires temporary restriction.

If a valid business justification and appropriate approval are confirmed, document the access as an approved exception.

If the access cannot be justified, follow the established access-removal process and document the remediation.

## Review Status

**Pending Business Justification**
