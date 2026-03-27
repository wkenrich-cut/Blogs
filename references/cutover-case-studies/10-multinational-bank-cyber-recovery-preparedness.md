# Multinational Bank Uses Cutover to Mature Cyber Recovery Preparedness

**Source:** https://cutover.com/success-stories/multinational-bank-uses-cutover-to-mature-cyber-recovery-preparedness

---

## Overview

A multinational bank built out a comprehensive cyber recovery capability using Cutover runbooks, separating application recovery from data integrity recovery to address the unique challenges of recovering from a cyber attack.

---

## The Problem: The Need for Robust Cyber Recovery

A multinational bank needed a better way of practicing and demonstrating its capability to recover from a pervasive cyber attack. While the regulator recognized that they had great preventative measures in place, they needed to prove that they could recover quickly and effectively if an attacker penetrated those defenses.

The bank's existing IT disaster recovery strategies were not sufficient for this task as these mainly revolved around assuming all existing data is good and failing it over from one set of infrastructure to another. In the case of a cyber attack, they would instead need to determine the last known good backup that is not infected and recover their applications from a bare metal state and repopulate with trusted data.

---

## The Solution: Building Cyber Recovery Runbooks

The recovery team took an approach of separating the application recovery from the data integrity recovery. It built out its platform and application recovery plans for responding to cyber incidents using Cutover runbooks, outlining their bare metal recovery plans initially focused on the most important tier 0 and 1 business services.

Creating these bare metal recovery plans using Cutover's automated runbooks enabled the team to capture the complex dependencies between manual and automated tasks to ensure that the recovery would run smoothly.

The next step was to build out hundreds of recovery plans associated with data integrity to repopulate the data related to their most critical services once the application is rebuilt from a bare metal state. This was done using approved templated recovery plans in Cutover for consistency and governance.

The application and data integrity plans can be combined to manage the entire cyber recovery process. Cutover provided a single repository view across all cyber recovery plans and gave the bank more confidence in its ability to recover.

### Cutover Features for Cyber Recovery

- Managed repository of recovery runbooks to enable rapid mobilization spanning hundreds of applications
- Automated runbooks using linked runbooks functionality — parent runbook managing the recovery as a whole with child runbooks for each individual application
- Real-time reporting and analytics for efficient control, visibility, and stakeholder engagement at scale
- API and integrations to automate repetitive tasks by linking runbooks to the recovery technology stack (e.g., CMDB)
- Post-execution analytics to drive continuous improvement
- Audit trail and auto-generated compliance logs for regulatory reporting

---

## The Outcome: Continuing the Cyber Recovery Maturity Journey

The bank foresees several outcomes from this continuing cyber recovery maturity journey:

- Faster recovery with reduced risk
- Removing regulatory burden by demonstrating a full suite cyber recovery plan to regulators
- Having a recovery capability that would enable them to reasonably set a Recovery Time Objective (RTO)

---

## Key Results

- Tier 0 and 1 application bare metal recovery plans established
- Hundreds of data integrity recovery plans built
- Full coverage of the cyber recovery process via combined runbooks
- Regulatory compliance demonstrated through Cutover's audit trails
- Clear path to setting measurable Recovery Time Objectives (RTOs)
