# Ticket Index

This file summarises the Jira Service Management and early support-tracking evidence for the Nexus Cloud Operations Lab.

Jira Service Management became the official service desk platform from Day 14 onward.

Azure DevOps Boards was used during the early foundation phase for support-style tracking.

## Important Ticketing Notes

- Nexus Retail Group is fictional.
- This is a portfolio lab, not a production environment.
- Jira issue numbers were automatically assigned by Jira.
- Manual ticket numbers such as NMSD-001 were not used in the final Jira setup.
- The Jira project key used in screenshots was NCOSD.
- Screenshots should be blurred before public upload if they show email addresses, public IPs, account details, or personal information.

---

## Day 8 — Azure DevOps Support Ticket Tracking

Platform:
Azure DevOps Boards

Purpose:
Used during the early foundation stage to track support-style work items before Jira Service Management became the official service desk platform.

Ticket areas included:

| Ticket Area | Purpose | Status |
|---|---|---|
| Finance storage access request | Track Finance access to secure storage | Completed |
| Ex-employee account review | Track disabled user/offboarding review | Completed |
| Sales access validation | Confirm Sales user should not access Finance storage | Completed |
| Finance RBAC verification | Confirm Finance group role assignment | Completed |
| RBAC evidence documentation | Document access testing evidence | Completed |

Evidence:
- day08-azure-devops-board.png
- day08-support-work-items-created.png
- day08-ticket-columns.png
- day08-ticket-detail-example.png

---

## Day 9 — Finance Access Ticket Resolution

Platform:
Azure DevOps Boards

Ticket Summary:
Finance user needs access to Finance storage.

Work Completed:
- Reviewed Finance access request
- Confirmed Nexus-GRP-Finance membership
- Confirmed Storage Blob Data Reader role assignment
- Confirmed finance-docs private container access model
- Documented ticket resolution

Evidence:
- day09-finance-ticket-open.png
- day09-finance-rbac-confirmation.png
- day09-finance-ticket-resolution-note.png
- day09-finance-ticket-resolved.png

Status:
Completed

---

## Day 10 — Sales Access Validation

Platform:
Azure DevOps Boards

Ticket Summary:
Sales user should not have access to Finance storage.

Work Completed:
- Reviewed Sales user access
- Confirmed Finance storage access was restricted to Nexus-GRP-Finance
- Validated least privilege access
- Documented resolution notes

Evidence:
- day10-sales-user-review.png
- day10-sales-no-finance-access.png
- day10-sales-ticket-resolution-note.png
- day10-sales-validation-summary.png

Status:
Completed

---

## Day 14 — Jira Service Management Setup

Platform:
Jira Service Management

Service Desk:
Nexus Cloud Operations Service Desk

Jira Project Key:
NCOSD

Purpose:
Set up Jira Service Management as the official MSP-style service desk platform for the Nexus Cloud Operations Lab.

Initial Jira tickets created:

| Jira Issue Key | Ticket Summary | Purpose | Status |
|---|---|---|---|
| NCOSD-1 | Finance user needs access to Azure storage | Access request tracking | Completed |
| NCOSD-2 | Ex-employee account still active | Offboarding / identity incident | Completed |
| NCOSD-3 | Sales user should not access Finance storage | Access control validation | Completed |
| NCOSD-5 | Document RBAC testing evidence | Documentation task | Completed |
| NCOSD-7 | Verify Finance group RBAC assignment | IAM / RBAC review | Completed |

Evidence:
- day14-jira-ticketing-board.png
- day14-service-project-created.png
- day14-jira-ticket-statuses.png

Status:
Completed

---

## Day 15 — Jira SLA and MSP Support Structure

Platform:
Jira Service Management

Purpose:
Document SLA thinking, escalation workflow, and MSP-style support structure.

Ticket / Documentation Areas:
- Priority mapping
- Ticket status review
- SLA mapping
- Escalation workflow
- MSP support process notes

Evidence:
- day15-jira-ticket-priority-view.png
- day15-jira-ticket-status-view.png
- day15-sla-mapping-notes.png
- day15-escalation-workflow-notes.png

Status:
Completed

---

## Day 16 — Active Directory Domain Controller Ticket

Platform:
Jira Service Management

Ticket Summary:
Build Active Directory domain controller for Nexus lab.

Work Completed:
- Created Windows Server VM in Azure
- Configured static private IP
- Installed Active Directory Domain Services
- Promoted server to domain controller
- Created nexus.local domain
- Verified Active Directory Users and Computers

Evidence:
- day16-jira-ad-domain-controller-ticket.png
- day16-active-directory-domain-created.png
- day16-domain-controller-installed.png

Status:
Completed

---

## Day 17 — Active Directory Users, Groups, OUs, and Offboarding Tickets

Platform:
Jira Service Management

Tickets Created:

| Ticket Summary | Purpose | Priority | Status |
|---|---|---|---|
| Create Active Directory OUs for Nexus departments | Document OU structure setup | Medium | Completed |
| Create Active Directory users and security groups | Document user/group creation | Medium | Completed |
| Disable ex-employee account in Active Directory | Document offboarding control | High | Completed |

