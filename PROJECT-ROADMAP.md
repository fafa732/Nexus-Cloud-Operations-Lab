# Project Roadmap

This file shows the completed roadmap for the Nexus Cloud Operations Lab.

The project was built as a practical IT Support, Cloud Operations, and MSP-style service desk portfolio lab.

## Roadmap Status

Completed.

The hands-on technical work is complete. The remaining work is GitHub organisation, screenshot upload, final documentation cleanup, and using the project for CV, LinkedIn, GitHub, and job applications.

---

## Phase 1 — Azure Foundation

Purpose:
Set up the basic Azure structure for the lab.

Completed work:

- Created Azure resource groups
- Applied basic resource organisation
- Reviewed cost awareness
- Created budget/cost control evidence
- Prepared the cloud environment for identity, networking, storage, monitoring, and server workloads

Related days:

- Day 1 — Project Overview
- Day 2 — Azure Foundation and Cost Control

Status:
Completed

---

## Phase 2 — Azure Networking

Purpose:
Create the basic network structure for the Nexus environment.

Completed work:

- Created virtual network
- Created subnets
- Created network security group structure
- Associated networking components
- Captured Azure networking evidence

Related day:

- Day 3 — Azure Networking

Status:
Completed

---

## Phase 3 — Microsoft Entra ID and Cloud Identity

Purpose:
Build and review cloud identity basics.

Completed work:

- Created Entra ID users
- Created Entra ID groups
- Assigned users to department groups
- Disabled an ex-employee account
- Reviewed cloud identity lifecycle basics

Related day:

- Day 4 — Entra ID Users and Groups

Status:
Completed

---

## Phase 4 — IAM, RBAC, and Storage Security

Purpose:
Practise access control, least privilege, and secure storage access.

Completed work:

- Reviewed IAM role assignments
- Created secure Azure Storage structure
- Created private Finance storage container
- Assigned RBAC access to the Finance group
- Tested Finance access
- Validated that Sales did not have Finance access
- Documented least privilege access testing

Related days:

- Day 5 — IAM Access Review
- Day 6 — Storage RBAC
- Day 7 — RBAC Access Testing

Status:
Completed

---

## Phase 5 — Early Ticket Tracking

Purpose:
Start documenting technical work using support-style tickets.

Completed work:

- Used Azure DevOps Boards for early ticket tracking
- Created support-style work items
- Documented access requests
- Documented RBAC validation
- Documented ticket resolutions

Related days:

- Day 8 — Azure DevOps Ticket Tracking
- Day 9 — Finance Access Ticket Resolution
- Day 10 — Sales Access Validation

Status:
Completed

---

## Phase 6 — Monitoring Foundation

Purpose:
Introduce Azure monitoring and alerting.

Completed work:

- Created/reviewed Log Analytics workspace
- Practised basic KQL queries
- Created Azure Monitor action group
- Created alert rule evidence
- Documented monitoring setup

Related days:

- Day 11 — Log Analytics and KQL
- Day 12 — Azure Monitor Alerts

Status:
Completed

---

## Phase 7 — MSP Expansion and Jira Service Management

Purpose:
Move the project into a more realistic MSP/service desk structure.

Completed work:

- Planned MSP-style support structure
- Replaced Freshdesk with Jira Service Management
- Created Nexus Cloud Operations Service Desk
- Created Jira support tickets
- Reviewed ticket statuses, priorities, and SLA thinking
- Documented escalation workflow

Related days:

- Day 13 — MSP Expansion and Jira Service Management Planning
- Day 14 — Jira Service Management Setup
- Day 15 — Jira SLA and MSP Support Structure

Status:
Completed

---

## Phase 8 — Windows Server and Active Directory

Purpose:
Build traditional Windows Server identity support skills.

Completed work:

- Created Windows Server VM in Azure
- Configured static private IP
- Installed Active Directory Domain Services
- Promoted server to domain controller
- Created the nexus.local domain
- Verified Active Directory Users and Computers
- Created OUs, users, and groups
- Disabled ex-employee account
- Practised password reset support
- Reviewed group membership and access controls

