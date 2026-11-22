# Project Maintenance Policy

<div align="center">

### Building software is only the beginning.
### Maintaining it is a commitment.

A framework for sustainable project ownership, maintainership and long-term development within NITM-SOSC.

</div>

---

## 01 / Purpose

NITM-SOSC encourages students to initiate, develop and maintain open-source software collaboratively.

However, a project should not become inactive simply because its original developer graduates, changes interests or becomes unavailable.

This policy establishes a common framework for:

- Project ownership and responsibilities.
- Appointment of project maintainers.
- Repository access and permissions.
- Contribution review and approval.
- Releases and documentation.
- Security and issue management.
- Maintainer transitions and project handovers.
- Archiving and discontinuation of projects.

Our objective is to build software that remains useful, accessible and maintainable beyond individual academic batches.

---

## 02 / Project Principles

Every project maintained under NITM-SOSC should follow these principles.

**Open Collaboration**

Projects should encourage contributions from interested community members.

**Transparent Development**

Development decisions, issues, changes and releases should be documented appropriately.

**Shared Responsibility**

Projects should avoid unnecessary dependence on a single developer.

**Sustainable Maintenance**

Projects should have realistic maintenance expectations and documented handover procedures.

**Responsible Development**

Security, licensing, documentation and software quality should be considered throughout the project lifecycle.

---

## 03 / Project Roles and Responsibilities

Different projects may require different organisational structures.

The following roles provide a recommended framework.

### Project Lead

The Project Lead coordinates the overall development of a project.

Responsibilities:

- Define project objectives and priorities.
- Coordinate contributors.
- Maintain the development roadmap.
- Communicate project progress.
- Identify and support potential maintainers.
- Coordinate major architectural decisions.

A Project Lead does not automatically receive unrestricted administrative authority over the entire organisation.

### Project Maintainer

Maintainers are responsible for the ongoing health of a project.

Responsibilities:

- Review and manage Pull Requests.
- Triage issues and bug reports.
- Maintain project documentation.
- Ensure changes follow project standards.
- Coordinate releases.
- Address maintenance and security concerns.
- Support contributors.
- Communicate important project decisions.

### Contributors

Contributors participate in project development.

They may:

- Implement features.
- Fix bugs.
- Improve documentation.
- Write tests.
- Review proposed changes.
- Suggest improvements.
- Participate in technical discussions.

Contributors do not automatically receive repository write permissions.

### Community Maintainers

Community Maintainers oversee the broader NITM-SOSC ecosystem.

Responsibilities include:

- Maintaining organisational standards.
- Supporting project continuity.
- Helping resolve cross-project issues.
- Facilitating maintainer transitions.
- Reviewing significant governance concerns.
- Ensuring projects follow applicable community policies.

---

## 04 / Project Initiation and Adoption

Projects intended to be maintained under NITM-SOSC should have a documented purpose and a clear maintenance arrangement.

Before a project becomes an established community project, it should ideally have:

- A project description.
- A defined problem statement.
- A proposed solution.
- An identified Project Lead.
- An initial contributor team.
- A development plan.
- An appropriate open-source licence.
- A README and contribution guidelines.
- A realistic maintenance plan.

Project proposals should follow the community's project proposal process.

Projects may begin as experimental initiatives and develop into maintained community projects as they mature.

Acceptance into the organisation does not automatically imply institutional ownership, sponsorship or endorsement by NIT Manipur.

---

## 05 / Appointment of Maintainers

Project maintainers should be selected based on demonstrated responsibility, technical understanding and willingness to maintain the project.

Relevant considerations include:

- Understanding of the project's architecture.
- Quality of previous contributions.
- Ability to review code.
- Communication and collaboration.
- Commitment to documentation.
- Awareness of security and software maintenance.
- Availability for ongoing responsibilities.

### Appointment Process

1. An existing maintainer identifies a suitable candidate or receives a nomination.
2. The candidate's contributions and readiness are evaluated.
3. The existing project maintainers discuss the appointment.
4. The appointment is documented.
5. Appropriate GitHub permissions are granted.

For new projects without existing maintainers, the founding team may recommend the initial Project Lead and maintainers, subject to the applicable community governance process.

Maintainer appointments should be transparent and documented.

---

## 06 / Repository Access and Permissions

Repository permissions should follow the principle of least privilege.

Not every contributor requires write access.

Recommended arrangements:

| Role | Suggested access |
|---|---|
| Community visitor | Public read access |
| Contributor | Fork and Pull Request workflow |
| Trusted collaborator | Access appropriate to assigned responsibilities |
| Project maintainer | Repository maintenance permissions |
| Project administrator | Administrative permissions when necessary |

Administrative permissions should be restricted to trusted individuals who genuinely require them.

Where possible:

- Use GitHub Teams to manage access.
- Enable two-factor authentication.
- Avoid sharing account credentials.
- Review repository permissions periodically.
- Remove unnecessary access when responsibilities change.
- Protect important branches and require appropriate reviews.

No individual should receive organisation-wide administrative access simply because they maintain one project.

---

## 07 / Development and Code Review

Projects should maintain a consistent development workflow.

Recommended practices:

- Use GitHub Issues to track work.
- Use separate branches for development.
- Submit changes through Pull Requests.
- Review code before merging.
- Run relevant tests and automated checks.
- Document significant architectural decisions.
- Keep dependencies reasonably maintained.
- Avoid committing secrets or credentials.

### Pull Request Review

Maintainers should review contributions based on:

- Correctness.
- Readability.
- Maintainability.
- Security implications.
- Compatibility.
- Testing.
- Project requirements.

Contributors should receive constructive and actionable feedback.

For important changes, projects should avoid relying on a single person's unreviewed decisions wherever practical.

