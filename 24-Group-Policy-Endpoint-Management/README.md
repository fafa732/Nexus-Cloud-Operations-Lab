# Day 24 — Group Policy Endpoint Management

## Purpose

This folder documents the Group Policy endpoint management work completed in the Nexus Cloud Operations Lab.

The goal was to use Active Directory Group Policy as the hands-on endpoint management fallback after Microsoft Intune access was blocked.

## Scenario

Nexus Retail Group needed endpoint policies for users and departments.

Because Intune/MDM configuration was blocked by a 401 / No Permission issue, endpoint management continued through Active Directory Group Policy.

## Work Completed

- Opened Group Policy Management
- Created an endpoint user policy GPO
- Linked the GPO to the Nexus Retail Group OU
- Configured Control Panel restriction
- Configured mapped drives for department shares
- Configured Finance mapped drive
- Configured HR mapped drive
- Configured Sales mapped drive
- Configured Warehouse mapped drive
- Configured domain password policy
- Configured account lockout policy
- Configured logon banner policy
- Documented endpoint management tasks in Jira Service Management
- Stopped and deallocated the VM after the lab work

## Group Policy Areas Configured

```text
User endpoint restriction
Department mapped drives
Password policy
Account lockout policy
Logon banner policy
