# Release Readiness Checklist

This checklist ensures releases are well-coordinated, tested, and communicated across all teams. Use this template for each release to validate readiness before deployment.

**Release Name/Version:** ________________  
**Scheduled Deployment Date:** ________________  
**Release Manager:** ________________

---

## Product & Planning (PM / Product Manager)

- [ ] **Acceptance Criteria Met**: All features and fixes meet documented acceptance criteria
- [ ] **Backlog Closure**: All planned work for this release is complete (or explicitly deferred)
- [ ] **Stakeholder Sign-Off**: Key stakeholders have reviewed and approved release scope
- [ ] **Release Notes Draft**: Release notes are drafted with customer-facing value propositions
- [ ] **Go/No-Go Decision**: PM has confirmed go/no-go decision with team

---

## Development & Quality (Developers / QA)

- [ ] **Code Review Complete**: All PRs are reviewed and approved
- [ ] **Test Coverage**: Automated tests pass; no critical bugs remain
- [ ] **Integration Testing**: Cross-team integration points have been tested
- [ ] **Performance Validation**: Load tests or performance benchmarks have been run
- [ ] **Smoke Tests Defined**: Post-deployment smoke tests are documented and ready
- [ ] **Known Issues Logged**: Any known limitations or deferred fixes are documented

---

## Security & Compliance (Security Liaison)

- [ ] **Security Review Complete**: New features have passed security review
- [ ] **Vulnerability Scan**: Code and dependencies pass security scanning
- [ ] **Compliance Check**: Changes comply with regulatory or organizational standards
- [ ] **Data Privacy**: Any data handling changes have been reviewed for privacy impact
- [ ] **Security Sign-Off**: Security team confirms readiness to deploy

---

## Operations & Reliability (SRE / Release Manager)

- [ ] **Deployment Plan**: Deployment steps, rollback procedure, and runbook are documented
- [ ] **Monitoring & Alerts**: Dashboards and alerts are configured for the release
- [ ] **SLO/SLI Baseline**: Current SLOs/SLIs are documented for comparison
- [ ] **Incident Playbook**: Incident response procedure is prepared and communicated
- [ ] **Rollback Plan**: Clear rollback procedure is tested and ready
- [ ] **Infrastructure Ready**: Servers, databases, or infrastructure changes are deployed
- [ ] **Load Capacity**: Expected load has been assessed; capacity is confirmed

---

## Communication & Stakeholder Readiness

- [ ] **Stakeholder Notification**: Key stakeholders are notified of release date and impact
- [ ] **Customer Communication**: Release notes and customer announcements are ready
- [ ] **Internal Communication**: Team and support staff are briefed on changes
- [ ] **Documentation Updated**: Help docs, FAQs, or runbooks are updated
- [ ] **Support Team Ready**: Support team is trained on new features and known issues

---

## Release Day Coordination (Release Manager)

- [ ] **Deployment Window Confirmed**: Date and time confirmed with all teams
- [ ] **On-Call Schedule**: SRE and support on-call coverage is confirmed
- [ ] **Pre-Deployment Sync**: All teams participate in pre-deployment readiness sync
- [ ] **Deployment Execution**: Release is deployed per plan
- [ ] **Post-Deployment Verification**: Smoke tests and sanity checks pass
- [ ] **Stakeholder Communication**: Release status and results communicated
- [ ] **Incident Log**: Any issues encountered are logged for post-mortem

---

## Post-Release (Analytics / Product Manager)

- [ ] **Success Metrics Tracked**: KPIs and success metrics are being monitored
- [ ] **Error Rates Monitored**: No unexpected error spikes or regressions observed
- [ ] **Performance Verified**: Performance metrics are in line with expectations
- [ ] **User Feedback Collected**: Early user feedback is being gathered
- [ ] **Retrospective Scheduled**: Team retrospective is scheduled to capture learnings

---

## Sign-Off

| Role | Name | Date | Signature |
|------|------|------|-----------|
| Product Manager | | | |
| Project Manager | | | |
| Release Manager | | | |
| SRE / Tech Lead | | | |
| Security Lead | | | |

---

## Release Notes Template

```
## Release [Version] - [Date]

### New Features
- [Feature 1]: Brief description of customer value
- [Feature 2]: Brief description of customer value

### Improvements
- [Improvement 1]: How this improves user/team experience
- [Improvement 2]: How this improves user/team experience

### Bug Fixes
- [Bug Fix 1]: What was broken and is now fixed
- [Bug Fix 2]: What was broken and is now fixed

### Known Issues
- [Issue 1]: Workaround or planned fix date
- [Issue 2]: Workaround or planned fix date

### Deployment Details
- Deployment Date: [Date]
- Estimated Downtime: [Time or "None"]
- Rollback Plan: [Brief description or link]

### Questions or Support
Contact [Support Email] or [Support Channel]
```
