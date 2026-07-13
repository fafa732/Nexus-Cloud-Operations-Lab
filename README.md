# Nexus Cloud Operations Lab

## Project Overview

Nexus Cloud Operations Lab is a hands-on IT Support and Cloud Operations portfolio project.

The project simulates support work for a fictional organisation called Nexus Retail Group. It demonstrates practical skills in Microsoft Azure, Microsoft Entra ID, Active Directory, Windows Server, Jira Service Management, Azure Backup, Azure Monitor, file share permissions, and Group Policy.

This project was completed from the perspective of a junior IT Support Technician, MSP Tier 1 Technician, Service Desk Analyst, or Junior Cloud Support Technician.

## Business Scenario

Nexus Retail Group is a fictional company with the following departments:

- IT
- Finance
- HR
- Sales
- Warehouse

The organisation needs a structured support environment where users, groups, permissions, storage access, tickets, server monitoring, backups, and endpoint policies are managed professionally.

## Tools Used

- Microsoft Azure
- Microsoft Entra ID
- Windows Server
- Active Directory Domain Services
- Active Directory Users and Computers
- Group Policy Management
- Azure Storage
- Azure RBAC
- Azure Backup
- Recovery Services Vault
- Azure Monitor
- Azure Alerts
- Log Analytics
- KQL
- Jira Service Management
- Azure DevOps Boards
- Remote Desktop Protocol
- GitHub
- LinkedIn

## Completed Project Areas

### Azure Foundation

Created and organised Azure resources for the lab environment, including resource groups, cost awareness, tagging, and basic cloud structure.

### Azure Networking

Created the core Azure virtual network, subnets, and network security group structure for the Nexus environment.

### Microsoft Entra ID

Created cloud users and groups for Nexus departments. Configured group membership and disabled an ex-employee account to simulate offboarding.

### Azure RBAC and Storage Access

Created secure Azure storage, configured a private Finance container, assigned RBAC access to the Finance group, and validated least privilege access.

### Ticket Tracking

Used Azure DevOps Boards during the early foundation phase for support-style ticket tracking. Jira Service Management later became the official service desk platform for the project.

### Jira Service Management

Created the Nexus Cloud Operations Service Desk and documented support tasks using Jira tickets, priorities, statuses, and resolution notes.

### Active Directory

Built a Windows Server VM in Azure and promoted it to a domain controller for the nexus.local domain. Created OUs, users, groups, and disabled user workflows.

### Helpdesk Support Tasks

Completed practical helpdesk tasks such as password reset, requiring password change at next logon, group access review, and disabled user review.

### File Server and Permissions

Created department file shares for Finance, HR, Sales, and Warehouse. Configured NTFS and share permissions using Active Directory security groups and validated least privilege access.

### Backup Readiness

Created a Recovery Services Vault and configured Azure Backup protection for the NexusAD-01 server.

### Monitoring and Alerts

Reviewed VM metrics, configured Azure Monitor alerting, registered the Microsoft.Insights provider, created an action group, and created a high CPU alert rule.

### Intune Access Review

Reviewed Microsoft Intune admin center access. Intune/MDM configuration was not marked as completed because Tenant Status access was blocked with a 401 / No Permission issue.

### Group Policy Endpoint Management

Used Active Directory Group Policy as the endpoint management fallback. Configured Control Panel restriction, mapped department drives, password policy, account lockout policy, and logon banner.

## Key Skills Demonstrated

- Azure administration
- Microsoft Entra ID administration
- Active Directory administration
- Windows Server support
- User and group management
- Password reset support
- User offboarding
- RBAC access control
- Least privilege access review
- Azure Storage security
- File share permissions
- NTFS permissions
- Jira ticket documentation
- Backup readiness
- Azure monitoring and alerts
- Group Policy configuration
- Endpoint management basics
- Troubleshooting and documentation

## Important Accuracy Note

This is a portfolio lab, not a production environment.

Nexus Retail Group is fictional.

Microsoft Intune and MDM were reviewed but not fully configured because access was blocked by a 401 / No Permission issue. The project continued with Active Directory Group Policy as the hands-on endpoint management fallback.

## Final Outcome

The Nexus Cloud Operations Lab demonstrates how Azure, Entra ID, Active Directory, Windows Server, Jira Service Management, Azure Backup, Azure Monitor, and Group Policy can be used together to support users, secure access, manage infrastructure, document tickets, and troubleshoot real issues in an MSP-style environment.
