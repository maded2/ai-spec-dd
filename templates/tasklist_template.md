# Implementation Tasks: [Story Title]

**Jira Story:** [PROJ-XXX - Story Title with link]  
**Epic:** [PROJ-YYY - Epic Title with link]  
**Assignee:** [Developer Name]  
**Started:** [YYYY-MM-DD]  
**Target Completion:** [YYYY-MM-DD]  
**Status:** [Not Started | In Progress | Blocked | Completed]

---

## Story Summary

[1-2 sentence summary of what this story delivers]

---

## Acceptance Criteria Quick Reference

- [ ] AC1: [Brief summary of acceptance criterion 1]
- [ ] AC2: [Brief summary of acceptance criterion 2]
- [ ] AC3: [Brief summary of acceptance criterion 3]

---

## Implementation Tasks

### Phase 1: Analysis & Design

- [ ] **Task 1.1:** Review Jira story, spec, and linked architecture docs
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 1.2:** Review related OpenAPI spec and ADRs in GitLab
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 1.3:** Identify impacted services/modules and dependencies
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**
    - **Impacted:**
        - [ ] Service/Module 1
        - [ ] Service/Module 2

- [ ] **Task 1.4:** Design technical approach and data flow
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**
    - **Decisions:**
        - [Key decision 1]
        - [Key decision 2]

- [ ] **Task 1.5:** Identify edge cases and error handling strategy
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

---

### Phase 2: Database/Schema Changes (if applicable)

- [ ] **Task 2.1:** Design database schema changes
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**
    - **Changes:**
        - [ ] New table: [table_name]
        - [ ] New column: [table.column]
        - [ ] Index: [index_name]

- [ ] **Task 2.2:** Write database migration script
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **File:** `src/main/resources/db/migration/V[XXX]__[description].sql`
    - **Notes:**

- [ ] **Task 2.3:** Test migration locally (up and down if applicable)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 2.4:** Verify migration is backward-compatible
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

---

### Phase 3: Backend Implementation

- [ ] **Task 3.1:** Create/update domain models and entities
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/main/java/.../model/[Entity].java`
    - **Notes:**

- [ ] **Task 3.2:** Create/update repository layer
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/main/java/.../repository/[Repository].java`
    - **Notes:**

- [ ] **Task 3.3:** Implement service layer business logic
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/main/java/.../service/[Service].java`
    - **Business Rules Implemented:**
        - [ ] Rule 1: [description]
        - [ ] Rule 2: [description]
    - **Notes:**

- [ ] **Task 3.4:** Implement controller/API endpoints
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/main/java/.../controller/[Controller].java`
    - **Endpoints:**
        - [ ] `POST /api/v1/[resource]`
        - [ ] `GET /api/v1/[resource]/{id}`
    - **Notes:**

- [ ] **Task 3.5:** Implement DTOs and mappers
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/main/java/.../dto/[DTO].java`
        - [ ] `src/main/java/.../mapper/[Mapper].java`
    - **Notes:**

- [ ] **Task 3.6:** Implement error handling and validation
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Error Scenarios Handled:**
        - [ ] Invalid input → 400 with error code [CODE]
        - [ ] Unauthorized → 401
        - [ ] Not found → 404
        - [ ] Business rule violation → 422 with error code [CODE]
    - **Notes:**

- [ ] **Task 3.7:** Add logging (no PII/sensitive data)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Logged:**
        - [ ] Request ID
        - [ ] User ID (hashed/masked)
        - [ ] Operation outcome (success/failure)
    - **NOT Logged:**
        - [ ] Account numbers
        - [ ] PII
    - **Notes:**

- [ ] **Task 3.8:** Add monitoring/metrics
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Metrics:**
        - [ ] Success/failure counter
        - [ ] Response time histogram
    - **Notes:**

---

### Phase 4: Integration (if applicable)

- [ ] **Task 4.1:** Integrate with upstream service: [service-name]
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 4.2:** Integrate with downstream service: [service-name]
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 4.3:** Implement Kafka producer/consumer (if applicable)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Topics:**
        - [ ] Produce to: `[topic-name]`
        - [ ] Consume from: `[topic-name]`
    - **Notes:**

- [ ] **Task 4.4:** Handle integration error scenarios
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Scenarios:**
        - [ ] Upstream timeout → retry with backoff
        - [ ] Downstream unavailable → circuit breaker
    - **Notes:**

---

### Phase 5: Testing

- [ ] **Task 5.1:** Write unit tests for domain/business logic
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/test/java/.../service/[Service]Test.java`
    - **Coverage Target:** ≥80%
    - **Actual Coverage:** [X]%
    - **Notes:**

