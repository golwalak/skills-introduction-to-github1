# IT Enterprise Hardware Asset Support Models

## Overview

This document defines the support models for enterprise hardware assets across the organization. It covers asset categories, support tiers, service-level agreements (SLAs), lifecycle management, and escalation procedures to ensure reliable operation of all IT hardware infrastructure.

---

## Hardware Asset Categories

| Category | Examples | Typical Lifecycle |
|---|---|---|
| **Servers** | Rack servers, blade servers, tower servers | 5–7 years |
| **Workstations & Desktops** | Desktop PCs, engineering workstations | 4–5 years |
| **Laptops & Mobile Devices** | Laptops, tablets, ruggedized devices | 3–4 years |
| **Networking Equipment** | Switches, routers, firewalls, access points | 5–7 years |
| **Storage Systems** | SAN, NAS, backup appliances | 5–7 years |
| **Peripherals** | Monitors, printers, scanners, docking stations | 3–5 years |
| **Data Center Infrastructure** | UPS, PDUs, environmental monitors | 7–10 years |

---

## Support Model Tiers

### Tier 1 — Warranty Support

- **Coverage:** Manufacturer warranty only
- **Response Time:** Next business day (NBD)
- **Availability:** Business hours (8×5)
- **Scope:** Hardware defect replacement; no on-site labor included
- **Best For:** Non-critical peripherals, test/dev equipment

### Tier 2 — Standard Support

- **Coverage:** Extended warranty + internal IT helpdesk
- **Response Time:** 8 business hours
- **Availability:** Business hours (8×5)
- **Scope:** Break/fix, parts replacement, basic troubleshooting
- **Best For:** General office workstations, standard laptops

### Tier 3 — Premium Support

- **Coverage:** Vendor support contract + dedicated internal support team
- **Response Time:** 4 hours
- **Availability:** Extended hours (16×7)
- **Scope:** On-site repair, proactive monitoring, firmware/driver updates
- **Best For:** Business-critical servers, core networking equipment

### Tier 4 — Mission-Critical Support

- **Coverage:** Vendor premium/critical support + 24/7 internal NOC
- **Response Time:** 1 hour (with 4-hour hardware replacement)
- **Availability:** Around the clock (24×7×365)
- **Scope:** Immediate on-site response, hot spares, redundant configurations, proactive health checks
- **Best For:** Production database servers, core switches/routers, SAN/storage arrays

---

## Service-Level Agreements (SLAs)

| Support Tier | Response Time | Resolution Target | Uptime Target |
|---|---|---|---|
| Tier 1 — Warranty | Next business day | 5 business days | N/A |
| Tier 2 — Standard | 8 business hours | 3 business days | 99.0% |
| Tier 3 — Premium | 4 hours | 8 hours | 99.9% |
| Tier 4 — Mission-Critical | 1 hour | 4 hours | 99.99% |

---

## Asset Lifecycle Management

### 1. Procurement

- Hardware purchases aligned with approved vendor list
- Support tier assigned at time of procurement based on asset role
- Asset tagged and entered into the Configuration Management Database (CMDB)

### 2. Deployment

- Standard image/configuration applied per asset category
- Warranty and support contract details recorded
- Assigned to owner and location in asset management system

### 3. Operations & Maintenance

- Scheduled preventive maintenance per support tier
- Firmware and driver updates following change management process
- Continuous monitoring for Tier 3 and Tier 4 assets

### 4. End of Life (EOL) & Decommission

- Assets reviewed at 75% of expected lifecycle
- Replacement planning triggered 6 months before EOL
- Secure data destruction and environmentally responsible disposal
- Asset record updated and closed in CMDB

---

## Escalation Procedures

| Level | Responsibility | Timeframe |
|---|---|---|
| **L1 — IT Helpdesk** | Initial triage, ticket creation, basic troubleshooting | 0–30 minutes |
| **L2 — Desktop/Server Support** | Hands-on diagnosis, parts swap, vendor coordination | 30 min – 4 hours |
| **L3 — Infrastructure Engineering** | Advanced troubleshooting, architecture-level resolution | 4–8 hours |
| **L4 — Vendor/Manufacturer** | Escalation to OEM for warranty or contract-covered repairs | As needed |
| **Management Escalation** | Notification to IT management for SLA breaches or critical impact | Per SLA thresholds |

---

## Roles and Responsibilities

| Role | Responsibilities |
|---|---|
| **Asset Manager** | Maintain CMDB, track lifecycle, coordinate procurement and disposal |
| **IT Helpdesk** | First point of contact, ticket management, L1 support |
| **Field Technicians** | On-site hardware repair and replacement |
| **Infrastructure Engineers** | Server/network/storage administration and advanced troubleshooting |
| **Vendor Management** | Negotiate and manage support contracts, coordinate vendor escalations |
| **IT Management** | Approve budgets, review SLA performance, strategic planning |

---

## Vendor Support Contracts

Maintain active support contracts with approved hardware vendors. Contracts should specify:

- Coverage scope (parts, labor, on-site)
- Response and resolution commitments
- Escalation contacts and procedures
- Contract renewal dates and terms
- Entitlement verification process

---

## Reporting and Metrics

Track and report on the following key performance indicators (KPIs):

- **Mean Time to Acknowledge (MTTA):** Average time from ticket creation to first response
- **Mean Time to Resolve (MTTR):** Average time from ticket creation to resolution
- **SLA Compliance Rate:** Percentage of incidents resolved within SLA targets
- **Asset Uptime:** Measured availability against uptime targets per tier
- **Repeat Incident Rate:** Frequency of recurring issues per asset
- **Cost per Incident:** Average support cost per hardware incident

---

## Document Control

| Field | Value |
|---|---|
| **Version** | 1.0 |
| **Last Updated** | 2026-03-23 |
| **Owner** | IT Asset Management |
| **Review Cycle** | Annual |
