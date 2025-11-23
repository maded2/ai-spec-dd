# ai-spec-dd

This repository contains templates and prompts for AI-assisted software development and documentation. It's designed to help with creating structured specifications, epics, stories, and development plans using AI assistance.

## Prompts

The `prompts/` directory contains various AI prompts for different purposes:

### create_epic_prompt.txt
This prompt is designed for business analysts working in banking environments to help decompose high-level requirements into coherent Jira Epics. The prompt:

1. Asks for clarifying questions about ambiguous or incomplete requirements
2. Decomposes requirements into a set of Jira Epics
3. Generates markdown content using a standardized template
4. Provides machine-readable output that can be saved as distinct markdown files

#### Usage
The prompt follows a three-pass approach:
1. **Understanding & Clarification**: Identifies ambiguities and asks clarifying questions
2. **Epic breakdown**: Proposes candidate Epics with names, descriptions, and rationales
3. **Content generation**: Creates detailed Epic markdown files using the standard template

Each Epic is output in a machine-readable format:
```
FILE_NAME: epic-<short-kebab-slug>.md
CONTENT_START
# Epic: <Title>
...rest of the epic template content in markdown...
CONTENT_END
```

This allows external systems to parse and save each Epic as a separate markdown file.

### create_story_prompt.txt
This prompt helps business analysts create detailed Jira Stories based on Epic requirements. It uses a comprehensive template that includes:

- Business context and goals
- High-level scope (In Scope/Out of Scope)
- Key constraints and dependencies
- Non-functional requirements in table format
- AI-assisted refinement notes
- Links and attachments section
- Acceptance criteria

#### Usage
The prompt takes raw business input and fills out the entire Epic template with concrete, realistic content. It asks for:
- Business goal and key drivers
- Impacted areas and constraints
- Regulatory context and timeframe
- Business owner and technical lead information

The output is a completed Jira Epic in markdown format, ready to be used in Jira or Confluence. The prompt ensures that all sections are filled with appropriate banking/financial terminology and realistic requirements for a Tier-1 banking environment.

### create_implementation_tasks_prompt.txt
This prompt assists system analysts and senior developers in creating detailed implementation task lists from Jira Stories. It generates actionable tasks following the team's conventions for a Jira + GitLab + ArgoCD toolchain.

The prompt generates a complete implementation task list that includes:

- Analysis, implementation, testing, and deployment phases
- Realistic effort estimates in hours
- Banking-specific considerations (security, compliance, observability)
- Team conventions for branching, commits, and code review
- Actionable tasks organized in logical order

#### Usage
The prompt takes a Jira Story as input and creates a detailed task list following these conventions:
- Branch naming: feature/PROJ-XXX-short-description
- Commit message format: type(scope): description [PROJ-XXX]
- Test coverage target: ≥80%
- Code review: Minimum 2 approvals

The output is a complete implementation task list in markdown format, ready to be saved as PROJ-XXX-implementation-tasks.md and used for tracking implementation progress. Each task is actionable and includes placeholders for actual time and links that will be filled during execution.
