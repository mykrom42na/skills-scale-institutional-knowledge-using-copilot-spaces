# OctoAcme — Role Collaboration & Handoff Checklist

## Purpose
Ensure smooth collaboration and clear handoffs between roles throughout the project lifecycle. Use these checklists to clarify expectations, coordinate work, and maintain accountability.

---

## New Team Member Onboarding Checklist

When a new team member joins the project:

- [ ] Project Manager introduces new member to the team and project context
- [ ] Share access to project documentation (README, project charter, docs/ folder)
- [ ] Add to relevant communication channels (Slack, Teams, email lists)
- [ ] Review role-specific responsibilities from octoacme-roles-and-personas.md
- [ ] Introduce key stakeholders and collaborators from other roles
- [ ] Share current sprint/iteration goals and upcoming milestones
- [ ] Set up necessary tools and permissions (repo access, project board, CI/CD)
- [ ] Schedule 1:1 check-ins for first two weeks

---

## Role-to-Role Handoff Checklists

### Product Manager → UX Designer Handoff

When starting design work on a new feature:

- [ ] Product Manager shares problem statement and user needs
- [ ] Success metrics and business goals communicated
- [ ] Target user personas or segments identified
- [ ] Technical constraints and feasibility considerations discussed
- [ ] Timeline and design milestone expectations set
- [ ] Stakeholder review process agreed upon
- [ ] UX Designer confirms understanding and asks clarifying questions

### UX Designer → Developer Handoff

When handing off designs for implementation:

- [ ] Final designs and prototypes shared in accessible format
- [ ] Design system components and patterns referenced
- [ ] Interactive states and edge cases documented
- [ ] Accessibility requirements specified
- [ ] Responsive behavior and breakpoints defined
- [ ] Assets (icons, images, fonts) provided
- [ ] UX Designer available for implementation questions
- [ ] Review process for implementation fidelity agreed upon

### Developer → QA Lead Handoff

When feature is ready for testing:

- [ ] Pull request created with clear description and acceptance criteria
- [ ] Unit tests written and passing
- [ ] Test data or test account setup instructions provided
- [ ] Known limitations or edge cases documented
- [ ] Environment or configuration requirements specified
- [ ] Demo or walkthrough scheduled if needed
- [ ] QA Lead confirms testability of acceptance criteria
- [ ] Bug reporting and triage process confirmed

### QA Lead → DevOps Engineer Handoff

When preparing for deployment:

- [ ] All acceptance criteria validated and signed off
- [ ] Test results and coverage metrics shared
- [ ] Known issues or limitations documented
- [ ] Deployment verification test plan provided
- [ ] Rollback criteria defined
- [ ] Monitoring and alerting requirements specified
- [ ] DevOps Engineer confirms deployment readiness
- [ ] Post-deployment smoke test checklist agreed upon

### Business Analyst → Product Manager Handoff

When completing requirements analysis:

- [ ] Requirements documentation finalized and reviewed
- [ ] Data analysis and business case completed
- [ ] Success metrics and KPIs defined
- [ ] Compliance or regulatory requirements identified
- [ ] Stakeholder sign-off obtained
- [ ] User stories or backlog items created
- [ ] Product Manager confirms alignment with product vision
- [ ] Open questions or risks escalated

---

## Cross-Role Communication Checklist

### Sprint Planning Preparation

Roles should prepare the following before sprint planning:

- **Product Manager**:
  - [ ] Prioritized backlog with clear acceptance criteria
  - [ ] Business value and context for each item
  
- **UX Designer**:
  - [ ] Design assets ready for in-scope work
  - [ ] Design effort estimates for new design work
  
- **QA Lead**:
  - [ ] Test plan or testing approach for complex features
  - [ ] Testing capacity and effort estimates
  
- **DevOps Engineer**:
  - [ ] Infrastructure dependencies identified
  - [ ] Deployment or environment concerns flagged
  
- **Business Analyst**:
  - [ ] Requirements clarifications documented
  - [ ] Data or analytics needs specified

### Release Readiness Review

Before each release, coordinate across roles:

- [ ] **Product Manager**: Release notes drafted, stakeholder communication plan ready
- [ ] **QA Lead**: All tests passing, quality signoff provided, known issues documented
- [ ] **DevOps Engineer**: Deployment plan reviewed, monitoring configured, rollback plan ready
- [ ] **UX Designer**: UI implementation reviewed and approved, accessibility validated
- [ ] **Business Analyst**: Success metrics tracking confirmed, compliance checks complete
- [ ] **Developers**: Code freeze respected, production hotfix process reviewed
- [ ] **Project Manager**: Release timeline communicated, stakeholders notified

### Retrospective Participation

All roles should contribute to retrospectives:

- [ ] Each role reflects on what went well
- [ ] Each role identifies improvement opportunities
- [ ] Cross-role collaboration pain points discussed
- [ ] Action items assigned with clear owners
- [ ] Follow-up on previous retrospective actions reviewed

---

## Best Practices for Role Collaboration

### Clear Communication
- Use shared terminology from project documentation
- Document decisions and share with affected roles
- Escalate blockers early to Project Manager
- Over-communicate rather than assume alignment

### Defined Touchpoints
- Establish regular sync meetings between frequently collaborating roles
- Create clear handoff points with documented expectations
- Use project board status updates to keep everyone informed
- Tag relevant roles in PR descriptions and comments

### Accountability & Ownership
- Each role owns their deliverables per octoacme-roles-and-personas.md
- Clarify who has final decision authority for each type of decision
- Document agreements in decision logs when trade-offs are made
- Follow through on commitments made during handoffs

### Feedback Loops
- Request feedback early and often from collaborating roles
- Create safe space for constructive feedback
- Act on feedback or explain why alternative approach is chosen
- Celebrate successful collaborations and teamwork

---

## Usage Notes

- Adapt these checklists to your project's specific needs
- Store completed checklists in project documentation for reference
- Review and refine checklists during retrospectives
- Use these as templates in project management tools (GitHub Issues, Jira, etc.)
