## Summary

**Jira Story:** [PROJ-XXX - Story Title with link]  
**Epic:** [PROJ-YYY - Epic Title with link]

[1-2 sentence summary of what this MR does and why.]

---

## Changes Made

### Code Changes
- [Brief bullet: e.g., "Added POST /api/v1/transactions endpoint"]
- [Brief bullet: e.g., "Refactored TransactionService to handle edge case X"]
- [Brief bullet: e.g., "Updated error handling to return standardized error codes"]

### Configuration/Infrastructure Changes
- [e.g., "Updated k8s Deployment with new resource limits"]
- [e.g., "Added new environment variable for feature flag"]

### Database/Schema Changes
- [e.g., "Added migration V123__add_transaction_status_column.sql"]
- [None]

---

## Acceptance Criteria Coverage

| Acceptance Criterion | Implemented? | Test Coverage |
|----------------------|--------------|---------------|
| AC1: [Given/When/Then] | ✅ Yes | Unit + Integration |
| AC2: [Given/When/Then] | ✅ Yes | Unit |
| AC3: [Error scenario] | ✅ Yes | Unit |

---

## AI-Assisted Development Notes

**AI Pre-Review Completed:** [Yes/No]  
**Date:** [YYYY-MM-DD]

**Agent Prompts Used:**
- "Generate controller and service skeletons for this API spec"
- "Generate unit tests covering all acceptance criteria"
- "Review this diff for spec alignment and security issues"

**AI Findings Addressed:**
- [e.g., "Agent flagged potential null pointer in line 45 → fixed"]
- [e.g., "Agent suggested additional negative test case → added"]

---

## Testing

### Unit Tests
- [ ] New unit tests added
- [ ] All unit tests passing locally
- [ ] Coverage: [X]% (target ≥80%)

### Integration/API Tests
- [ ] New integration tests added
- [ ] All integration tests passing in CI

### Manual Testing
- [ ] Tested locally against dev environment
- [ ] Tested edge cases from Jira story
- [ ] Tested error scenarios

**Test Evidence:**  
[Link to test results, screenshots, or Postman collection]

---

## Security & Compliance

- [ ] No secrets or credentials hard-coded
- [ ] No PII or sensitive data logged
- [ ] Input validation implemented for all external inputs
- [ ] Authorization checks in place
- [ ] Security review completed (if required for this change)

**Security Notes:**  
[Any specific security considerations or mitigations]

---

## Non-Functional Requirements

- [ ] Performance: Tested under expected load, meets SLA
- [ ] Logging: Appropriate logs added (no sensitive data)
- [ ] Monitoring: Metrics/alerts configured if needed
- [ ] Error handling: Graceful degradation and user-friendly errors

---

## Deployment Notes

**Deployment Method:** [ArgoCD auto-sync / Manual sync / Canary]

**Rollback Plan:**  
[e.g., "Revert to previous image tag via ArgoCD; no DB migration rollback needed"]

**Feature Flags:**  
[e.g., "Feature behind flag `enable_new_transaction_flow` (default: false)"]

**Database Migrations:**  
[e.g., "Migration V123 is backward-compatible; safe to deploy"]

---

## Checklist (MR Author)

- [ ] Code follows team coding standards
- [ ] All acceptance criteria from Jira implemented
- [ ] Tests written and passing (unit + integration)
- [ ] AI pre-review completed and findings addressed
- [ ] No linting or build errors
- [ ] MR title and description are clear
- [ ] Jira story linked
- [ ] Ready for human code review

---

## Reviewer Checklist

- [ ] Code is clear, maintainable, and follows standards
- [ ] All acceptance criteria covered
- [ ] Tests are meaningful and sufficient
- [ ] No security or compliance issues
- [ ] NFRs addressed (performance, logging, monitoring)
- [ ] Deployment and rollback plan is sound

---

## Related Links

- **OpenAPI Spec:** [Link to openapi.yaml in repo]
- **ADR:** [Link to architecture decision record]
- **Confluence Spec:** [Link]
- **CI Pipeline:** [Link to GitLab CI job]