Evidence:
- day17-jira-ad-ou-ticket.png
- day17-jira-ad-users-groups-ticket.png
- day17-jira-ad-offboarding-ticket.png

Status:
Completed

---

## Day 18 — Active Directory Helpdesk Support Tickets

Platform:
Jira Service Management

Tickets Created:

| Ticket Summary | Purpose | Priority | Status |
|---|---|---|---|
| User needs Active Directory password reset | Password reset support workflow | Medium | Completed |
| Verify Finance group access in Active Directory | Group membership/access review | Medium | Completed |
| Validate Sales user has no Finance group access | Least privilege validation | High | Completed |
| Review disabled ex-employee account in Active Directory | Offboarding review | High | Completed |

Evidence:
- day18-jira-ad-password-reset-ticket.png
- day18-jira-ad-finance-group-access-ticket.png
- day18-jira-ad-sales-no-finance-access-ticket.png
- day18-jira-ad-exemployee-review-ticket.png

Status:
Completed

---

## Day 19 — AD and Entra ID Identity Review

Platform:
No Jira ticket required for this day unless created separately.

Purpose:
Review and compare identity structure in Active Directory and Microsoft Entra ID.

Work Completed:
- Reviewed AD OU structure
- Reviewed AD users and groups
- Reviewed Entra ID users and groups
- Reviewed disabled user handling
- Captured identity review evidence

Evidence:
- day19-ad-ou-structure-review.png
- day19-ad-users-list-review.png
- day19-entra-users-list-review.png
- day19-entra-groups-list-review.png
- day19-entra-disabled-user-review.png

Status:
Completed

---

## Day 20 — File Server and Permissions Tickets

Platform:
Jira Service Management

Tickets Created:

| Ticket Summary | Purpose | Priority | Status |
|---|---|---|---|
| Create department file shares for Nexus users | Document department share creation | Medium | Completed |
| Configure Finance share permissions using AD group | Document Finance share access control | High | Completed |
| Validate Sales user has no Finance share access | Least privilege validation | High | Completed |

Evidence:
- day20-jira-department-file-shares-ticket.png
- day20-jira-finance-share-permissions-ticket.png
- day20-jira-sales-no-finance-share-access-ticket.png

Status:
Completed

---

## Day 21 — Backup Readiness Tickets

Platform:
Jira Service Management

Tickets Created:

| Ticket Summary | Purpose | Priority | Status |
|---|---|---|---|
| Configure Azure backup for NexusAD-01 | Document Azure Backup configuration | High | Completed |
| Review backup readiness for NexusAD-01 | Document backup pre-check/status review | Medium | Completed |

Evidence:
- day21-jira-azure-backup-configured-ticket.png
- day21-jira-backup-readiness-review-ticket.png

Status:
Completed

---

## Day 22 — Monitoring and Alerting Tickets

Platform:
Jira Service Management

Tickets Created:

| Ticket Summary | Purpose | Priority | Status |
|---|---|---|---|
| Configure monitoring for NexusAD-01 | Document Azure Monitor metrics review | Medium | Completed |
| Create high CPU alert for NexusAD-01 | Document alert rule setup | High | Completed |
| Register Microsoft.Insights provider for Azure Monitor | Document troubleshooting of blocked monitor setup | Medium | Completed |

Evidence:
- day22-jira-vm-monitoring-review-ticket.png
- day22-jira-high-cpu-alert-ticket.png
- day22-jira-microsoft-insights-provider-ticket.png

Status:
Completed

---

## Day 23 — Intune Access Review Ticket

Platform:
Jira Service Management

Ticket Summary:
Review Intune access for endpoint management.

Work Completed:
- Opened Microsoft Intune admin center
- Reviewed access to Intune tenant/admin area
- Identified 401 / No Permission issue
- Documented that Intune/MDM was not completed
- Continued endpoint management through Active Directory Group Policy

Evidence:
- day23-jira-intune-access-review-ticket.png
- day23-intune-admin-center-opened.png
- day23-intune-access-blocked.png

Status:
Completed

---

## Day 24 — Group Policy Endpoint Management Tickets

Platform:
Jira Service Management

Tickets Created:

| Ticket Summary | Purpose | Priority | Status |
|---|---|---|---|
| Configure endpoint user policy through Group Policy | Document GPO endpoint restriction setup | High | Completed |
| Configure department mapped drives through Group Policy | Document mapped drive policy setup | High | Completed |
| Configure domain password and account lockout policies | Document domain security policy setup | High | Completed |

Evidence:
- day24-jira-endpoint-user-policy-ticket.png
- day24-jira-department-mapped-drives-ticket.png
- day24-jira-domain-security-policy-ticket.png

Status:
Completed

---

## Ticketing Skills Demonstrated

- Jira Service Management ticket creation
- Support request documentation
- Incident documentation
- Access request handling
- Offboarding ticket documentation
- Password reset workflow documentation
- Backup readiness documentation
- Monitoring and alert documentation
- Troubleshooting documentation
- Resolution note writing
- Priority awareness
- MSP-style service desk workflow
