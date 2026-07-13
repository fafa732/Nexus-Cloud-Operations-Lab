# Day 16 — Active Directory Build

## Purpose

This folder documents the Active Directory build for the Nexus Cloud Operations Lab.

The goal was to build a Windows Server VM in Azure and configure it as a domain controller for a traditional Active Directory environment.

## Scenario

Nexus Retail Group needed an on-prem-style identity environment to support users, groups, OUs, file permissions, password resets, and Group Policy.

A Windows Server VM was deployed in Azure and promoted to a domain controller for the nexus.local domain.

## Work Completed

- Created a Windows Server VM in Azure
- Configured the VM for Active Directory use
- Set the private IP address to static
- Installed Active Directory Domain Services
- Promoted the server to a domain controller
- Created the nexus.local domain
- Verified Active Directory Users and Computers
- Documented the work in Jira Service Management
- Stopped and deallocated the VM after the lab work

## Domain Details

```text
Domain: nexus.local
NetBIOS name: NEXUS
Domain controller: NexusAD-01
