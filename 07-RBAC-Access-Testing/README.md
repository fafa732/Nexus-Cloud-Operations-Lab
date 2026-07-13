# Day 7 — RBAC Access Testing

## Purpose

This folder documents the RBAC access testing phase of the Nexus Cloud Operations Lab.

The goal was to validate that Azure Storage access followed least privilege principles.

## Scenario

Nexus Retail Group needed to confirm that Finance users could access the Finance storage container, while Sales users could not access Finance resources.

## Work Completed

- Reviewed Finance storage access
- Tested Finance user access path
- Reviewed Sales user access limitations
- Confirmed Sales users were not granted Finance storage access
- Documented the access testing results
- Prepared evidence for later ticket resolution work

## Access Testing Logic

The access model tested was:

```text
Finance user → Finance group → RBAC role → Finance storage access
Sales user → No Finance group membership → No Finance storage access
