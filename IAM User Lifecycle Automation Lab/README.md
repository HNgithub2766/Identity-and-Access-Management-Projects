# IAM User Lifecycle Automation Lab

## Overview

This project demonstrates Identity and Access Management (IAM) processes commonly used in enterprise environments. It focuses on automating user onboarding and offboarding workflows using PowerShell while applying Role-Based Access Control (RBAC), least privilege principles, and audit logging.

The workflow is inspired by real-world IAM processes used to support employee onboarding, offboarding, access provisioning, group assignment and licence management within enterprise environments. In practice, similar processes were performed using ManageEngine ADManager Plus, where CSV-driven provisioning workflows automated account creation, group assignment and access allocation. This project recreates those concepts using PowerShell to demonstrate IAM automation and governance principles.

---

## Objectives

- Automate user onboarding activities
- Automate user offboarding activities
- Apply Role-Based Access Control (RBAC)
- Improve consistency in access provisioning
- Support audit and compliance requirements
- Demonstrate Identity Governance concepts

---

## Technologies Used

- PowerShell
- Active Directory
- CSV Import
- RBAC Concepts
- IAM Governance Principles

---

## Features

### User Onboarding

The onboarding script:

- Creates a new Active Directory account
- Generates usernames automatically
- Assigns department-specific security groups
- Applies required access permissions
- Exchange Online licence assignment
- MFA policy enforcement
- Records actions in an audit log
  

### User Offboarding

The offboarding script:

- Disables user accounts
- Removes group memberships
- Revokes access permissions
- Moves accounts to a disabled users OU
- Generates audit logs for compliance purposes

---

## Workflow

```text
Manager Request
        ↓
HR Approval
        ↓
CSV Import
        ↓
Account Creation
        ↓
Group Assignment
        ↓
Access Provisioning
        ↓
Audit Log Generated

