---
description: 8/14/202 - 8/27/2024
---

# sprint-106-summary

### <mark style="color:orange;">Priority Setting</mark>

* Reparsing &#x20;
  * Reasoning: OFA has ability to reparse and the data process with latest system logic which will enable STTs to get error reports that are meaningful and relevant and OFA gets the needed data. System, as a whole, will be more flexible with data flow (able to hot fix and hit reparse).  Additionally, we want to avoid missing data and be able to repopulate the database after cleaning the data. &#x20;
* Data Access Strategy&#x20;
  * Reasoning: Creating daily blockers &#x20;
* Admin Console Improvements&#x20;
  * Reasoning: Trigger has been met to refine tickets (Research Synthesis)
* Improved Dev Tooling&#x20;
  * improve test\_parse.py 2641&#x20;
  * separate celery 2592&#x20;
  * Reasoning: Developing / refining tickets to support the above priorities – These tickets will enhance capabilities while the above are being flushed out &#x20;

### <mark style="color:orange;">Sprint Goal</mark>

**Dev:**

_**Reparsing, Admin Console Improvements, Application Health Monitoring work, and Improved Dev Tooling**_

* \#2965 — As tech lead, I want a database seed implemented for testing
* \#3102  — Admin Exp: Django Implement Multi-Select Fiscal Period Dropdown For Data Export&#x20;
* \#2561 — As a sys admin, I need TDP to automatically deactivate accounts that are inactive for 180 days
* \#3110 — Spike - Investigate Custom Filter Integration
* \#3137 — \[bug] OFA unable to export data to csv by record type and fiscal period
* \#3074 — TDP Data Files page permissions for DIGIT & Sys Admin user groups
* \#3076  — Admin Filter Enhancements for Data Files Page&#x20;

**DevOps:**

_**Successful deployments across environments and pipeline stability investments**_

*

**Design:**

_**Support reviews, In-app banner to support parsed data, Continue Error Audit (Cat 4)**_

* \#2968  — \[Design Deliverable] Update Error Audit for Cat 4 / QA
* \#3114 — \[Design Spike] In-app banner for submission history pages w/ data parsed before May 2024
* \#3143 — August release notes — Knowledge Center & Email Template