- [ ] **Task 5.2:** Write unit tests for controllers
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/test/java/.../controller/[Controller]Test.java`
    - **Notes:**

- [ ] **Task 5.3:** Write integration/API tests
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/test/java/.../integration/[Feature]IntegrationTest.java`
    - **Scenarios Covered:**
        - [ ] Happy path (AC1)
        - [ ] Edge case 1 (AC2)
        - [ ] Error scenario 1 (AC3)
    - **Notes:**

- [ ] **Task 5.4:** Write negative/boundary tests
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Scenarios:**
        - [ ] Invalid input
        - [ ] Boundary values
        - [ ] Unauthorized access
    - **Notes:**

- [ ] **Task 5.5:** Run all tests locally and verify passing
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Results:**
        - Unit tests: [X passed / Y total]
        - Integration tests: [X passed / Y total]
    - **Notes:**

- [ ] **Task 5.6:** Manual testing in local/dev environment
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Test Cases:**
        - [ ] AC1: [description]
        - [ ] AC2: [description]
        - [ ] AC3: [description]
    - **Notes:**

---

### Phase 6: Documentation

- [ ] **Task 6.1:** Update OpenAPI spec (if API changes)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **File:** `docs/api/[service]-api.yaml`
    - **Notes:**

- [ ] **Task 6.2:** Update README with new features/endpoints
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **File:** `README.md`
    - **Notes:**

- [ ] **Task 6.3:** Update/create runbook for operations
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **File:** `docs/runbooks/[feature]-runbook.md`
    - **Notes:**

- [ ] **Task 6.4:** Document configuration changes
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **New Config:**
        - [ ] Environment variable: `[VAR_NAME]`
        - [ ] Feature flag: `[FLAG_NAME]`
    - **Notes:**

---

### Phase 7: Code Review & Quality

- [ ] **Task 7.1:** Run AI pre-review on changes
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Agent Findings:**
        - [ ] Finding 1 → [Resolution]
        - [ ] Finding 2 → [Resolution]
    - **Notes:**

- [ ] **Task 7.2:** Self-review code for:
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Checklist:**
        - [ ] No secrets or credentials hard-coded
        - [ ] No PII in logs
        - [ ] Error handling complete
        - [ ] Code follows team standards
        - [ ] All TODOs resolved or tracked
    - **Notes:**

- [ ] **Task 7.3:** Run linter and fix issues
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 7.4:** Run security scan (SAST) locally
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Issues Found:** [X]
    - **Issues Resolved:** [X]
    - **Notes:**

---

### Phase 8: GitLab MR & CI/CD

- [ ] **Task 8.1:** Create feature branch
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Branch:** `feature/PROJ-XXX-short-description`
    - **Notes:**

- [ ] **Task 8.2:** Commit changes with clear messages
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Commits:**
        - [ ] `feat(api): add POST /transactions endpoint [PROJ-XXX]`
        - [ ] `test(api): add integration tests for transactions [PROJ-XXX]`
        - [ ] `docs(api): update OpenAPI spec [PROJ-XXX]`
    - **Notes:**

- [ ] **Task 8.3:** Push branch and create GitLab MR
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **MR Link:** [URL]
    - **Notes:**

- [ ] **Task 8.4:** Fill out MR template completely
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Sections Completed:**
        - [ ] Summary
        - [ ] Acceptance criteria coverage
        - [ ] Testing evidence
        - [ ] Security checklist
    - **Notes:**

- [ ] **Task 8.5:** Verify GitLab CI pipeline passes
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Pipeline Status:**
        - [ ] Build: ✅
        - [ ] Unit tests: ✅
        - [ ] Integration tests: ✅
        - [ ] Security scan: ✅
    - **Notes:**

