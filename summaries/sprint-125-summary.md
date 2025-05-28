---
description: 5/7/2025 - 5/20/2025
---

# Sprint 125 Summary

## Summary

### Deliverables

In the past sprint, we completed the following deliverables:

* 🎉 **FRA Reporting is Live!**\
  This milestone delivers a complete, end-to-end submission workflow for FRA data—including new validation logic, downloadable error reports, updated permissions, and Knowledge Center content tailored to States, Tribes, and Territories (STTs). Built in close collaboration with OFA, this release reflects months of research, testing, and iteration to ensure accessibility, usability, and alignment with evolving reporting needs. Huge thanks to all partners who made this possible!

### Other Highlights

During this sprint, the team focused on enhancing our application health monitoring stack, conducting research for the fTANF replacement, and ensuring data security. Other highlights included:

**Application Health Monitoring:**

* Improved transparency and traceability, giving OFA users direct access to debugging details.
* Ensured the TDP platform stayed on a secure, actively maintained logging stack as Promtail approaches deprecation.

**Continuous User Feedback & Research Loops:**

* Developed designs that enable lightweight, compliant in-app prompts that gather contextual user feedback.

**Enabling Secure Data Access for DIGIT via Grafana:**

* Set up views to enable safe, efficient access for Grafana and automation workflows without exposing sensitive information.
* Explored structure for onboarding DIGIT to Grafana.
* Created RDS user to enable secure data exploration and dashboarding while safeguarding production data from accidental changes.

**FRA Post-MVP Enhancements:**

* Extended parsing log file support to ensure consistent traceability.

**fTANF Replacement - Foundational Research & Concept Validation:**

* Built use case tracker to enable the team to design a modern replacement grounded in real tribal workflows.

**Operations & Maintenance:**

* Migrated HHS repo to GHCR to ensure long-term access, organizational control, and alignment with HHS-wide infrastructure standards.
* Developed requirements documentation to ensure a shared, well-defined foundation for designing and developing centralized TANF data feedback reports in TDP.
* Ensured SSN errors for WEIs appeared in Critical tab of error reports, supporting timely error resolution by STTs.&#x20;

## Product Roadmap Progress&#x20;

{% hint style="info" %}
For more detailed information on task progress, please visit the [overall roadmap](https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/timeline) for these epics.
{% endhint %}

* Application Health Monitoring | <mark style="color:green;">**ON TRACK**</mark> | Progress: 82% <mark style="color:green;">**(+4%)**</mark> | Estimated Completion Date: July 29, 2025
  * <mark style="color:yellow;">**Potential Risk:**</mark>  Timeline for completion may be affected due to delays in allowing Sentry.
* Continuous User Research & Feedback Loops | <mark style="color:green;">**ON TRACK**</mark> | Progress: 69% <mark style="color:green;">**(+50%)**</mark> | Estimated Completion Date: September 23, 2025
  * <mark style="color:purple;">**Note:**</mark>  Development tickets will be added to this epic shortly, which will affect progress towards completion but the estimated completion date.
* Enabling Secure Data Access for DIGIT in Grafana | <mark style="color:green;">**ON TRACK**</mark> | Progress: 35% <mark style="color:green;">**(+6%)**</mark> | Estimated Completion Date: August 12, 2025
  * <mark style="color:purple;">**Note:**</mark>  This epic encapsulates has not yet been finalized, as there are additional items that may impact scope (e.g., data retention strategy). Thus, timelines and progress percentage are subject to change.
* FRA Post-MVP Enhancements | <mark style="color:green;">**ON TRACK**</mark> | Progress: 17% <mark style="color:green;">**(+8%)**</mark> | Estimated Completion Date: September 23, 2025
  * <mark style="color:purple;">**Note:**</mark>  Developer tickets for some design work is yet to be created, which may impact timelines.
* FRA Reporting Requirements MVP | <mark style="color:green;">**COMPLETE!!!**</mark> | Progress: 100% <mark style="color:green;">**(+2%)**</mark> | Estimated Completion Date: May 15, 2025
* fTANF Replacement - Foundational Research & Concept Validation | <mark style="color:green;">**ON TRACK**</mark> | Progress: 25% <mark style="color:green;">**(+11%)**</mark> | Estimated Completion Date: December 16, 2025
* Regional Staff TDP Access & Onboarding | <mark style="color:red;">**OFF TRACK**</mark> | Progress: 38% <mark style="color:red;">**(-9%)**</mark> | Estimated Completion Date: November 4, 2025
  * <mark style="color:purple;">**Note:**</mark>  Due to some of the unforeseen changes in HHS staffing, this epic is on pause until further notice.

