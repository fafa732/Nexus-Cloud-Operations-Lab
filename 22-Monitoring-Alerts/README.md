# Day 22 — Monitoring and Alerts

## Purpose

This folder documents the Azure monitoring and alerting work completed in the Nexus Cloud Operations Lab.

The goal was to practise reviewing VM metrics, troubleshooting Azure Monitor setup issues, creating an action group, and configuring an alert rule.

## Scenario

Nexus Retail Group needed basic monitoring for the NexusAD-01 server.

The support task was to review VM performance metrics, configure alerting, and document the monitoring setup in Jira Service Management.

## Work Completed

- Reviewed NexusAD-01 CPU metrics
- Reviewed NexusAD-01 availability metrics
- Identified that Microsoft.Insights provider registration was required
- Registered the Microsoft.Insights resource provider
- Created an Azure Monitor action group
- Created a high CPU alert rule
- Linked the alert rule to the action group
- Documented monitoring and alerting tasks in Jira Service Management
- Stopped and deallocated the VM after the lab work

## Monitoring Resources

```text
Monitored server: NexusAD-01
Action group: nexus-ad-monitoring-ag
Alert type: High CPU alert
Condition: Percentage CPU greater than 80%
