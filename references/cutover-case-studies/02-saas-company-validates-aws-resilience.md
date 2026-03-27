# SaaS Company Validates AWS Resilience

**Source:** https://cutover.com/success-stories/saas-company-validates-aws-resilience

---

## Overview

A SaaS provider used Cutover to demonstrate annual multi-region AWS failover capabilities to a major investment bank client, satisfying stringent compliance requirements.

---

## Problem: Ensuring Resilient SaaS Operations for a Major Bank

A prominent American multinational investment bank required its SaaS provider to rigorously demonstrate the resilience of their AWS-hosted application. To satisfy stringent internal compliance policies, the bank mandated an annual multi-region failover exercise. This involved successfully failing over the SaaS application between AWS regions, specifically from us-east-1 to us-west-2 (or vice versa). The SaaS company needed to provide irrefutable evidence of the successful failover, including before-and-after screenshots and a follow-up confirmation of continued operation in the secondary region a week later.

---

## Solution: Leveraging Cutover for Automated Multi-Region Failover

To meet the bank's demanding resilience requirements, the SaaS company implemented Cutover, an automated runbook platform. Cutover facilitated a structured and auditable failover process from the primary AWS region (us-east-1) to the secondary region (us-west-2). The SaaS application was architected with active-active-active availability zones (AZs) and multi-region availability to support a seamless failover.

The Cutover runbook incorporated several key elements:

- **Failover Activities:** Clearly defined and automated steps for initiating and executing the regional failover.
- **Milestone Tasks:** Trackable progress points to ensure the failover proceeded according to plan.
- **Checklists for Evidence Gathering:** Integrated steps to capture necessary evidence, including screenshots of the application's status before and after the failover.
- **Acceptance Testing for Validation:** Automated and manual test scripts to verify the functionality, critical integrations, and API endpoints in the failover region.

---

## Outcome: Demonstrated Resilience and Compliance Adherence

The annual multi-region failover tests, orchestrated through Cutover, successfully demonstrated the SaaS application's resilience to the bank's compliance officers. The detailed runbooks provided clear and auditable evidence of the failover process, including the required screenshots and subsequent confirmation of stable operation in the us-west-2 region. The successful transition and the following year of uninterrupted operation in the new region proved the robustness and stability of the SaaS platform in a failover scenario.

---

## Key Results

- Annual multi-region AWS failover successfully executed
- Full compliance with bank's internal resilience policies
- Auditable evidence trail provided for compliance officers
- Demonstrated uninterrupted operation in secondary region
