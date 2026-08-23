# AI Risk Assessment Toolkit

A lightweight assessment template for evaluating AI systems before and during deployment.

> This is an educational portfolio artifact, not legal advice or a substitute for a formal enterprise risk methodology.

## Assessment Record

### 1. System Identification

- **System name:**
- **Business owner:**
- **Technical owner:**
- **Assessment date:**
- **Lifecycle stage:**
- **Intended use:**
- **Out-of-scope use:**

### 2. Stakeholder Impact

Identify who may use, operate, depend on, or be affected by the system.

- Direct users:
- Indirect users:
- Customers / citizens / employees affected:
- Internal teams affected:
- Third-party providers:

### 3. Risk Areas

Score each area from **1 (low)** to **5 (high)** based on the potential impact and likelihood.

| Risk Area | Impact | Likelihood | Score | Key Concern |
|---|---:|---:|---:|---|
| Safety / Harm |  |  |  |  |
| Security |  |  |  |  |
| Privacy |  |  |  |  |
| Fairness / Bias |  |  |  |  |
| Reliability |  |  |  |  |
| Transparency |  |  |  |  |
| Accountability |  |  |  |  |
| Legal / Regulatory |  |  |  |  |
| Reputational |  |  |  |  |
| Operational |  |  |  |  |

### 4. Risk Questions

#### Purpose

- Is the use case clearly defined?
- Is the intended outcome measurable?
- Could the system be used outside its approved purpose?

#### Data

- What data enters the system?
- Where does it originate?
- Is data quality sufficient?
- Could inappropriate or sensitive data be exposed?

#### Model / System

- What model or AI components are used?
- What are known limitations?
- Are outputs deterministic or variable?
- Are external models, APIs, agents, or tools involved?

#### Security

- Can users manipulate inputs to cause harmful behavior?
- Can the system access sensitive tools or data?
- Are permissions appropriately scoped?
- Is there logging and monitoring?

#### Human Oversight

- What decisions remain with humans?
- When is human review mandatory?
- Can a decision be challenged or reversed?

#### Monitoring

- What metrics indicate healthy operation?
- What thresholds trigger investigation?
- Who receives alerts?

### 5. Controls

For every material risk, document the control.

| Risk | Existing Control | Control Owner | Residual Risk | Action Required |
|---|---|---|---|---|
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |

### 6. Decision

Select one:

- **Proceed** — risks are understood and controls are proportionate.
- **Proceed with conditions** — deployment depends on specified controls or monitoring.
- **Escalate** — additional governance or specialist review is required.
- **Do not proceed** — risks are unacceptable or cannot currently be controlled.

### 7. Evidence Checklist

- [ ] System purpose documented
- [ ] Owner assigned
- [ ] Stakeholders identified
- [ ] Risk assessment completed
- [ ] Data sources documented
- [ ] Security review completed
- [ ] Privacy considerations assessed
- [ ] Testing / validation evidence available
- [ ] Human oversight defined
- [ ] Monitoring plan defined
- [ ] Incident escalation defined
- [ ] Deployment decision recorded
- [ ] Review date scheduled

## Assessment Principle

**A risk assessment should produce a decision and a control plan—not just a score.**