## Tasks

### Application Health Monitoring

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3295">#3295</a> - Associate parsing log files with datafile submissions in DAC</td><td>Improves transparency and traceability, giving OFA users direct access to debugging details and enhancing trust in data processing outcomes.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3258">#3258</a> - Migrate Promtail to Alloy</td><td>Streamlines logging infrastructure, reduces deployment complexity, and ensures scalable, unified access to app logs in Loki.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3336">#3336</a> - Decouple Celery and Redis from backend into separate Cloud.gov services</td><td>Improves scalability, reliability, and maintainability of TDP’s background task infrastructure while aligning with cloud-native best practices.</td><td><mark style="color:yellow;"><strong>IN PROGRESS &#x26; MOVED TO NEXT SPRINT</strong></mark></td></tr></tbody></table>

### Continuous User Feedback & Research Loops

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4483">#4483</a> - Ideate on designs for persistent feedback button &#x26; modal</td><td>Empowers users to share real-time insights in context, fostering continuous improvement through spontaneous, high-quality input while strengthening user trust and platform usability.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4502">#4502</a> - Design contextual in-app feedback prompts</td><td>Enables the design of lightweight, compliant in-app prompts that gather contextual user feedback at key moments in the TANF data workflow—empowering evidence-based product improvements while minimizing user disruption.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4510">#4510</a> - Establish feedback review and synthesis process</td><td>Establishes a consistent, transparent process for turning user feedback into actionable insights—ensuring valuable input informs product and design decisions while reinforcing a culture of continuous improvement.</td><td><mark style="color:blue;"><strong>QASP REVIEW</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4780">#4780</a> -  Explore frontend observability dashboard options and MVP setup</td><td>Allows us to confirm a compliant, privacy-conscious solution and begin surfacing meaningful user behavior insights that will inform future improvements to the TDP experience.</td><td><mark style="color:purple;"><strong>RAFT REVIEW</strong></mark></td></tr></tbody></table>

### Enabling Secure Data Access for DIGIT in Grafana

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3579">#3579</a> - Set up Postgres views for all record types</td><td>Enhances data security, supports compliance, and enables safe, efficient access for Grafana and automation workflows without exposing sensitive information.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4477">#4477</a> - Explore &#x26; align on structure for continuous feedback sessions on Grafana with DIGIT</td><td>Ensures dashboards evolve to meet real user needs, surface usability issues early, and support a culture of continuous improvement without placing a heavy burden on internal stakeholders.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3422">#3422</a> - Create and configure read-only RDS user for Grafana integration</td><td>Enables secure data exploration and dashboarding for OFA while safeguarding production data from accidental changes.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3472">#3472</a> - Investigate Grafana resource requirements for large exports</td><td>Helps determine whether Grafana can efficiently handle large TANF data exports, identifying potential memory constraints, performance limitations, and cost-effective solutions to meet DIGIT's interim data access needs.</td><td><mark style="color:red;"><strong>BLOCKED</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3423">#3423</a> - Grant DIGIT Team access to Grafana with viewer/editor permissions</td><td>Enables secure, controlled data visibility for monitoring and analysis while preserving dashboard integrity and preventing unintended changes.</td><td><mark style="color:purple;"><strong>RAFT REVIEW</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3580">#3580</a> - Create PostgreSQL users, roles, and permissions based on privilege mapping</td><td>Strengthens data security by enforcing least-privilege access and preventing unauthorized exposure of sensitive information.</td><td><mark style="color:yellow;"><strong>IN PROGRESS &#x26; MOVED TO NEXT SPRINT</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4795">#4795</a> -  Explore Vault integration for credential rotation</td><td>Lays the groundwork for centralized, automated secrets management that enhances security, reduces operational overhead, and aligns with long-term DevSecOps goals across the platform.</td><td><mark style="color:yellow;"><strong>IN PROGRESS &#x26; MOVED TO NEXT SPRINT</strong></mark></td></tr></tbody></table>

### FRA Reporting Requirements MVP

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/tdp-command-center-67d9d9079cf6b20017b3725a/issues/gh/raft-tech/tanf-app/4897">#4897</a> - Bug: Rapid clicking of the submit button submits multiple copies of the file</td><td>Ensures accurate submission records, prevents user confusion, and maintains the integrity of the submission history view.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3489">#3489</a> - Fix file input collapsing after cancelling file selection on FRA page</td><td>Ensures a consistent and accessible user experience during file uploads, preventing UI confusion and maintaining usability across browsers.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4900">#4900</a> - Bug: Spinner &#x26; auto refresh don't consistently appear/occur</td><td>Enhances user confidence, prevents confusion during file processing, and improves the overall transparency of the submission workflow.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr></tbody></table>

