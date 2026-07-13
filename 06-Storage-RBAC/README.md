# Day 6 — Storage RBAC

## Purpose

This folder documents the Azure Storage RBAC configuration for the Nexus Cloud Operations Lab.

The goal was to practise securing storage access using group-based permissions and Azure role assignments.

## Scenario

Nexus Retail Group needed a secure Finance storage area where Finance users could access documents, while non-Finance users were excluded.

## Work Completed

- Created or reviewed the Azure Storage account
- Created the private Finance storage container
- Confirmed the container was not publicly accessible
- Assigned RBAC access to the Finance group
- Used group-based access instead of direct user access
- Prepared the environment for access testing

## Access Control Model

Finance storage access was controlled through:

```text
Finance users → Finance group → Azure RBAC role → Finance storage container
