# Day 17 — Active Directory Users, Groups, and OUs

## Purpose

This folder documents the Active Directory organisational structure created for the Nexus Cloud Operations Lab.

The goal was to practise creating OUs, users, security groups, group membership, and disabled user handling in Active Directory.

## Scenario

Nexus Retail Group needed a structured Active Directory environment with department-based OUs and groups.

This structure allowed user accounts to be organised clearly and prepared the environment for helpdesk tasks, file permissions, and Group Policy.

## Work Completed

- Opened Active Directory Users and Computers
- Created the main Nexus Retail Group OU
- Created department OUs
- Created Active Directory security groups
- Created department user accounts
- Added users to the correct groups
- Disabled an ex-employee account
- Documented the work in Jira Service Management

## OU Structure

```text
Nexus Retail Group
├── IT
├── Finance
├── HR
├── Sales
├── Warehouse
├── Disabled Users
└── Service Accounts
