# Sample Organization

## Company Overview

**Company Name:** Northstar Solutions

Northstar Solutions is a fictional mid-sized organization used to simulate realistic Identity and Access Management (IAM) scenarios.

The environment will be used to practice:

- User provisioning
- Role-based access control
- Group management
- Joiner, Mover, and Leaver workflows
- Access reviews
- Least privilege
- Privileged access management
- Identity governance
- Authentication and MFA
- PowerShell automation

---

## Departments

The organization contains the following departments:

- Information Technology
- Information Security
- Human Resources
- Finance
- Sales
- Operations

---

## Department Roles

### Information Technology

**Help Desk Analyst**
- Standard employee access
- Ticketing system
- Remote support tools
- Password reset capability
- Basic Active Directory user support

**Systems Administrator**
- Server administration
- Active Directory administration
- Elevated infrastructure access
- Administrative tools
- Separate privileged account required

---

### Information Security

**Security Analyst**
- Security monitoring platform
- Authentication and security logs
- Incident management system
- Security reporting tools

**Security Administrator**
- Security platform administration
- Elevated security configuration access
- Security policy management
- Privileged account required

---

### Human Resources

**HR Specialist**
- HR information system
- Employee records
- Onboarding and offboarding documentation
- Standard Microsoft 365 access

**HR Manager**
- HR Specialist access
- Department reporting
- Employee management functions
- Approval authority for HR-related access

---

### Finance

**Financial Analyst**
- Financial reporting applications
- Financial data
- Accounting-related resources
- Standard Microsoft 365 access

**Finance Manager**
- Financial Analyst access
- Department reporting
- Financial approval functions
- Approval authority for Finance-related access

---

### Sales

**Sales Representative**
- CRM access
- Customer information
- Sales reporting tools
- Standard Microsoft 365 access

**Sales Manager**
- Sales Representative access
- Team reporting
- Sales management functions

---

### Operations

**Operations Specialist**
- Operations applications
- Inventory and workflow systems
- Standard Microsoft 365 access

**Operations Manager**
- Operations Specialist access
- Department reporting
- Operational management functions

---

## Access Model

Northstar Solutions will use Role-Based Access Control (RBAC).

Users will receive access based primarily on:

1. Department
2. Job role
3. Business need
4. Approved exceptions

Access should follow the Principle of Least Privilege.

Users should only receive the minimum permissions required to perform their assigned responsibilities.

---

## Privileged Access

Administrative access will be separated from standard user access.

For example, a Systems Administrator may have:

- `jsmith@northstarsolutions.com`
  - Standard daily-use account

- `adm-jsmith@northstarsolutions.com`
  - Privileged administrative account

Privileged accounts should only be used when elevated permissions are required.

---

## Access Approval Model

Access requests may require approval from:

- User's manager
- Department manager
- Application owner
- IAM or IT administrator
- Information Security

The required approval will depend on the sensitivity of the requested access.

---

## IAM Security Principles

The lab will follow these principles:

- Least Privilege
- Role-Based Access Control
- Separation of Duties
- Access Accountability
- Business Justification
- Regular Access Reviews
- Controlled Privileged Access
- Documented Approval Processes
