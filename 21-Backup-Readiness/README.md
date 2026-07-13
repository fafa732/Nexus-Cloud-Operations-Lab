# Day 21 — Backup Readiness

## Purpose

This folder documents the Azure Backup readiness work completed in the Nexus Cloud Operations Lab.

The goal was to practise protecting the NexusAD-01 server using Azure Backup and documenting backup readiness from an IT support and operations perspective.

## Scenario

Nexus Retail Group needed backup protection for its Active Directory server.

The support task was to create backup readiness evidence, enable protection, review backup status, and document the work in Jira Service Management.

## Work Completed

- Created a Recovery Services Vault
- Enabled backup protection for NexusAD-01
- Used an enhanced backup policy when required
- Reviewed backup status
- Reviewed backup pre-check information
- Documented backup readiness in Jira Service Management
- Stopped and deallocated the VM after the lab work

## Backup Resource

```text
Recovery Services Vault: nexus-rsv-ad-prod
Protected server: NexusAD-01