---

## 08 / Documentation and Project Health

Every maintained project should provide sufficient documentation for new contributors to understand and work with it.

Recommended repository files include:

| File | Purpose |
|---|---|
| `README.md` | Project overview and setup |
| `CONTRIBUTING.md` | Contribution instructions |
| `LICENSE` | Software licensing terms |
| `CODE_OF_CONDUCT.md` | Community behaviour |
| `SECURITY.md` | Security reporting |
| `CHANGELOG.md` | Important project changes |

Projects should periodically review:

- Open issues.
- Pending Pull Requests.
- Dependency updates.
- Documentation accuracy.
- Build and test status.
- Security advisories.
- Release history.

The level of maintenance should be appropriate to the project's complexity and usage.

---

## 09 / Releases and Versioning

Maintainers are responsible for coordinating project releases.

Where appropriate, projects should:

- Use meaningful version numbers.
- Maintain release notes.
- Document breaking changes.
- Identify important bug fixes.
- Tag stable releases.
- Communicate known limitations.

Projects may follow Semantic Versioning where it suits their release model.

Not every experimental project needs a formal release schedule.

---

## 10 / Security Responsibilities

Security must be considered throughout the project lifecycle.

Maintainers should:

- Protect repository credentials.
- Review sensitive changes carefully.
- Avoid committing private keys and API tokens.
- Keep important dependencies updated.
- Address reported vulnerabilities responsibly.
- Follow the applicable security reporting policy.
- Communicate relevant security updates.

Security vulnerabilities should not be disclosed through public issues before responsible investigation and remediation.

Refer to the organisation's [Security Policy](https://github.com/NITM-SOSC/.github/blob/main/SECURITY.md).

---

## 11 / Maintainer Inactivity

Academic commitments, internships, graduation and personal circumstances can affect a maintainer's availability.

NITM-SOSC recognises that participation is voluntary.

However, projects should have a process for addressing prolonged inactivity.

When a maintainer becomes unavailable:

1. The project team should attempt to establish communication.
2. Existing maintainers should review the project's maintenance requirements.
3. A suitable replacement may be identified.
4. Relevant responsibilities and access should be transferred.
5. The transition should be documented.

Temporary inactivity should not automatically result in the removal of a maintainer.

Changes to responsibilities should be handled transparently and respectfully.

---

## 12 / Project Handover and Graduation

Project continuity across graduating batches is a central priority of NITM-SOSC.

A departing Project Lead or Maintainer should make reasonable efforts to transfer relevant responsibilities.

### Recommended Handover Checklist

- [ ] Identify the incoming Project Lead or Maintainer.
- [ ] Document the current project architecture.
- [ ] Explain the development workflow.
- [ ] Transfer relevant repository responsibilities.
- [ ] Review outstanding issues and Pull Requests.
- [ ] Document unresolved bugs and technical debt.
- [ ] Explain deployment and release procedures.
- [ ] Transfer operational knowledge securely.
- [ ] Update maintainer information.
- [ ] Record the transition in project documentation.

Passwords, personal access tokens and private credentials must never be transferred informally. Access should be provisioned through appropriate account and permission management procedures.

Project maintainership is a responsibility that can be transferred.

Copyright ownership and licensing rights remain governed by the applicable licences and contributor agreements, not by this maintenance policy.

---

## 13 / Project Abandonment and Archival

Some projects may eventually become inactive or unnecessary.

Before archiving a project, maintainers should consider:

- Whether the project still serves a useful purpose.
- Whether another contributor is willing to maintain it.
- Whether outstanding security issues exist.
- Whether users depend on the software.
- Whether documentation needs updating.
- Whether an alternative project already exists.

### Archival Process

1. Discuss the project's status with its maintainers.
2. Communicate the proposed archival decision.
3. Provide an opportunity for another maintainer to take responsibility.
4. Document the project's final status.
5. Update the repository README.
6. Archive the repository when appropriate.

Archived projects should retain their historical contributions and documentation wherever possible.

Archiving a repository does not transfer or remove the underlying copyright or licensing rights.

---

## 14 / Disputes and Maintenance Decisions

Technical disagreements are a normal part of collaborative software development.

Maintainers should prioritise:

- Technical reasoning.
- Documented project objectives.
- Community contribution standards.
- Security and reliability.
- Constructive communication.

If a disagreement cannot be resolved within the project team, it may be referred to the appropriate Community Maintainers under the organisation's governance policy.

Individuals involved in a conflict of interest should not unilaterally decide the outcome.

---

## 15 / Transparency and Accountability

Projects should document important maintenance decisions.

Where appropriate, this includes:

- Maintainer appointments.
- Major architectural decisions.
- Significant project changes.
- Release decisions.
- Changes in project status.
- Project handovers.
- Archival decisions.

The purpose is not to create unnecessary administration, but to ensure that important project knowledge remains accessible.

---

## 16 / Policy Review

This policy may be revised as NITM-SOSC develops and adopts more mature project management practices.

Significant changes should follow the community's governance and decision-making procedures.

Project-specific requirements may supplement this policy where necessary, provided they do not conflict with applicable organisational policies.

---

## / Building Beyond Individual Contributors

A successful open-source project is not defined only by the person who created it.

It is defined by the people who continue to improve it, maintain it, document it and make it useful to others.

At NITM-SOSC, we want projects to outlive individual contributions and academic batches.

**Build something meaningful. Maintain it responsibly. Pass it forward.**

<div align="center">

### NITM-SOSC

**Learn Independently · Build Collaboratively · Contribute Globally**

<sub>An independent, student-led open-source community</sub>

<sub>National Institute of Technology Manipur · India</sub>

</div>
