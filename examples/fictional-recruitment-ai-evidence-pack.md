# Fictional recruitment AI evidence pack

This worked example shows how the toolkit's separate records can connect for one AI-assisted recruitment workflow. Every organisation, person, product name, date and record ID below is fictional.

It is an illustrative operating record, not legal advice, a conformity assessment, or a conclusion that every recruitment tool is a high-risk AI system. Classification depends on the system's intended purpose and how it is used. Obtain qualified advice for a real system.

## 1. Scenario and working assumptions

**Organisation:** Northstar Staffing Ltd, an EU-based recruitment agency acting as deployer in this example

**System:** Shortlist Assist, supplied by a fictional third party

**Purpose:** summarise applications and recommend a ranked shortlist for open roles

**Decision boundary:** recruiters must review the underlying application and record their own decision; the tool cannot reject an applicant or send a decision

**Accountable owner:** Head of Talent Operations

**Operational owner:** Recruitment Operations Manager

**Review date:** 15 October 2026

The team records the system as **potential Annex III employment high-risk — legal and technical classification review open**. Recruitment and candidate-selection systems are identified in the AI Act's employment category, but this example does not substitute a classification analysis.

## 2. Connected system inventory record

| Field | Example entry |
|---|---|
| System ID | SYS-REC-001 |
| Provider / product | Fictional Vendor Ltd / Shortlist Assist |
| Intended purpose | Summarise applications and recommend a ranked shortlist for recruiter review |
| People operating it | Six recruiters and two recruitment team leads |
| People affected | Job applicants |
| Inputs | CV, application form, role criteria and recruiter notes |
| Outputs | Candidate summary, ranked recommendation and cited application fields |
| Prohibited use | Automatic rejection; inferring protected characteristics; using data outside the approved fields; copying output into a decision without review |
| Human oversight | A trained recruiter compares the output with the original application and role criteria, can disregard it, and records the final decision and reason |
| Working risk status | Potential Annex III employment high-risk; classification decision CL-001 remains open |
| Known limitations | Ranking may over-weight wording similarity; incomplete applications can produce misleading summaries; performance across languages not yet validated |
| Data / rights checks | Privacy and labour-law review open; assess whether a DPIA, worker-representative information, and applicant notice are required |
| Monitoring | Weekly override sample; monthly error and complaint review; immediate escalation for suspected discrimination, material mismatch or provider incident |
| Evidence links | TR-REC-01, AS-REC-01, POL-RAI-03, SOP-OVR-02, DEC-001, REV-001 |

## 3. People and exposure map

| Role | Contact with the system | Decision or control | Potential harm if unprepared |
|---|---|---|---|
| Recruiter | Operates it for each application | Accepts, changes or disregards recommendations | Uncritical reliance, missed qualified applicants, unsupported decisions |
| Team lead | Reviews exceptions and samples | Pauses use and escalates incidents | Systemic errors remain undetected |
| Head of Talent Operations | Accountable business owner | Approves purpose, controls and continued use | Controls do not match the actual workflow |
| Privacy / AI governance lead | Reviews data, notices and classification evidence | Requires remediation or specialist advice | Rights, transparency or record gaps persist |
| Vendor support | Supports the system on the deployer's behalf | Diagnoses approved support cases only | Exposure to unnecessary applicant data or uncontrolled changes |
| Applicants | Affected by the workflow | Can ask for information or challenge a decision through the published process | Career opportunity affected without an understandable route to review |

## 4. Role-based literacy matrix

| Role | Learning outcome | Measure | Practice or assessment | Evidence | Refresh trigger |
|---|---|---|---|---|---|
| Recruiter | Explain the tool's purpose, limits and prohibited uses; verify source material; override and escalate safely | 60-minute facilitated workflow session plus SOP review | Review two fictional applications, identify one unsupported summary and document an override | TR-REC-01 attendance; AS-REC-01 scored scenario; SOP-OVR-02 acknowledgement | New model or data field; material error; six-month review |
| Team lead | Detect patterns in overrides, complaints and errors; pause use when thresholds are met | 45-minute oversight workshop | Interpret a fictional monitoring report and choose an escalation path | TR-LEAD-01; AS-LEAD-01 | Monitoring change; incident; six-month review |
| Accountable owner | Explain intended purpose, working classification, residual gaps and acceptance criteria | 30-minute owner briefing | Approve or return DEC-001 with written rationale | BR-OWN-01; DEC-001 | Purpose, provider or risk-status change |
| Privacy / AI governance | Challenge data, notice, rights and evidence assumptions | Specialist review of system file and provider material | Record findings and owners in REV-001 | REV-001 | Regulatory guidance or processing change |
| Vendor support | Follow access, confidentiality and incident-routing limits | Contract-linked support briefing | Access-control acknowledgement and support simulation | VEN-TR-01; VEN-ACK-01 | Staff or support-scope change |

Passing a slide deck to staff is not treated as completion. For operators, completion requires the scenario exercise and acknowledgement; failed attempts are coached and reassessed.

## 5. Human-oversight scenario

**Exercise AS-REC-01:** Shortlist Assist ranks Candidate B below Candidate A and states that Candidate B lacks the required sector experience. The original application shows two years of relevant experience under a different job title.

