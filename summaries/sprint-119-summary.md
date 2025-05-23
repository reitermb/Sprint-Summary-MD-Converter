---
description: February 12, 2025 - February 25, 2025
---

# Sprint 119 Summary

## Summary

### Highlights

During this sprint, the team focused on enhancing backend functionality and user experience of our application. Key highlights included:

* Improved Developer Tooling:
  * Streamlined and simplified the reparse logic by creating a shared utility function.
* FRA Reporting Requirements MVP:
  * Enabled more modular and maintainable code, ensuring seamless integration between TANF/SSP and FRA data types.
* Operations &. Maintenance:
  * Ensured a smoother, more reliable user experience on the Data Files page.
* OFA Regional Staff UI MVP:
  * Provided a solid foundation for the MVP by defining clear user stories and prioritizing essential features for regional staff.
* Regional Staff Access to TDP:
  * Enhanced user access control by ensuring regional users can only interact with relevant data.

## Roadmap Progress&#x20;

{% hint style="info" %}
For more detailed information on task progress, please visit the [overall roadmap](https://sharing.clickup.com/9011887661/g/h/8cjczhd-111/1f2d90e8fb20c62) for these epics.
{% endhint %}

* FRA Reporting Requirements MVP | <mark style="color:green;">**ON TRACK**</mark> | Progress: 46% | Estimated Completion Date: May 15, 2025
  * <mark style="color:purple;">**Note:**</mark> Prioritization of #3398 should take precedence. Review can be couple with #3407, since they collectively create the proposed FRA interface.
  * <mark style="color:purple;">**Note:**</mark>  We are currently planning to send out the email to STTs for early access testing recruitment on 2/28. I am planning to coordinate details on this as part of Prod Sync on 2/28.&#x20;
* Regional Staff Access to TDP | <mark style="color:green;">**ON TRACK**</mark> | Progress: 20% | Estimated Completion Date: May 6, 2025
  * <mark style="color:purple;">**Note:**</mark>  We would like to request QASP review on #3385 as soon as possible to ensure we can remain on track here.
* OFA Regional Staff UI MVP | <mark style="color:green;">**ON TRACK**</mark> | Progress: 8% | Estimated Completion Date: October 21, 2025
  * <mark style="color:purple;">**Note:**</mark> Research planning has been brought in to occur in conjunction with design ideation. We are targeting to share our first round of design ideation in this upcoming sprint.
* Application Health Monitoring | <mark style="color:yellow;">**AT RISK**</mark> | Progress: 45% | Estimated Completion Date: July 15, 2025
  * <mark style="color:yellow;">**Potential Risk:**</mark> Decommissioning Kibana/ElasticSearch ([#3363](https://app.zenhub.com/workspaces/laurens-product-board-6744a37f854a2c00246c2ed8/issues/gh/raft-tech/tanf-app/3363)) is currently blocked by the merging of [#3463](https://app.zenhub.com/workspaces/laurens-product-board-6744a37f854a2c00246c2ed8/issues/gh/raft-tech/tanf-app/3463). Merging [#3463](https://app.zenhub.com/workspaces/laurens-product-board-6744a37f854a2c00246c2ed8/issues/gh/raft-tech/tanf-app/3463) into production will unblock QASP review from occurring for [#3363](https://app.zenhub.com/workspaces/laurens-product-board-6744a37f854a2c00246c2ed8/issues/gh/raft-tech/tanf-app/3363).&#x20;
  * <mark style="color:yellow;">**Potential Risk:**</mark> Integrating Prometheus with Mimir ([#3244](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3244)) will be delayed further due to unexpected changes in staffing. We are planning to have our new team member pick this up once he is properly onboarded.

## Tasks

### Improved Developer Tooling

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3205">#3205</a> - Reparse command refactor</td><td>Streamlined and simplified the reparse logic by creating a shared utility function, improving maintainability and enabling more customizable parsing behavior for both the admin and management commands.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr></tbody></table>

### FRA Reporting Requirements MVP

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3426">#3426</a> - [Tech Memo] Improvements to RowSchema and Field classes for FRA</td><td>Enabled more modular and maintainable code, ensuring seamless integration between TANF/SSP and FRA data types.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3398">#3398</a> - Implement FRA report selection and upload interface</td><td>Enables users to select and upload new FRA report types for a given fiscal quarter, streamlining the data entry process and ensuring accurate reporting for the "Work Outcomes for TANF Exiters" section.</td><td><mark style="color:blue;"><strong>QASP REVIEW</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3407">#3407</a> - Implement FRA submission history interface</td><td>Enhances the user experience by allowing users to easily view and track the history of their FRA report submissions, improving transparency and usability.</td><td><mark style="color:blue;"><strong>QASP REVIEW</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3411">#3411 </a>- [Design Deliverable] Finalize KC content for FRA Report #1</td><td>Ensures users have clear, accurate, and consistent guidance on submission workflows and error reporting, promoting smoother interactions with the platform.</td><td><mark style="color:blue;"><strong>QASP REVIEW</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3463">#3463</a> - Refactor parsing engine to class-based design</td><td>Improves code maintainability, scalability, and readability while ensuring existing functionality remains intact and fully tested.</td><td><mark style="color:blue;"><strong>QASP REVIEW</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3473">#3473</a> - Refactor RowSchema and Field classes to use RawRow and Position</td><td>Enhances the parsing engine’s abstraction, improving code clarity, modularity, and maintainability while ensuring seamless validation and data handling.</td><td><mark style="color:purple;"><strong>RAFT REVIEW</strong></mark></td></tr></tbody></table>

### Application Health Monitoring

**Note:** [#3244](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3244) will be delayed further due to unexpected changes in staffing. We are planning to have our new team member pick this up once he is properly onboarded.

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3244">#3244</a> - Integrate Prometheus with Mimir to enable data persistence on cloud.gov</td><td>Ensures the persistence of time series data on cloud.gov, addressing the issue of data loss due to regular restaging by enabling reliable storage and retrieval of metrics on S3.</td><td><mark style="color:red;"><strong>DELAYED</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3294">#3294</a> - Implement log file generation and S3 upload for parser runs</td><td>Enhances traceability, security, and debugging by ensuring that each datafile submission generates a dedicated log file, reducing the risk of sensitive data leakage and improving error diagnosis through structured log storage in S3.</td><td><mark style="color:purple;"><strong>RAFT REVIEW</strong></mark></td></tr></tbody></table>

### Operations & Maintenance

**Note:** [#3363](https://app.zenhub.com/workspaces/laurens-product-board-6744a37f854a2c00246c2ed8/issues/gh/raft-tech/tanf-app/3363) is currently blocked by the merging of [#3463](https://app.zenhub.com/workspaces/laurens-product-board-6744a37f854a2c00246c2ed8/issues/gh/raft-tech/tanf-app/3463). Merging [#3463](https://app.zenhub.com/workspaces/laurens-product-board-6744a37f854a2c00246c2ed8/issues/gh/raft-tech/tanf-app/3463) into production will unblock QASP review from occurring for [#3363](https://app.zenhub.com/workspaces/laurens-product-board-6744a37f854a2c00246c2ed8/issues/gh/raft-tech/tanf-app/3363).&#x20;

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3413">#3413</a> - Fix file upload collapse and null file handling</td><td>Ensured a smoother, more reliable user experience on the Data Files page, preventing errors and improving usability.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3363">#3363</a> - Decommission Kibana &#x26; ElasticSearch</td><td>Streamlines our infrastructure by removing unused Kibana and Elasticsearch services, reducing technical debt and simplifying system maintenance.</td><td><mark style="color:red;"><strong>BLOCKED</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3491">#3491</a> - Add banner to KC denoting loss of email notification functionality</td><td>Ensures users are promptly informed of the temporary email outage through an accessible and well-integrated banner, minimizing confusion and maintaining transparency while a resolution is pursued.</td><td><mark style="color:blue;"><strong>QASP REVIEW</strong></mark></td></tr></tbody></table>

### OFA Regional Staff UI MVP

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3427">#3427</a> - Gather requirements and feature prioritization for minimum viable regional staff user interface</td><td>Provided a solid foundation for the MVP by defining clear user stories and prioritizing essential features for regional staff, ensuring that the design and development align with their workflows and the specific needs of submission tracking and issue resolution.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3262">#3262</a> - [Design Ideation] Regional Staff UI MVP</td><td>Ensures a well-researched, user-centered design foundation for the regional staff MVP, resulting in an intuitive interface that aligns with their workflows and meets key functional requirements.</td><td><mark style="color:yellow;"><strong>IN PROGRESS &#x26; MOVED TO NEXT SPRINT</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3408">#3408</a> - [Research Planning] OFA Regional Staff UI MVP</td><td>Establishes a structured research plan for the OFA Regional Staff UI MVP, ensuring a clear methodology for gathering user insights, refining designs, and aligning the interface with regional staff needs.</td><td><mark style="color:yellow;"><strong>IN PROGRESS &#x26; MOVED TO NEXT SPRINT</strong></mark></td></tr></tbody></table>

### Regional Staff Access to TDP

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3384">#3384</a> - Update the existing OFA access workflow to include regions</td><td>Enhanced user access control by ensuring regional users can only interact with relevant data, improving security, communication, and transparency through region-specific permissions and email notifications.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3385">#3385</a> - Update Data Files page for regional staff</td><td>Ensures that regional staff have appropriate, limited access to TDP, enabling them to view submission history for their assigned STTs while preventing unauthorized data uploads or downloads, thereby enhancing security and role-based access control.</td><td><mark style="color:purple;"><strong>RAFT REVIEW</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3461">#3461 </a>- Create and facilitate Project Updates meeting for regional staff</td><td>Ensures regional staff are well-informed about their new TDP access, providing them with a clear understanding of key functionalities, a live demonstration, and an opportunity for Q&#x26;A, ultimately supporting a smooth onboarding process.</td><td><mark style="color:yellow;"><strong>IN PROGRESS &#x26; MOVED TO NEXT SPRINT</strong></mark></td></tr></tbody></table>

