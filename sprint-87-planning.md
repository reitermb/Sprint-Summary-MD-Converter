# Sprint 87 Planning

## Sprint 87 Planning

11/22/2023 - 12/05/2023

### Sprint Goal

* Dev:
  * Continue parsing engine development
    * Review SSP Sec 04
    * Implement all Tribal Sec (02, 03 and review 01)
  * Finalize review on #2683 - ZAP CORS Misconfiguration
  * \#2599 - Error Report "Friendly Names"
  * Coordinate w/ OFA and draft dev contingency plan for future gov shutdown
    * Document any further planning (if any beyond Andrew's use of ACF laptop)
* DevOps:
  * 2429 - Singular Clam AV
  * 2722 - Singular deployment workflow
    * Scoped out of 2419
  * \#2729 - Migrations via CircleCI

***

### New Tickets to Consider

* Kibana #1858
* TANF Enhancement #2681?
* lower priorirty: #2711/ #2646 Jan/Mo availability?

***

### Planned Goal + Stretch

| Champion |                                                                Goal                                                                |                                  Stretch                                  |
| -------- | :--------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------: |
| Mo       |                                                             2429, 2599                                                             |                            2536 (Cat 4) support                           |
| George   |                                                          2663, 2722, 2592                                                          |                                    2419                                   |
| Jan      |                                                       2729, 2592/2722 support                                                      |                               1116 Tribal S3                              |
| Eric     |                                                     1114, 1115, SSP PR support                                                     |                          Pairing on Kibana w/ Tom                         |
| Andrew   |                                                            2536 (Cat 4)                                                            |                          DevOps + Parsing support                         |
| Miles    |  TDP onboarding & utilization support, followup with past errors participant shortlist, support in research planning & a11y audits | General-use HTML Email Template, continued refinement of research roadmap |
| Camilla  | TDP onboarding & utilization support, proceed with internal TDP & Django a11y audit, support in plan for revisited errors research |                  Continued refinement of research roadmap                 |

***

### Considerations

* Day off for Thanksgiving on the 23rd
  * Miles OOO Nov 22-24
  * Lauren OOO Nov 21-24
  * Andrew OOO Nov 23-24th
  * OFA has early release Nov 22nd @ 2PM
* Alex to drop official response to OCIO DMARC issue/blocker in the SendGrid hack.md (issue related to a DDoS attack)
* Contingency plan and response tabletop coming in two weeks \~ 1-2 hours of dev time, discussion oriented
* Penetration testing in staging, will take \~3 weeks
  * We should communicate plans re: pushing releases
  * Release next week to give OCIO December for testing
