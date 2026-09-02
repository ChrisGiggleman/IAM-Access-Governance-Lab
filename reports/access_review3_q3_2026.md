## Finding 003 — Help Desk User with Direct Privileged Active Directory Access

**User:** Alex Jackson
**User ID:** U011
**Department:** Information Technology
**Role:** Help Desk Analyst
**Account Status:** Active

**Assignment ID:** A028
**Resource:** Active Directory
**Access Level:** Privileged
**Access Source:** Direct
**Approved By:** U009 — Chris Martinez, Systems Administrator
**Granted Date:** 2026-01-12
**Assignment Status:** Active

## Observation

Alex Jackson is an active Help Desk Analyst with direct Privileged access to Active Directory.

Alex already has a standard role-based Active Directory Help-Desk entitlement through assignment A021. The additional privileged entitlement is outside the normal access associated with his Help Desk role.

The presence of privileged access does not automatically indicate an access-control violation because elevated permissions may be required for specific administrative responsibilities. However, the entitlement should be reviewed to confirm that it remains necessary and appropriately controlled.

## Investigation Steps

* Review the original access request, approval ticket, and supporting documentation for assignment A028.
* Determine the business reason the privileged Active Directory access was originally granted.
* Verify whether the access was intended to be permanent or temporary.
* Confirm with Chris Martinez that the privileged access is still required for Alex Jackson's current responsibilities.
* Compare the entitlement against the standard Help Desk role and identify the specific administrative tasks that require additional privilege.
* Determine what Active Directory actions the privileged entitlement allows Alex to perform.
* Review whether the level of privilege granted is greater than what is required for the documented task.
* Determine whether organizational policy requires privileged access to use a separate administrative account, privileged access management solution, time-limited access, or additional monitoring.
* Verify whether an expiration date or periodic review requirement should have been associated with the entitlement.

## Risk Assessment

**Risk Level:** Medium to High

Privileged Active Directory access may allow a user to perform sensitive administrative actions beyond standard Help Desk responsibilities.

Depending on the permissions associated with the entitlement, the user may be able to modify user accounts, security groups, permissions, authentication settings, or other sensitive directory configurations.

Standing privileged access also increases the potential impact of credential compromise, misuse, or administrative error.

The risk should therefore be evaluated based on the specific permissions granted, documented business requirement, duration of access, and controls applied to the privileged entitlement.

## Recommended Action

Do not immediately remove the privileged entitlement solely because Alex Jackson is a Help Desk Analyst.

Complete the access review and determine whether a current business justification exists.

If the privileged access is still required:

1. Document the approved business justification.
2. Confirm that the current level of privilege is the minimum required.
3. Determine whether the access should use a separate privileged account.
4. Apply an expiration or future review date where appropriate.
5. Ensure privileged activity is logged and monitored according to organizational policy.
6. Document the manager or access-owner confirmation supporting continued access.

If the access is no longer required, cannot be justified, or exceeds Alex's current responsibilities:

1. Follow the established access-removal process.
2. Remove or reduce the privileged entitlement.
3. Verify that Alex retains only the access required for his Help Desk responsibilities.
4. Document the remediation and final access state.

## Review Status

**Pending Business Justification and Privileged Access Review**
