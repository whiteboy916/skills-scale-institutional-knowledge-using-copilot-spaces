# Role Interaction Matrix

This matrix shows how different personas collaborate across project phases and workflows. Use this to understand responsibilities, communication patterns, and decision-making authority at each stage.

## Legend
- **D** = Decision maker or approver
- **C** = Contributor or executor
- **I** = Informed or consulted
- **R** = Responsible for tracking/reporting
- **—** = Not typically involved

---

## Project Initiation Phase

| Phase Activity | Product Manager | Project Manager | Developer | QA Lead | Release Manager | Technical Architect | Stakeholder Rep | Documentation Specialist | Risk Manager |
|---|---|---|---|---|---|---|---|---|---|
| Define business requirements | D | C | I | I | — | I | D | — | I |
| Clarify scope and constraints | C | D | C | I | — | C | C | — | I |
| Identify project risks | I | C | I | I | I | I | C | — | D |
| Estimate effort and timeline | I | C | C | C | C | C | I | I | I |
| Stakeholder kickoff | C | C | — | — | — | — | D | C | I |
| Establish success metrics | D | C | — | I | — | — | C | C | — |

---

## Project Planning Phase

| Phase Activity | Product Manager | Project Manager | Developer | QA Lead | Release Manager | Technical Architect | Stakeholder Rep | Documentation Specialist | Risk Manager |
|---|---|---|---|---|---|---|---|---|---|
| Define acceptance criteria | D | C | C | C | — | I | I | — | — |
| Create testing strategy | I | I | C | D | — | I | — | — | — |
| Develop technical design | I | I | C | I | — | D | — | C | I |
| Plan release strategy | I | D | I | I | D | C | I | I | C |
| Define dependencies | C | D | C | I | C | C | I | — | I |
| Create risk mitigation plans | I | C | I | I | C | I | I | — | D |
| Establish communication plan | C | D | I | I | I | I | C | C | I |

---

## Execution Phase

| Phase Activity | Product Manager | Project Manager | Developer | QA Lead | Release Manager | Technical Architect | Stakeholder Rep | Documentation Specialist | Risk Manager |
|---|---|---|---|---|---|---|---|---|---|
| Implement features | — | I | C | — | — | I | — | — | — |
| Code reviews | — | — | C | I | — | I | — | — | — |
| Execute test plans | — | I | I | D | — | I | — | — | — |
| Log and track defects | — | C | C | C | — | I | — | — | — |
| Resolve blockers | C | D | C | I | — | I | — | — | I |
| Daily standups | — | D | C | I | — | — | — | — | — |
| Document technical specs | I | I | C | I | — | D | — | C | — |
| Monitor project risks | I | R | I | I | I | I | I | — | D |

---

## Testing & QA Phase

| Phase Activity | Product Manager | Project Manager | Developer | QA Lead | Release Manager | Technical Architect | Stakeholder Rep | Documentation Specialist | Risk Manager |
|---|---|---|---|---|---|---|---|---|---|
| Develop test cases | I | I | C | D | — | I | — | — | — |
| Execute regression testing | — | I | I | D | — | — | — | — | — |
| Perform performance testing | — | I | I | D | I | C | — | — | — |
| Verify bug fixes | — | I | C | D | — | I | — | — | — |
| Quality gate approval | I | I | I | D | C | — | — | — | — |
| Create release notes | I | I | I | I | D | I | — | D | — |

---

## Release & Deployment Phase

| Phase Activity | Product Manager | Project Manager | Developer | QA Lead | Release Manager | Technical Architect | Stakeholder Rep | Documentation Specialist | Risk Manager |
|---|---|---|---|---|---|---|---|---|---|
| Prepare deployment plan | I | C | C | I | D | C | — | C | C |
| Conduct deployment readiness review | I | C | C | C | D | C | I | I | I |
| Execute deployment | — | I | I | I | D | C | — | — | I |
| Monitor post-deployment | — | I | I | I | D | C | — | — | I |
| Perform smoke tests | — | I | I | I | D | — | — | — | — |
| Execute rollback (if needed) | — | I | I | I | D | C | — | — | I |
| Communicate release to stakeholders | C | C | — | — | C | — | D | — | — |
| Deploy user documentation | I | — | — | — | — | — | I | D | — |

---

## Post-Release & Continuous Improvement

| Phase Activity | Product Manager | Project Manager | Developer | QA Lead | Release Manager | Technical Architect | Stakeholder Rep | Documentation Specialist | Risk Manager |
|---|---|---|---|---|---|---|---|---|---|
| Monitor production metrics | I | I | I | I | D | — | C | — | I |
| Gather stakeholder feedback | D | I | — | — | — | — | C | I | — |
| Conduct retrospective | C | D | C | C | C | C | I | C | C |
| Document lessons learned | I | C | C | I | I | I | — | D | — |
| Update process documentation | I | C | — | — | — | I | — | D | I |
| Assess continuous improvement opportunities | I | D | I | I | — | I | I | — | C |

---

## Key Principles

1. **Collaboration Over Isolation**: Personas work together across phases, not in silos
2. **Clear Decision Authority**: Each activity has a clear decision maker (D)
3. **Accountability**: Owners track and report progress (R)
4. **Cross-functional Input**: Multiple perspectives inform decisions
5. **Risk Awareness**: Risk Manager is consulted early and throughout
6. **Documentation**: Documentation Specialist ensures knowledge capture

---

## How to Use This Matrix

1. **Planning**: Use this matrix when planning project activities to assign roles and responsibilities
2. **Meetings**: Reference this matrix when determining who should attend meetings or reviews
3. **Decision Making**: Use this to understand who has authority on specific decisions
4. **Onboarding**: Help new team members understand their involvement in various activities
5. **Process Improvement**: Identify gaps or excessive involvement that could be streamlined

For more information on each persona, see `docs/octoacme-roles-and-personas.md`.