- [ ] **Task 8.6:** Address CI failures (if any)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Issues:**
        - [ ] Issue 1 → [Resolution]
    - **Notes:**

---

### Phase 9: Code Review & Iteration

- [ ] **Task 9.1:** Request code review from team
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Reviewers:** [Name1, Name2]
    - **Notes:**

- [ ] **Task 9.2:** Address review comments
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Comments:**
        - [ ] Comment 1 → [Resolution]
        - [ ] Comment 2 → [Resolution]
    - **Notes:**

- [ ] **Task 9.3:** Obtain approval from reviewers
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Approvals:**
        - [ ] Reviewer 1: ✅
        - [ ] Reviewer 2: ✅
    - **Notes:**

---

### Phase 10: Deployment & Verification

- [ ] **Task 10.1:** Merge MR to main branch
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Merged:** [YYYY-MM-DD HH:MM]
    - **Notes:**

- [ ] **Task 10.2:** Verify deployment to dev environment via ArgoCD
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **ArgoCD Status:** [Synced | Healthy]
    - **Notes:**

- [ ] **Task 10.3:** Run smoke tests in dev environment
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Tests:**
        - [ ] API endpoint accessible
        - [ ] Happy path works
        - [ ] Error handling works
    - **Notes:**

- [ ] **Task 10.4:** Verify logs and metrics in dev
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Checks:**
        - [ ] No errors in logs
        - [ ] Metrics being emitted
        - [ ] No PII in logs
    - **Notes:**

- [ ] **Task 10.5:** Hand off to QA for testing
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **QA Environment:** [dev | test]
    - **Test Evidence Link:** [URL]
    - **Notes:**

---

### Phase 11: QA & Sign-off

- [ ] **Task 11.1:** Support QA during testing
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Issues Found:** [X]
    - **Notes:**

- [ ] **Task 11.2:** Fix defects found by QA
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Defects:**
        - [ ] Defect 1 → [Resolution]
    - **Notes:**

- [ ] **Task 11.3:** Obtain QA sign-off
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **QA Approved:** [YYYY-MM-DD]
    - **Notes:**

- [ ] **Task 11.4:** Obtain security review (if required)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Security Approved:** [YYYY-MM-DD]
    - **Notes:**

---

### Phase 12: Production Readiness

- [ ] **Task 12.1:** Update Jira story status to "Ready for Production"
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 12.2:** Prepare deployment notes and rollback plan
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Rollback Plan:** [Brief description]
    - **Notes:**

- [ ] **Task 12.3:** Coordinate with ops for production deployment
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Deployment Window:** [YYYY-MM-DD HH:MM]
    - **Notes:**

- [ ] **Task 12.4:** Monitor production deployment
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Deployment Status:** [Success | Rolled Back]
    - **Notes:**

- [ ] **Task 12.5:** Verify in production (smoke tests)
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Tests:**
        - [ ] API endpoint accessible
        - [ ] Happy path works
        - [ ] Metrics and logs healthy
    - **Notes:**

- [ ] **Task 12.6:** Update Jira story to "Done"
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Completed:** [YYYY-MM-DD]
    - **Notes:**

---

## Summary

**Total Estimated Effort:** [Xh]  
**Total Actual Effort:** [Xh]  
**Variance:** [+/- Xh]

**Key Learnings:**
- [Learning 1]
- [Learning 2]

**Blockers Encountered:**
- [Blocker 1 and resolution]

**AI Assistance Used:**
- [Prompt 1: Generated code skeletons]
- [Prompt 2: Generated test cases]
- [Prompt 3: Pre-reviewed MR]

---

## Links

