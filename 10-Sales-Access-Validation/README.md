# Day 10 — Sales Access Validation

## Purpose

This folder documents the Sales access validation work completed in the Nexus Cloud Operations Lab.

The goal was to confirm least privilege access by validating that a Sales user did not have access to Finance storage resources.

## Scenario

Nexus Retail Group needed to make sure that department access was properly restricted.

Finance users should have access to Finance storage, but Sales users should not be able to access Finance resources.

## Work Completed

- Reviewed the Sales user access path
- Confirmed the Sales user was not part of the Finance group
- Reviewed Finance storage access control
- Validated that Finance storage was restricted
- Documented the access validation result
- Captured ticket evidence for least privilege testing

## Access Control Logic

```text
Sales user → No Finance group membership → No Finance storage access
