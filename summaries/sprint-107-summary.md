# sprint-107-summary

8/28/2024 - 9/10/2024

### <mark style="color:orange;">Priority Setting</mark>

* Re-parsing epic &#x20;
  * Re: OFA's reports behind schedule because db incomplete&#x20;
* Postgres db access &#x20;
  * Re: after db re-populated, csv exports not functional&#x20;
  * Note: short-term workaround in-place, but will have limited value with incomplete db  &#x20;
* UX research with DIGIT team&#x20;
  * Re: provide clarity on OFA's data use  to help inform strategies and tools needed for the system to better support the DIGIT team's goals.&#x20;
* Continuous communication with STTs about latest TDP **features** and updates&#x20;
  * Re: release notes&#x20;

### <mark style="color:orange;">Sprint Goal</mark>

**Dev:**

_**Re-parsing, Admin Console Improvements, and Application Health Monitoring work**_

* \#3106 — Re-Parse Django Action&#x20;
* \#2965 — As tech lead, I want a database seed implemented for testing
* \#3137 — \[bug] OFA unable to export data to csv by record type and fiscal period
* \#3074 — TDP Data Files page permissions for DIGIT & Sys Admin user groups
* \#3042 — Sentry in cloud.gov
* \#2458 — Integrate Nexus into CircleCI

**DevOps:**

_**Successful deployments across environments and pipeline stability investments**_

* \#3044 — Prometheus/Grafana - Local Environment

**Design:**

_**Support reviews, In-app banner to support parsed data, Continue Error Audit (Cat 4)**_

* \#3156 — Release Notes Email Template
* \#3100 — \[Design Deliverable] Update stakeholders & personas document
* \#2968  — \[Design Deliverable] Update Error Audit for Cat 4 / QA

## Tickets

### Completed/Merged

* [#2561 As a sys admin, I need TDP to automatically deactivate accounts that are inactive for 180 days](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/2561)
* [#2792 \[Error Audit\] Category 3 error messages clean-up](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/2792)
* [#3043 Sentry: Local environment for Debugging](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3043)
* [#3064 Re-parse Meta Model](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3064)
* [#3065 Spike - Guarantee Sequential Execution of Re-parse Command](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3065)
* [#3074 TDP Data Files page permissions for DIGIT & Sys Admin user groups](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3074)
* [#3076 Admin Filter Enhancements for Data Files Page](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3076)
* [#3078 \[Research Synthesis\] DIGIT Admin Experience Improvements](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3078)
* [#3087 Admin By Newest Filter Enhancements for Data Files Page](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3087)
* [#3114 \[Design Spike\] In-app banner for submission history pages w/ data parsed before May 2024](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3114)
* [#3142 \[Research Spike\] Get more detail about Yun & DIGIT's data workflow and use cases](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3142)

### Submitted (QASP Review, OCIO Review)

*

### Ready to Merge

* [#2883 Pre-Made Reporting Dashboards on Kibana](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/2883)
* [#3102 Admin Exp: Django Implement Multi-Select Fiscal Period Dropdown For Data Export ](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3102)

### Closed (Not Merged)

* [#3110 Spike - Investigate Custom Filter Integration](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3110)
* [#3156 Release Notes Knowledge Center and Email Template](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3156)

### Moved to Next Sprint&#x20;

**In Progress**&#x20;

* [#2968 \[Design Deliverable\] Update Error Audit for Cat 4 / QA](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/2968)
* [#3060 As a TDP user, I need to stay logged in when I'm actively using the system](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3060)
* [#3100 \[Design Deliverable\] Update stakeholders & personas document](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3100)
* [#3106 Re-Parse Django Action ](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3106)
* [#3137 \[bug\] OFA unable to export data to csv by record type and fiscal period](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3137)
* [#3164 \[Research Synthesis\] Yun & DIGIT's data workflow and use cases](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3164)
* [#3170 Reparse Command Fails when Queryset is Large](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3170)
* [#3179 Spike - How We Work / Hopes & Fears Workshop prep](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3179)

**Blocked**

*

**Raft Review**

* [#2458 Integrate Nexus into CircleCI](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/2458)
* [#2965 As tech lead, I want a database seed implemented for testing](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/2965)
* [#3044 Prometheus/Grafana - Local Environment](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3044)
