# AI Governance Framework

A practical starting framework for governing AI systems across their lifecycle.

> This framework is a portfolio artifact and learning resource, not legal advice or a substitute for an organization's formal compliance program.

## 1. Governance Objectives

An AI governance program should help an organization:

1. Understand where AI is being used.
2. Identify and prioritize AI-related risks.
3. Assign clear accountability.
4. Establish proportionate controls.
5. Monitor systems after deployment.
6. Provide evidence for review, audit, and improvement.

## 2. AI Lifecycle

**Idea → Assessment → Design → Development → Validation → Deployment → Monitoring → Review / Retirement**

Governance should be present throughout the lifecycle rather than introduced only after deployment.

## 3. Core Governance Domains

| Domain | Key Question | Example Evidence |
|---|---|---|
| Purpose & Scope | Why does the AI system exist? | Use-case statement |
| Risk | What could go wrong? | Risk assessment |
| Accountability | Who owns the system and its outcomes? | RACI / ownership record |
| Data | Is the data appropriate and governed? | Data inventory |
| Security | Can the system be abused or compromised? | Security assessment |
| Privacy | Could personal or sensitive data be affected? | Privacy assessment |
| Fairness | Could outcomes create unjustified disparities? | Evaluation results |
| Transparency | Can relevant stakeholders understand the system? | System documentation |
| Human Oversight | When must a human intervene? | Escalation procedure |
| Monitoring | How will performance and risk be tracked? | Monitoring plan |
| Incident Management | What happens when something goes wrong? | Incident response plan |

## 4. Risk Classification

Use a simple proportional model as a starting point:

### Low Risk

Limited impact, low autonomy, and readily reversible outcomes.

**Typical controls:** basic documentation, owner assignment, monitoring.

### Moderate Risk

Meaningful operational, financial, reputational, or user impact.

**Typical controls:** formal risk assessment, validation, human oversight, security/privacy review, monitoring thresholds.

### High Risk

Potential for significant harm, sensitive decisions, substantial autonomy, or difficult-to-reverse consequences.

**Typical controls:** enhanced review, documented approval, stronger testing, explicit human oversight, incident procedures, continuous monitoring, and periodic governance review.

## 5. Minimum AI System Record

Every governed AI system should have a basic record containing:

- System name
- Business owner
- Technical owner
- Purpose and intended use
- Users and affected stakeholders
- Data sources
- Models / AI components
- External providers or dependencies
- Risk classification
- Known limitations
- Security considerations
- Privacy considerations
- Human oversight requirements
- Monitoring metrics
- Incident escalation path
- Review date

## 6. Governance Decision Gate

Before deployment, ask:

- Is the intended use clearly defined?
- Has the risk been assessed?
- Are responsibilities assigned?
- Are security and privacy risks understood?
- Has the system been appropriately tested?
- Are limitations documented?
- Is human oversight adequate for the risk level?
- Are monitoring and incident processes ready?
- Is there evidence supporting the deployment decision?

## 7. Continuous Monitoring

Governance does not end at deployment. Monitor for:

- Performance degradation
- Unexpected behavior
- Safety or security incidents
- Data drift or changes in inputs
- Changes in the operating environment
- User complaints or escalation patterns
- Material changes to models, prompts, tools, or dependencies

## 8. Governance Principle

**The level of governance should be proportional to the potential impact and risk of the AI system.**

The objective is not to prevent innovation. It is to create enough visibility, accountability, and control to enable responsible innovation.
