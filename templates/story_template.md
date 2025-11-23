# Story: [Short Story Title]

**Story Key:** [PROJ-XXX]  
**Epic:** [PROJ-YYY - Epic Name]  
**Assignee:** [Developer Name]  
**Reporter:** [PO/BA Name]  
**Sprint:** [Sprint X]

---

## User Story

**As a** [type of user],  
**I want** [goal/desire],  
**So that** [benefit/value].

---

## Business Context

[1-2 sentences: Why is this story important? What business problem does it solve?]

---

## Functional Requirements

### Preconditions
- [What must be true before this feature can be used]

### Postconditions
- [What will be true after successful execution]

### Business Rules
1. [Rule 1: e.g., "Transaction amount must be > 0"]
2. [Rule 2: e.g., "User must be authenticated"]
3. [Rule 3]

### Edge Cases & Error Scenarios
- **Edge Case 1:** [Description and expected behavior]
- **Edge Case 2:** [Description and expected behavior]
- **Error Scenario 1:** [e.g., "Invalid input → return 400 with error code X"]

---

## Non-Functional Requirements

| Category | Requirement |
|----------|-------------|
| **Performance** | [e.g., API response < 300ms p95] |
| **Security** | [e.g., Requires OAuth2 token with scope X] |
| **Logging** | [e.g., Log transaction ID, user ID (hashed), timestamp; do NOT log account numbers] |
| **Monitoring** | [e.g., Emit metric for success/failure rate] |

---

## Acceptance Criteria

### Functional
- [ ] **Given** [precondition], **When** [action], **Then** [expected outcome]
- [ ] **Given** [precondition], **When** [action], **Then** [expected outcome]
- [ ] **Given** [error condition], **When** [action], **Then** [error response with code X]

### Non-Functional
- [ ] API response time < [X]ms under normal load
- [ ] No PII logged in application logs
- [ ] Unit test coverage ≥ 80% for new code
- [ ] Integration tests cover all acceptance criteria

---

## AI-Assisted Refinement

**Refined By:** [PO/BA Name]  
**Date:** [YYYY-MM-DD]

**Agent Prompts Used:**
- "Generate acceptance criteria in Given/When/Then format for this story"
- "Identify missing edge cases and error scenarios"
- "Propose non-functional requirements based on similar features"

**Clarifications Resolved:**
- [Question 1 → Answer]
- [Question 2 → Answer]

---

## Technical Notes

**Impacted Services/Modules:**  
[e.g., payment-service, user-service]

**API Endpoints (if applicable):**  
- `POST /api/v1/transactions`
- `GET /api/v1/transactions/{id}`

**Data Model Changes:**  
[Brief description or link to schema/ERD]

---

## Links & Attachments

- **Spec Document:** [Confluence/GitLab link]
- **OpenAPI Spec:** [GitLab link to openapi.yaml]
- **Architecture Decision Record:** [GitLab link to ADR]
- **Related Stories:** [PROJ-AAA, PROJ-BBB]

---

## Definition of Ready Checklist

- [ ] Story is refined with clear acceptance criteria
- [ ] Edge cases and error scenarios identified
- [ ] NFRs documented
- [ ] Dependencies identified and resolved or tracked
- [ ] Spec linked and reviewed by tech lead
- [ ] Story sized and estimated by team

---

## Definition of Done Checklist

- [ ] Code implements all acceptance criteria
- [ ] Unit tests written and passing (≥80% coverage)
- [ ] Integration/API tests written and passing
- [ ] Code reviewed and approved in GitLab MR
- [ ] No secrets or PII in logs
- [ ] Documentation updated (README, API docs, runbooks)
- [ ] Deployed to dev/test environment via ArgoCD
- [ ] QA sign-off obtained
- [ ] Security review completed (if required)