- **Jira Story:** [PROJ-XXX](https://jira.example.com/browse/PROJ-XXX)
- **GitLab MR:** [!123](https://gitlab.example.com/project/merge_requests/123)
- **OpenAPI Spec:** [Link](https://gitlab.example.com/.../docs/api/service-api.yaml)
- **ArgoCD Application:** [Link](https://argocd.example.com/applications/service-name)# Implementation Tasks: [Story Title]

**Jira Story:** [PROJ-XXX - Story Title with link]  
**Epic:** [PROJ-YYY - Epic Title with link]  
**Assignee:** [Developer Name]  
**Started:** [YYYY-MM-DD]  
**Target Completion:** [YYYY-MM-DD]  
**Status:** [Not Started | In Progress | Blocked | Completed]

---

## Story Summary

[1-2 sentence summary of what this story delivers]

---

## Acceptance Criteria Quick Reference

- [ ] AC1: [Brief summary of acceptance criterion 1]
- [ ] AC2: [Brief summary of acceptance criterion 2]
- [ ] AC3: [Brief summary of acceptance criterion 3]

---

## Implementation Tasks

### Phase 1: Analysis & Design

- [ ] **Task 1.1:** Review Jira story, spec, and linked architecture docs
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 1.2:** Review related OpenAPI spec and ADRs in GitLab
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 1.3:** Identify impacted services/modules and dependencies
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**
    - **Impacted:**
        - [ ] Service/Module 1
        - [ ] Service/Module 2

- [ ] **Task 1.4:** Design technical approach and data flow
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**
    - **Decisions:**
        - [Key decision 1]
        - [Key decision 2]

- [ ] **Task 1.5:** Identify edge cases and error handling strategy
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

---

### Phase 2: Database/Schema Changes (if applicable)

- [ ] **Task 2.1:** Design database schema changes
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**
    - **Changes:**
        - [ ] New table: [table_name]
        - [ ] New column: [table.column]
        - [ ] Index: [index_name]

- [ ] **Task 2.2:** Write database migration script
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **File:** `src/main/resources/db/migration/V[XXX]__[description].sql`
    - **Notes:**

- [ ] **Task 2.3:** Test migration locally (up and down if applicable)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 2.4:** Verify migration is backward-compatible
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

---

### Phase 3: Backend Implementation

- [ ] **Task 3.1:** Create/update domain models and entities
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/main/java/.../model/[Entity].java`
    - **Notes:**

- [ ] **Task 3.2:** Create/update repository layer
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/main/java/.../repository/[Repository].java`
    - **Notes:**

- [ ] **Task 3.3:** Implement service layer business logic
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/main/java/.../service/[Service].java`
    - **Business Rules Implemented:**
        - [ ] Rule 1: [description]
        - [ ] Rule 2: [description]
    - **Notes:**

- [ ] **Task 3.4:** Implement controller/API endpoints
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/main/java/.../controller/[Controller].java`
    - **Endpoints:**
        - [ ] `POST /api/v1/[resource]`
        - [ ] `GET /api/v1/[resource]/{id}`
    - **Notes:**

- [ ] **Task 3.5:** Implement DTOs and mappers
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/main/java/.../dto/[DTO].java`
        - [ ] `src/main/java/.../mapper/[Mapper].java`
    - **Notes:**

- [ ] **Task 3.6:** Implement error handling and validation
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Error Scenarios Handled:**
        - [ ] Invalid input → 400 with error code [CODE]
        - [ ] Unauthorized → 401
        - [ ] Not found → 404
        - [ ] Business rule violation → 422 with error code [CODE]
    - **Notes:**

- [ ] **Task 3.7:** Add logging (no PII/sensitive data)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Logged:**
        - [ ] Request ID
        - [ ] User ID (hashed/masked)
        - [ ] Operation outcome (success/failure)
    - **NOT Logged:**
        - [ ] Account numbers
        - [ ] PII
    - **Notes:**

- [ ] **Task 3.8:** Add monitoring/metrics
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Metrics:**
        - [ ] Success/failure counter
        - [ ] Response time histogram
    - **Notes:**

---

### Phase 4: Integration (if applicable)

- [ ] **Task 4.1:** Integrate with upstream service: [service-name]
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 4.2:** Integrate with downstream service: [service-name]
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 4.3:** Implement Kafka producer/consumer (if applicable)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Topics:**
        - [ ] Produce to: `[topic-name]`
        - [ ] Consume from: `[topic-name]`
    - **Notes:**

- [ ] **Task 4.4:** Handle integration error scenarios
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Scenarios:**
        - [ ] Upstream timeout → retry with backoff
        - [ ] Downstream unavailable → circuit breaker
    - **Notes:**

---

### Phase 5: Testing

- [ ] **Task 5.1:** Write unit tests for domain/business logic
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/test/java/.../service/[Service]Test.java`
    - **Coverage Target:** ≥80%
    - **Actual Coverage:** [X]%
    - **Notes:**

- [ ] **Task 5.2:** Write unit tests for controllers
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/test/java/.../controller/[Controller]Test.java`
    - **Notes:**

- [ ] **Task 5.3:** Write integration/API tests
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Files:**
        - [ ] `src/test/java/.../integration/[Feature]IntegrationTest.java`
    - **Scenarios Covered:**
        - [ ] Happy path (AC1)
        - [ ] Edge case 1 (AC2)
        - [ ] Error scenario 1 (AC3)
    - **Notes:**

- [ ] **Task 5.4:** Write negative/boundary tests
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Scenarios:**
        - [ ] Invalid input
        - [ ] Boundary values
        - [ ] Unauthorized access
    - **Notes:**

- [ ] **Task 5.5:** Run all tests locally and verify passing
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Results:**
        - Unit tests: [X passed / Y total]
        - Integration tests: [X passed / Y total]
    - **Notes:**

- [ ] **Task 5.6:** Manual testing in local/dev environment
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Test Cases:**
        - [ ] AC1: [description]
        - [ ] AC2: [description]
        - [ ] AC3: [description]
    - **Notes:**

---

### Phase 6: Documentation

- [ ] **Task 6.1:** Update OpenAPI spec (if API changes)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **File:** `docs/api/[service]-api.yaml`
    - **Notes:**

- [ ] **Task 6.2:** Update README with new features/endpoints
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **File:** `README.md`
    - **Notes:**

- [ ] **Task 6.3:** Update/create runbook for operations
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **File:** `docs/runbooks/[feature]-runbook.md`
    - **Notes:**

- [ ] **Task 6.4:** Document configuration changes
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **New Config:**
        - [ ] Environment variable: `[VAR_NAME]`
        - [ ] Feature flag: `[FLAG_NAME]`
    - **Notes:**

---

### Phase 7: Code Review & Quality

- [ ] **Task 7.1:** Run AI pre-review on changes
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Agent Findings:**
        - [ ] Finding 1 → [Resolution]
        - [ ] Finding 2 → [Resolution]
    - **Notes:**

- [ ] **Task 7.2:** Self-review code for:
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Checklist:**
        - [ ] No secrets or credentials hard-coded
        - [ ] No PII in logs
        - [ ] Error handling complete
        - [ ] Code follows team standards
        - [ ] All TODOs resolved or tracked
    - **Notes:**

- [ ] **Task 7.3:** Run linter and fix issues
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 7.4:** Run security scan (SAST) locally
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Issues Found:** [X]
    - **Issues Resolved:** [X]
    - **Notes:**

---

### Phase 8: GitLab MR & CI/CD

- [ ] **Task 8.1:** Create feature branch
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Branch:** `feature/PROJ-XXX-short-description`
    - **Notes:**

- [ ] **Task 8.2:** Commit changes with clear messages
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Commits:**
        - [ ] `feat(api): add POST /transactions endpoint [PROJ-XXX]`
        - [ ] `test(api): add integration tests for transactions [PROJ-XXX]`
        - [ ] `docs(api): update OpenAPI spec [PROJ-XXX]`
    - **Notes:**

- [ ] **Task 8.3:** Push branch and create GitLab MR
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **MR Link:** [URL]
    - **Notes:**

- [ ] **Task 8.4:** Fill out MR template completely
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Sections Completed:**
        - [ ] Summary
        - [ ] Acceptance criteria coverage
        - [ ] Testing evidence
        - [ ] Security checklist
    - **Notes:**

- [ ] **Task 8.5:** Verify GitLab CI pipeline passes
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Pipeline Status:**
        - [ ] Build: ✅
        - [ ] Unit tests: ✅
        - [ ] Integration tests: ✅
        - [ ] Security scan: ✅
    - **Notes:**

- [ ] **Task 8.6:** Address CI failures (if any)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Issues:**
        - [ ] Issue 1 → [Resolution]
    - **Notes:**

---

### Phase 9: Code Review & Iteration

- [ ] **Task 9.1:** Request code review from team
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Reviewers:** [Name1, Name2]
    - **Notes:**

- [ ] **Task 9.2:** Address review comments
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Comments:**
        - [ ] Comment 1 → [Resolution]
        - [ ] Comment 2 → [Resolution]
    - **Notes:**

- [ ] **Task 9.3:** Obtain approval from reviewers
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Approvals:**
        - [ ] Reviewer 1: ✅
        - [ ] Reviewer 2: ✅
    - **Notes:**

---

### Phase 10: Deployment & Verification

- [ ] **Task 10.1:** Merge MR to main branch
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Merged:** [YYYY-MM-DD HH:MM]
    - **Notes:**

- [ ] **Task 10.2:** Verify deployment to dev environment via ArgoCD
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **ArgoCD Status:** [Synced | Healthy]
    - **Notes:**

- [ ] **Task 10.3:** Run smoke tests in dev environment
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Tests:**
        - [ ] API endpoint accessible
        - [ ] Happy path works
        - [ ] Error handling works
    - **Notes:**

- [ ] **Task 10.4:** Verify logs and metrics in dev
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Checks:**
        - [ ] No errors in logs
        - [ ] Metrics being emitted
        - [ ] No PII in logs
    - **Notes:**

- [ ] **Task 10.5:** Hand off to QA for testing
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **QA Environment:** [dev | test]
    - **Test Evidence Link:** [URL]
    - **Notes:**

---

### Phase 11: QA & Sign-off

- [ ] **Task 11.1:** Support QA during testing
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Issues Found:** [X]
    - **Notes:**

- [ ] **Task 11.2:** Fix defects found by QA
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Defects:**
        - [ ] Defect 1 → [Resolution]
    - **Notes:**

- [ ] **Task 11.3:** Obtain QA sign-off
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **QA Approved:** [YYYY-MM-DD]
    - **Notes:**

- [ ] **Task 11.4:** Obtain security review (if required)
    - **Estimated:** [Xh]
    - **Actual:** [Xh]
    - **Security Approved:** [YYYY-MM-DD]
    - **Notes:**

---

### Phase 12: Production Readiness

- [ ] **Task 12.1:** Update Jira story status to "Ready for Production"
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Notes:**

- [ ] **Task 12.2:** Prepare deployment notes and rollback plan
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Rollback Plan:** [Brief description]
    - **Notes:**

- [ ] **Task 12.3:** Coordinate with ops for production deployment
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Deployment Window:** [YYYY-MM-DD HH:MM]
    - **Notes:**

- [ ] **Task 12.4:** Monitor production deployment
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Deployment Status:** [Success | Rolled Back]
    - **Notes:**

- [ ] **Task 12.5:** Verify in production (smoke tests)
    - **Estimated:** [1h]
    - **Actual:** [Xh]
    - **Tests:**
        - [ ] API endpoint accessible
        - [ ] Happy path works
        - [ ] Metrics and logs healthy
    - **Notes:**

- [ ] **Task 12.6:** Update Jira story to "Done"
    - **Estimated:** [0.5h]
    - **Actual:** [Xh]
    - **Completed:** [YYYY-MM-DD]
    - **Notes:**

---

## Summary

**Total Estimated Effort:** [Xh]  
**Total Actual Effort:** [Xh]  
**Variance:** [+/- Xh]

**Key Learnings:**
- [Learning 1]
- [Learning 2]

**Blockers Encountered:**
- [Blocker 1 and resolution]

**AI Assistance Used:**
- [Prompt 1: Generated code skeletons]
- [Prompt 2: Generated test cases]
- [Prompt 3: Pre-reviewed MR]

---

## Links

- **Jira Story:** [PROJ-XXX](https://jira.example.com/browse/PROJ-XXX)
- **GitLab MR:** [!123](https://gitlab.example.com/project/merge_requests/123)
- **OpenAPI Spec:** [Link](https://gitlab.example.com/.../docs/api/service-api.yaml)
- **ArgoCD Application:** [Link](https://argocd.example.com/applications/service-name)