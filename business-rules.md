# Business Rules — Spotify Music Discovery & Personalised Recommendation System

> **Case Study Context:** This document forms part of an academic Business Analysis case study. The business rules below are proposed rules for a hypothetical solution inspired by Spotify's music discovery context. They do not represent Spotify's actual internal business rules or policies.

## 1. Purpose

This document identifies proposed business rules that would influence how the hypothetical music discovery and personalised recommendation solution operates.

Business rules define constraints, conditions or principles that the proposed solution should follow. They are distinct from functional requirements, which describe the behaviour the solution must provide.

---

## 2. Proposed Business Rules

| ID     | Business Rule                                                                                                                               | Rationale                                                     |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| BR-001 | Recommendations should be based only on information that the proposed solution is permitted to use.                                         | Supports appropriate data use and privacy considerations.     |
| BR-002 | Personal information and interaction data should be handled in accordance with applicable privacy requirements.                             | Protects users and supports responsible data handling.        |
| BR-003 | Recommendation results should be relevant to the defined purpose of the music discovery experience.                                         | Keeps recommendations aligned with the business objective.    |
| BR-004 | The solution should not expose information that a user is not authorised to access.                                                         | Supports security and privacy.                                |
| BR-005 | Recommendation processing should operate within defined data-quality requirements.                                                          | Poor-quality data may affect recommendation relevance.        |
| BR-006 | Requirements must be traceable to an identified business need, stakeholder need or user requirement.                                        | Supports requirements governance and validation.              |
| BR-007 | Changes to approved requirements should be documented and assessed for impact.                                                              | Supports controlled requirements management.                  |
| BR-008 | Recommendations should not intentionally disadvantage or exclude creators based on inappropriate or prohibited criteria.                    | Supports responsible and fair solution design.                |
| BR-009 | The proposed solution should provide an appropriate user experience when sufficient information is unavailable to generate recommendations. | Prevents an unclear or incomplete user experience.            |
| BR-010 | Business rules and requirements must be validated with appropriate stakeholders before implementation in a real-world environment.          | Ensures the proposed solution reflects agreed business needs. |

---

## 3. Detailed Business Rules

### BR-001 — Permitted Information

The proposed recommendation process should only use information that the solution is permitted to collect, process and use for the defined business purpose.

This rule supports the privacy and data-governance considerations identified within the case study.

---

### BR-002 — Privacy and Data Handling

Personal information and relevant interaction data should be handled in accordance with applicable privacy requirements.

The case study does not define specific legal, organisational or technical privacy controls. These would require further analysis and stakeholder validation in a real-world project.

---

### BR-003 — Recommendation Relevance

Recommendations should support the defined purpose of helping listeners discover music that may be relevant to their interests.

Recommendation relevance should be evaluated using agreed business and user measures.

---

### BR-004 — Authorised Access

The proposed solution should prevent users from accessing information that they are not authorised to access.

This rule applies particularly to personal information, protected system information and any other restricted information.

---

### BR-005 — Data Quality

Information used to support recommendation processing should meet defined data-quality expectations.

Where data is incomplete, inaccurate or otherwise unsuitable, the proposed solution should follow agreed handling rules.

---

### BR-006 — Requirements Traceability

Each approved requirement should be traceable to its source, such as:

* Business need
* Stakeholder need
* User story
* Business rule
* Process requirement

This supports validation and helps identify the impact of requirement changes.

---

### BR-007 — Requirements Change Control

Changes to approved requirements should be documented and assessed for potential impact.

Impact assessment may consider:

* Business objectives
* Stakeholders
* User stories
* Functional requirements
* Non-functional requirements
* Acceptance criteria
* Scope
* Dependencies

---

### BR-008 — Fair Creator Visibility

The proposed solution should avoid intentionally disadvantaging or excluding creators based on inappropriate or prohibited criteria.

The specific fairness criteria and controls would require further stakeholder, legal and technical analysis in a real-world implementation.

---

### BR-009 — Insufficient Recommendation Information

Where sufficient information is unavailable to generate a meaningful recommendation, the proposed solution should provide an appropriate alternative experience rather than presenting misleading results.

The exact fallback behaviour would require further requirements elicitation.

---

### BR-010 — Stakeholder Validation

Business rules identified in this case study should be treated as proposed rules until validated and approved by appropriate stakeholders.

This distinction is important because the project is an academic case study and does not represent an approved set of Spotify business rules.

---

## 4. Relationship to Requirements

Business rules can influence functional and non-functional requirements.

For example:

| Business Rule                                    | Related Requirements      |
| ------------------------------------------------ | ------------------------- |
| BR-001 — Permitted Information                   | FR-004, FR-005, NFR-006   |
| BR-002 — Privacy and Data Handling               | FR-004, NFR-005, NFR-006  |
| BR-003 — Recommendation Relevance                | FR-005, FR-006            |
| BR-004 — Authorised Access                       | NFR-005, NFR-006          |
| BR-005 — Data Quality                            | FR-005, NFR-011           |
| BR-006 — Requirements Traceability               | FR-012, NFR-012           |
| BR-007 — Requirements Change Control             | FR-012, NFR-012           |
| BR-008 — Fair Creator Visibility                 | FR-010                    |
| BR-009 — Insufficient Recommendation Information | FR-011                    |
| BR-010 — Stakeholder Validation                  | All proposed requirements |

---

## 5. Business Analysis Considerations

The business rules in this document are proposed for demonstration purposes.

In a real project, the Business Analyst would work with relevant stakeholders to:

1. Identify applicable business policies and rules.
2. Confirm the source and authority of each rule.
3. Determine which requirements are affected.
4. Identify conflicts between rules and requirements.
5. Document exceptions.
6. Obtain stakeholder approval.
7. Maintain traceability as rules change.

The rules should therefore be reviewed alongside the requirements analysis and requirements traceability artefacts.
