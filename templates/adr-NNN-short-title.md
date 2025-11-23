# ADR-NNN: [Short Decision Title]

**Status:** [Proposed | Accepted | Deprecated | Superseded by ADR-XXX]  
**Date:** [YYYY-MM-DD]  
**Deciders:** [Names or roles: Architect, Tech Lead, Security]  
**Jira Epic/Story:** [PROJ-XXX]

---

## Context

[Describe the problem, requirement, or architectural question that needs a decision.  
Include relevant business context, technical constraints, and NFRs.]

**Key Drivers:**
- [Driver 1: e.g., "Must support 10k TPS"]
- [Driver 2: e.g., "Must comply with data residency requirements"]
- [Driver 3: e.g., "Team has limited experience with technology X"]

---

## Decision

[State the decision clearly and concisely.]

**We will:** [e.g., "Use Kafka for event streaming between payment-service and notification-service"]

---

## Options Considered

### Option 1: [Name]
**Pros:**
- [Pro 1]
- [Pro 2]

**Cons:**
- [Con 1]
- [Con 2]

**Alignment with NFRs:** [Brief assessment]

---

### Option 2: [Name]
**Pros:**
- [Pro 1]
- [Pro 2]

**Cons:**
- [Con 1]
- [Con 2]

**Alignment with NFRs:** [Brief assessment]

---

### Option 3: [Name] *(Selected)*
**Pros:**
- [Pro 1]
- [Pro 2]

**Cons:**
- [Con 1]
- [Con 2]

**Alignment with NFRs:** [Brief assessment]

**Why this option:**  
[Rationale for selection, including trade-offs accepted.]

---

## Consequences

### Positive
- [Consequence 1: e.g., "Improved scalability"]
- [Consequence 2: e.g., "Aligns with existing platform standards"]

### Negative
- [Consequence 1: e.g., "Increased operational complexity"]
- [Consequence 2: e.g., "Requires team training"]

### Neutral
- [Consequence 1: e.g., "No impact on existing services"]

---

## Implementation Notes

**Key Components:**
- [Component 1: e.g., "Kafka cluster in production VPC"]
- [Component 2: e.g., "Schema registry for event schemas"]

**Migration/Rollout Plan:**  
[e.g., "Phase 1: Deploy Kafka; Phase 2: Migrate payment-service; Phase 3: Migrate notification-service"]

**Risks & Mitigations:**
- **Risk 1:** [e.g., "Kafka cluster failure"] → **Mitigation:** [e.g., "Multi-AZ deployment + monitoring"]
- **Risk 2:** [e.g., "Schema evolution issues"] → **Mitigation:** [e.g., "Use schema registry with compatibility checks"]

---

## AI-Assisted Design Notes

**Agent Prompts Used:**
- "Propose architecture options for event streaming between services with these NFRs: [list]"
- "Compare Kafka vs RabbitMQ vs AWS SNS/SQS for this use case"
- "Generate pros/cons and risk analysis for each option"

**Agent Contributions:**
- [e.g., "Agent identified schema evolution as a key risk"]
- [e.g., "Agent suggested multi-AZ deployment pattern"]

---

## References

- **Jira Epic:** [PROJ-XXX]
- **OpenAPI Spec:** [Link]
- **Related ADRs:** [ADR-001, ADR-045]
- **External References:** [Links to vendor docs, RFCs, internal standards]

---

## Review & Approval

| Role | Name | Date | Status |
|------|------|------|--------|
| Architect | [Name] | [YYYY-MM-DD] | ✅ Approved |
| Tech Lead | [Name] | [YYYY-MM-DD] | ✅ Approved |
| Security | [Name] | [YYYY-MM-DD] | ✅ Approved |
| Compliance | [Name] | [YYYY-MM-DD] | ✅ Approved |

