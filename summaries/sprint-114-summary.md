---
description: December 4, 2024 - December 17, 2024
---

# Sprint 114 Summary

## Summary

### Highlights

In this sprint, our team successfully completed a range of tasks focused on strengthening security, enhancing developer workflows, refining user interfaces, and improving system monitoring to better align with user and operational needs. Key highlights included:

* Operations & Maintenance:
  * Implemented automated email notifications for system admin role changes, ensuring improved oversight and security.
  * Updated validation logic to reduce erroneous error messages and improve data integrity.
* Improved Developer Tooling:
  * Introduced pre-commit linting checks to maintain code quality and streamline development.
* Application Health Monitoring:
  * Deployed Alertmanager to production, enhancing system monitoring and alerting capabilities.
* User Experience Improvements:
  * Consolidated footer links and implemented dynamic report sections based on user roles for a more intuitive user experience.
  * Established a technical strategy that ensures STT users can consistently access error reports
* FRA Reporting Requirements MVP:
  * Finalized research recruitment sessions with user participants.

## Roadmap Progress&#x20;

\[OMITTED] This will be included in future sprint summaries.

## Tasks

### User Experience Improvements

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3155">#3155</a> - [Spike] Prioritized Errors</td><td>Established a technical strategy that ensures STT users can consistently access error reports, regardless of parser error count, while improving backend performance and UX without halting parsing.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/2137">#2137</a> - Update footer designs to address additions like vulnerability disclosure</td><td>Streamlined the footer's HTML structure by consolidating all links into a single list element, improving maintainability and ensuring consistency across the layout without impacting the visual presentation.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/2217">#2217</a> - As a 'Data Analyst', I would like to only view sections that need submission</td><td>Enhanced the user experience for STT Data Analysts by displaying only relevant sections for data submission, reducing confusion and increasing efficiency by hiding unnecessary sections they do not need to interact with.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3271">#3271</a> - Reprocessed On enhancement</td><td>Improves the clarity and usability of the submission history by replacing the most recent reprocessed date with a clickable trigger that opens a detailed dialog, offering full transparency on reprocessing events and ensuring users have access to accurate, context-rich information.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr></tbody></table>

### Improved Developer Tooling

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/1786">#1786</a> - As a developer, I want linters to run automatically before git push</td><td>Automated the linting and secret checks during the commit process, ensuring code quality and preventing sensitive data from being pushed to repositories, thereby enhancing security and consistency in development workflows.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3223">#3223</a> - Automate buildpack states via Terraform</td><td>Enhances the team's ability to manage and track CloudFoundry deployments more effectively, improving state visibility, reducing unnecessary redeployments, and ensuring better control over infrastructure, while maintaining seamless integration with CircleCI and updating relevant documentation.</td><td><mark style="color:blue;"><strong>IN PROGRESS &#x26; MOVED TO NEXT SPRINT</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3205">#3205</a> - Reparse command refactor</td><td>Streamlines and simplifies the reparse logic by creating a shared utility function, improving maintainability and enabling more customizable parsing behavior for both the admin and management commands.</td><td><mark style="color:blue;"><strong>IN PROGRESS &#x26; MOVED TO NEXT SPRINT</strong></mark></td></tr></tbody></table>

### FRA Reporting Requirements MVP

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3267">#3267</a> - FRA Research Recruitment</td><td>Ensured the efficient and organized tracking of research recruitment, enabling timely communication with targeted participants and documenting any changes to recruitment criteria, ultimately supporting the successful execution of FRA research sessions.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3297">#3297 </a>- FRA Research Synthesis</td><td>Provides valuable user insights through finalized research synthesis and findings, guiding the development of the FRA MVP while ensuring stakeholder alignment, accessibility, and actionable outcomes for future development.</td><td><mark style="color:blue;"><strong>IN PROGRESS &#x26; MOVED TO NEXT SPRINT</strong></mark></td></tr></tbody></table>

### Application Health Monitoring

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3254">#3254 </a>- AlertManager Cloud.gov</td><td>Ensured that Alertmanager is successfully deployed to production, enabling efficient monitoring, management, and silencing of alerts, while providing accessible alert management functionality for administrators and developers across all environments.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3243">#3243</a> - Promtail Pipelines</td><td>Enhances the Grafana logging dashboard by implementing Promtail pipelines to extract and enrich log metadata (such as log level, message, and app name), enabling more powerful and flexible querying of logs in Grafana.</td><td><mark style="color:yellow;"><strong>QASP REVIEW</strong></mark></td></tr></tbody></table>

### Operations & Maintenance

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3278">#3278</a> - Revise Validation Logic for TANF Active Case Items 27, 29, 26AIII, and 32D</td><td>Resolved unnecessary error messages for STTs by updating the validation logic to correctly accept a value of 0, ensuring smoother data submission and reducing confusion or incorrect rejections of valid entries.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/1337">#1337</a> - As a sys owner, I want to be emailed when sys admin permissions have been assigned.</td><td>Ensured that Lauren is notified via email whenever a "System Admin" role is assigned or unassigned, improving auditing capabilities and enhancing oversight of critical user role changes.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3320">#3320</a> - Revise Cat 3 Validator Logic for SSP Active Case Data</td><td>Resolved incorrect error messages in SSP Active Case reports by updating the validation logic to correctly accept a value of 3 for citizenship status when family affiliation is 1, ensuring accurate feedback for STTs and reducing unnecessary resubmissions.</td><td><mark style="color:green;"><strong>COMPLETE</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/1577">#1577</a> - Upgrade react-scripts to 5.0</td><td>Ensures that the project is using the latest stable versions of <code>react-scripts</code> and <code>file-type</code>, addressing potential breaking changes and improving overall stability and functionality while maintaining compatibility and compliance with modern standards.</td><td><mark style="color:yellow;"><strong>QASP REVIEW</strong></mark></td></tr><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3316">#3316</a> - v 3.7.5 Release Notes and Knowledge Center Updates</td><td>Ensures STTs receive timely and accurate release notes via both the TDP portal and email, improving communication, transparency, and user understanding of recent updates and changes.</td><td><mark style="color:yellow;"><strong>QASP REVIEW</strong></mark></td></tr></tbody></table>

### Regional Staff Access to TDP

<table><thead><tr><th width="176">Task</th><th width="445">Value Proposition</th><th>Status</th></tr></thead><tbody><tr><td><a href="https://app.zenhub.com/workspaces/sprint-board-5f18ab06dfd91c000f7e682e/issues/gh/raft-tech/tanf-app/3249">#3249</a> - As regional staff, I want to be able to see the status of my STTs submissions and view their error reports.</td><td>Empowers regional staff with the ability to directly access submission statuses and error reports for their regions, reducing delays and the central office's workload, while improving overall transparency and efficiency in managing STT data submissions.</td><td><mark style="color:orange;"><strong>RAFT REVIEW</strong></mark></td></tr></tbody></table>

