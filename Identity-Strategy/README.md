# Greenwood-Accountant-Microsoft-365-Identity-Project
Greenwood Accountants
Microsoft 365 Identity Strategy Design Document
1. Introduction

Greenwood Accountants is a growing accounting firm that requires a secure, scalable, and well-managed identity system to support its employees,cloud services and its various departments. This document outlines the identity strategy that will be implemented using Microsoft 365 and Microsoft Entra ID to ensure secure access, proper user management, and compliance with organizational standards.

2. Business Overview

Greenwood Accountants operates across multiple departments including:

Finance
Human Resources
Audit
Administration
Information Technology (IT)

The organization currently manages employee accounts manually, which creates challenges such as:

Inconsistent user naming
Delayed onboarding and offboarding
Weak access control
Increased security risks
Difficulty managing permissions

To improve operational efficiency and security, Greenwood Accountants will implement a centralized cloud identity solution using Microsoft 365.

3. Project Objectives

The objectives of this identity strategy are to:

Create a centralized identity management system
Improve security through role-based access control
Standardize user account naming conventions
Enable secure access to Microsoft 365 services
Simplify onboarding and offboarding processes
Support future business growth and scalability
4. Identity Solution Design
4.1 Identity Platform

The organization will use:

Microsoft 365
Microsoft Entra ID (formerly Azure Active Directory)

These platforms will provide:

User authentication
Identity and access management
Secure cloud access
Group-based permissions
Multi-factor authentication (MFA)
5. User Principal Name (UPN) Naming Convention
Standard Format

The organization will use the following naming structure:

firstname.lastname@greenwoodaccountants.com

Examples
john.smith@greenwoodaccountants.com
mary.jones@greenwoodaccountants.com
Edge Case Rules

Where duplicate names exist, the following rules will apply:

Situation	Naming Format Example
Duplicate full name	john.smith2@greenwoodaccountants.com
Middle initial available	john.a.smith@greenwoodaccountants.com
Long names	Use shortened approved format
Temporary staff	temp.firstname@greenwoodaccountants.com

This ensures all accounts remain unique and easy to identify.

6. Identity and Access Management Strategy
Role-Based Access Control (RBAC)

Permissions will be assigned based on job responsibilities.

Department	Access Level
Finance	Financial applications and reports
HR	Employee records and HR systems
Audit	Audit documentation and reporting tools
IT	Administrative and security controls
Administration	Shared operational resources
7. Security Measures
Multi-Factor Authentication (MFA)

All users will be required to use MFA when signing into Microsoft 365 services.

Conditional Access

Conditional Access policies will be implemented to:

Restrict unauthorized access
Enforce secure login requirements
Protect sensitive company information
Password Policy

Passwords must:

Be at least 12 characters long
Include uppercase, lowercase, numbers, and symbols
Be changed periodically according to company policy
8. User Lifecycle Management
Onboarding

New employees will:

Receive a Microsoft 365 account
Be assigned to the appropriate department group
Receive role-based permissions
Complete MFA registration
Offboarding

When employees leave:

Accounts will be disabled immediately
Access permissions will be removed
Licenses will be reclaimed
Data retention policies will be applied
9. Group Management Strategy

Security groups and Microsoft 365 groups will be created for each department to simplify permission management.

Examples
Finance-Team
HR-Team
Audit-Team
IT-Admins

This approach reduces administrative overhead and improves consistency.

10. Compliance and Monitoring
11. The IT department will:

Monitor sign-in activities
Review audit logs regularly
Track suspicious login attempts
Ensure compliance with company security policies
Microsoft 365 security and compliance tools will support monitoring and reporting activities.

12. Backup and Recovery

Cloud-based redundancy provided by Microsoft 365 will help ensure service availability. Administrative recovery procedures will also be documented for accidental account deletion or compromise.

12. Conclusion

The implementation of Microsoft 365 identity services at Greenwood Accountants will provide a secure, scalable, and efficient identity management environment. The strategy supports business growth, strengthens security, improves access management, and simplifies IT administration across the organization.