### FRA Post-MVP Enhancements

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4467">#4467</a> - Extend parser log file support to FRA submissions</td><td>Ensures consistent traceability, simplifies debugging, and aligns FRA reporting with the platform’s standardized logging infrastructure.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr></tbody></table>

### fTANF Replacement - Foundational Research & Concept Validation

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4665">#4665</a> - Build STT fTANF use case tracker</td><td>Enables the team to design a modern replacement grounded in real Tribal workflows, minimizing the risk of building tools that miss critical user needs.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr></tbody></table>

### In-App Error Reporting

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/tdp-command-center-67d9d9079cf6b20017b3725a/issues/gh/raft-tech/tanf-app/4943">#4943</a> - Complete foundational discovery for in-app error reporting</td><td>Enables us to design a compliant, high-impact in-app error reporting experience that aligns with real user needs and implementation realities.</td><td><mark style="color:yellow;"><strong>IN PROGRESS &#x26; MOVED TO NEXT SPRINT</strong></mark></td></tr></tbody></table>

### Operations & Maintenance

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3498">#3498</a> - Migrate Raft/OFA to GHCR</td><td>Ensures long-term access, organizational control, and alignment with HHS-wide infrastructure standards, reducing dependency on third-party registries.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4951">#4951</a> - Create requirements document for centralizing TANF feedback reports in TDP</td><td>Provides a shared, well-defined foundation for designing and developing centralized TANF data feedback reports in TDP, ensuring alignment across teams, reducing ambiguity, and supporting user-centered, compliant implementation.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4660">#4660</a> - Ensure SSN errors for invalid/missing SSNs in WEIs appear in critical tab</td><td>Ensures data integrity and timely error resolution by making high-impact validation issues more visible to STTs, ultimately reducing delays and improving compliance with employment tracking requirements.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3525">#3525</a> - Remediate 2/25 webinspect findings related to RA-5 controls</td><td>Ensures compliance with NIST RA-5 requirements, preserves our system’s ATO standing, and reinforces our commitment to a secure and well-governed infrastructure—even when findings are determined to be false positives.</td><td><mark style="color:blue;"><strong>QASP REVIEW</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3516">#3516</a> - Reevaluate and adjust reparse timeout calculation</td><td>Ensures processing estimates are accurate and practical, improving system monitoring, task management, and developer confidence without affecting the user experience.</td><td><mark style="color:purple;"><strong>RAFT REVIEW</strong></mark></td></tr></tbody></table>

### Regional Staff TDP Access & Onboarding

_Note: Due to unforeseen changes in staffing, we will be postponing work with regional staff features at this time. This may be picked up at a later date._

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3461">#3461 </a>- Create and facilitate Project Updates meeting for regional staff</td><td>Ensures regional staff are well-informed about their new TDP access, providing them with a clear understanding of key functionalities, a live demonstration, and an opportunity for Q&#x26;A, ultimately supporting a smooth onboarding process.</td><td><mark style="color:red;"><strong>BLOCKED</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3523">#3523 </a>- Refine research plan for regional staff MVP onboarding experience</td><td>Ensures user feedback is captured early, guiding design decisions with real-world insights and supporting the creation of a user-centered, effective interface.</td><td><mark style="color:red;"><strong>BLOCKED</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3462">#3462</a> - Create and facilitate optional training session for regional staff</td><td>Empowers them to confidently navigate and utilize TDP’s features, fostering engagement, reducing support needs, and ensuring effective use of the platform.</td><td><mark style="color:red;"><strong>BLOCKED</strong></mark></td></tr></tbody></table>

### User Experience Enhancements

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/tdp-command-center-67d9d9079cf6b20017b3725a/issues/gh/raft-tech/tanf-app/4632">#4632</a> - Revisit UX strategic roadmap and define team objectives</td><td>Ensures alignment with product goals, strengthens cross-functional collaboration, and empowers the UX team to deliver more consistent, user-centered improvements across TDP.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3557">#3557</a> - Explore error message clarity in identified issue areas</td><td>Lays the groundwork for improving error clarity by investigating confusing messages, identifying actionable fixes, and proposing changes that will help users resolve issues more confidently and independently during data submission.</td><td><mark style="color:blue;"><strong>QASP REVIEW</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/4925">#4925</a> - Update file naming convention in submission history downloads</td><td>Improves clarity and traceability for users reviewing submission history outside the platform, reducing confusion and streamlining file organization.</td><td><mark style="color:purple;"><strong>RAFT REVIEW</strong></mark></td></tr></tbody></table>
