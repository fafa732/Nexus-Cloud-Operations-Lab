# Day 20 — File Server and Permissions

## Purpose

This folder documents the Windows file server and permissions work completed in the Nexus Cloud Operations Lab.

The goal was to practise creating department file shares and controlling access using Active Directory security groups.

## Scenario

Nexus Retail Group needed shared folders for different departments.

Each department required access to its own share, while users from other departments should not have unnecessary access.

## Work Completed

- Created department share folders
- Created Finance, HR, Sales, and Warehouse shares
- Configured share permissions
- Configured NTFS permissions
- Assigned access using Active Directory security groups
- Validated that Sales did not have Finance share access
- Documented file server support tasks in Jira Service Management

## Department Shares

```text
Finance-Share
HR-Share
Sales-Share
Warehouse-Share