Related days:

- Day 16 — Active Directory Build
- Day 17 — AD Users, Groups, and OUs
- Day 18 — AD Helpdesk Support Tasks

Status:
Completed

---

## Phase 9 — AD and Entra ID Identity Review

Purpose:
Compare traditional Active Directory identity with Microsoft Entra ID identity.

Completed work:

- Reviewed AD users
- Reviewed AD groups
- Reviewed AD OU structure
- Reviewed Entra ID users
- Reviewed Entra ID groups
- Reviewed disabled user handling
- Captured identity lifecycle evidence

Related day:

- Day 19 — AD and Entra ID Identity Review

Status:
Completed

---

## Phase 10 — File Server and Permissions

Purpose:
Practise file server administration and least privilege access control.

Completed work:

- Created department file share folders
- Created Finance, HR, Sales, and Warehouse shares
- Configured share and NTFS permissions
- Assigned access using AD security groups
- Validated that Sales did not have Finance share access
- Documented file access support tickets in Jira

Related day:

- Day 20 — File Server and Permissions

Status:
Completed

---

## Phase 11 — Backup Readiness

Purpose:
Practise backup configuration and recovery readiness documentation.

Completed work:

- Created Recovery Services Vault
- Enabled Azure Backup for NexusAD-01
- Used enhanced backup policy when required
- Reviewed backup status and pre-checks
- Documented backup readiness in Jira

Related day:

- Day 21 — Backup Readiness

Status:
Completed

---

## Phase 12 — Server Monitoring and Alerts

Purpose:
Practise operational monitoring and alert creation.

Completed work:

- Reviewed VM CPU metrics
- Reviewed VM availability metrics
- Registered Microsoft.Insights provider
- Created Azure Monitor action group
- Created high CPU alert rule
- Documented alerting setup and troubleshooting in Jira

Related day:

- Day 22 — Monitoring and Alerts

Status:
Completed

---

## Phase 13 — Intune Access Review

Purpose:
Review Microsoft Intune access and decide the endpoint management route.

Completed work:

- Opened Microsoft Intune admin center
- Reviewed access to tenant status/admin area
- Identified 401 / No Permission issue
- Documented that Intune/MDM configuration was blocked
- Decided to continue endpoint management using Active Directory Group Policy

Related day:

- Day 23 — Intune Access Review

Status:
Completed as access review.

Important note:
Microsoft Intune and MDM were not configured.

---

## Phase 14 — Group Policy Endpoint Management

Purpose:
Use Active Directory Group Policy as the hands-on endpoint management fallback.

Completed work:

- Opened Group Policy Management
- Created endpoint user policy GPO
- Linked GPO to Nexus Retail Group OU
- Configured Control Panel restriction
- Configured department mapped drives
- Configured password policy
- Configured account lockout policy
- Configured logon banner policy
- Documented endpoint management tasks in Jira

Related day:

- Day 24 — Group Policy Endpoint Management

Status:
Completed

---

## Final Project Outcome

The Nexus Cloud Operations Lab demonstrates practical experience across:

- Microsoft Azure
- Microsoft Entra ID
- Active Directory
- Windows Server
- Jira Service Management
- Azure RBAC
- Azure Storage
- Azure Backup
- Azure Monitor
- Group Policy
- File share permissions
- User administration
- Access review
- Ticket documentation
- MSP-style support workflow

---

## Not Completed / Not Claimed

The following were reviewed or considered but not claimed as completed:

- Full Microsoft Intune configuration
- Full MDM deployment
- Full hybrid identity sync
- Production environment deployment
- Real company environment
- Real client data

---

## Next Steps After Roadmap

- Upload cleaned screenshots
- Add individual day folders
- Add runbooks
- Add ticket notes
- Add final project report
- Use the GitHub repository for job applications, CV support, and interview discussions