The recruiter must:

1. compare the generated statement with the original application and documented role criteria;
2. identify that the statement is unsupported;
3. disregard the ranking and make an independent, criteria-based decision;
4. record the override, affected vacancy and concise reason without adding unnecessary personal data;
5. escalate the output as a potential systematic matching error; and
6. avoid contacting the applicant until the approved review path is complete.

**Pass evidence:** assessor records all six behaviours and links the completed scenario to the recruiter's training record. A pass demonstrates performance in this exercise only; it is not a certificate of legal compliance.

## 6. Example evidence register

| Evidence ID | Date | Record | Owner | Connects to | Status / next review |
|---|---|---|---|---|---|
| CL-001 | 17 Aug 2026 | Classification issue log and counsel questions | AI governance lead | SYS-REC-001 | Open; decision due 5 Sep 2026 |
| POL-RAI-03 | 20 Aug 2026 | Approved responsible AI use policy v3 | Head of Talent Operations | All operating roles | Approved; annual review or trigger |
| SOP-OVR-02 | 22 Aug 2026 | Recruiter verification, override and escalation procedure | Recruitment Operations Manager | Recruiters, team leads | Approved; review after first monitoring cycle |
| TR-REC-01 | 28 Aug 2026 | Recruiter session attendance and facilitator record | Learning lead | Six recruiters | Complete; two absences assigned make-up dates |
| AS-REC-01 | 28 Aug 2026 | Fictional application scenario rubric and results | Team leads | Recruiters | Five pass; one reassessment due 2 Sep 2026 |
| VEN-TR-01 | 29 Aug 2026 | Vendor-support access briefing | System owner | Vendor support staff | Pending named attendee list |
| DEC-001 | 5 Sep 2026 | Accountable-owner go/no-go decision | Head of Talent Operations | CL-001, training, open gaps | Not started |
| REV-001 | 15 Sep 2026 | First monitoring and control review | AI governance lead | Overrides, errors, complaints, changes | Scheduled |

## 7. Decision trail before use

The accountable owner does not approve production use until the file answers each question:

- Is the intended purpose fixed, and is use technically limited to that purpose?
- Has the legal role and high-risk classification been reviewed and recorded?
- Have applicable privacy, employment, worker-information and affected-person transparency duties been assessed?
- Are provider instructions, limitations and change notices available to operators and reviewers?
- Can trained humans understand, challenge, override and stop the workflow in practice?
- Are errors, overrides, complaints, incidents and material changes monitored with named owners?
- Can a reviewer trace every operator to the current measure, assessment, policy and procedure?

DEC-001 records the evidence considered, unresolved gaps, decision, conditions, owner, date and next review. A conditional approval names a deadline and stop condition; it does not silently convert missing evidence into acceptance.

## 8. Open gaps and action log

| Gap | Action | Owner | Due date | Stop condition |
|---|---|---|---|---|
| Final classification not recorded | Complete intended-purpose analysis and obtain qualified review | AI governance lead | 5 Sep 2026 | No production use before decision |
| Provider performance evidence incomplete | Obtain instructions, validation scope, known limitations and change-notice process | System owner | 26 Aug 2026 | No live applicant data |
| Language performance unknown | Test approved fictional cases in each intended language and set acceptance criteria | Recruitment Operations Manager | 3 Sep 2026 | Limit pilot to validated languages |
| Worker and applicant information path not approved | Assess applicable duties and approve notices and challenge route | Privacy / employment counsel | 5 Sep 2026 | No affected-person decisions |
| Two training records incomplete | Run make-up session and assessment | Learning lead | 2 Sep 2026 | Untrained staff have no access |

## 9. Reviewer acceptance test

Select one fictional recruiter and one decision. Within 15 minutes, an internal reviewer should be able to trace:

`SYS-REC-001 → recruiter's role → TR-REC-01 → AS-REC-01 → POL-RAI-03 and SOP-OVR-02 → recorded override → REV-001`

The test fails if a link is missing, the version or date is unclear, the record does not describe what actually happened, or the reviewer must rely on an unrecorded verbal explanation. Log the failure as a gap, assign an owner and repeat the test after correction.

## Primary sources and scope notes

- [Regulation (EU) 2024/1689](https://eur-lex.europa.eu/eli/reg/2024/1689/oj)
- [European Commission — AI literacy questions and answers](https://digital-strategy.ec.europa.eu/en/faqs/ai-literacy-questions-answers)
- [European Commission — Navigating the AI Act](https://digital-strategy.ec.europa.eu/en/faqs/navigating-ai-act)
- [EU AI Act Service Desk — Recital 57 on employment systems](https://ai-act-service-desk.ec.europa.eu/en/ai-act/recital-57)

The Commission's AI literacy Q&A says measures should account for role, risk, context, knowledge and affected people; it also says there is no required certificate or one-size-fits-all format. Its navigation Q&A describes deployer obligations for high-risk systems, including following instructions, monitoring, human oversight and, in relevant workplace contexts, information duties. This example turns those considerations into connected operating records without claiming that records alone establish compliance.

Sources last checked: 17 August 2026.
