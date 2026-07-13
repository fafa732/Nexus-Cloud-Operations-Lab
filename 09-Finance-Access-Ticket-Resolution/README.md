# Day 9 — Finance Access Ticket Resolution

## Purpose

This folder documents the Finance access ticket resolution for the Nexus Cloud Operations Lab.

The goal was to show how an access request is reviewed, validated, documented, and resolved using support-ticket workflow.

## Scenario

A Finance user needed access to the secure Finance storage area.

The support task was to confirm that access was controlled through the correct Finance group and RBAC assignment, rather than granting unnecessary direct access.

## Work Completed

- Reviewed the Finance access request
- Confirmed the Finance group was the correct access path
- Reviewed RBAC access for Finance storage
- Confirmed Finance storage access was restricted
- Documented the resolution in the ticketing system
- Captured evidence for access control and ticket closure

## Access Control Logic

```text
Finance user → Finance group → RBAC role → Finance storage access
