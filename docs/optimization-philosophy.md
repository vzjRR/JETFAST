# Optimization Philosophy

## Purpose

vzjRR PC Jet follows an evidence-based Windows optimization methodology.

The objective is not to apply the largest possible number of tweaks.

The objective is to identify real problems, apply justified corrections, improve gaming performance where measurable, preserve system stability and security, and maintain a reliable rollback path.

---

## Core Principles

### 1. Measure Before Changing

The system must be inspected before any optimization is performed.

A baseline should be established whenever the required measurement is available.

Without a baseline, performance improvement must not be claimed.

---

### 2. Evidence Over Internet Tweaks

A popular Windows gaming tweak is not automatically a valid optimization.

Every proposed change should have a technical reason based on:

- the detected hardware
- the detected Windows configuration
- measured system behavior
- documented Windows behavior
- reliable vendor documentation
- reproducible evidence

---

### 3. Stability Before Performance

The optimization hierarchy is:

1. System stability
2. System reliability
3. Security preservation
4. Frame-time consistency
5. Background workload reduction
6. Storage responsiveness
7. CPU efficiency
8. GPU efficiency
9. Network stability
10. Raw FPS

Maximum FPS is not the only objective.

---

### 4. Minimal Intervention

Do not change something simply because it can be changed.

If the current configuration is already appropriate, leave it alone.

The preferred optimization is:

> The smallest justified change that produces a measurable or technically defensible benefit.

---

### 5. Reversibility

Whenever possible, every modification must be reversible.

Before changing a configuration:

1. Record the current state.
2. Create an appropriate backup.
3. Apply the change.
4. Verify the new state.
5. Record the result.
6. Preserve the rollback information.

---

### 6. No Placebo Optimization

The system must not apply tweaks merely because they are commonly advertised as "FPS boosts."

Examples of changes that must not be performed without strong evidence:

- arbitrary HPET changes
- arbitrary BCD timer changes
- random TCP registry tweaks
- random GPU registry tweaks
- fake RAM cleaning
- forced realtime priority
- arbitrary CPU affinity
- arbitrary interrupt affinity
- mass Windows service disabling
- unnecessary shader-cache deletion

---

### 7. Security Must Be Preserved

Gaming performance must not be improved by unnecessarily weakening Windows security.

Do not disable security mechanisms merely because they may theoretically reduce overhead.

Protected areas include:

- Microsoft Defender
- Windows Firewall
- Secure Boot
- Memory Integrity
- SmartScreen
- Windows Update

Security-related changes are separate high-risk operations.

---

### 8. Hardware-Aware Optimization

Never assume that one configuration is optimal for every computer.

Optimization decisions must account for:

- CPU architecture
- GPU model
- RAM capacity
- RAM configuration
- storage type
- motherboard
- Windows version
- driver version
- display refresh rate
- VRR/HDR configuration
- power configuration
- thermal behavior
- desktop/laptop status

---

### 9. Gaming Optimization

The project should focus on:

- stable FPS
- consistent frame times
- reduced stutter
- reduced unnecessary background activity
- GPU utilization efficiency
- CPU utilization efficiency
- storage responsiveness
- system responsiveness
- network stability
- thermal stability

Do not optimize only for a theoretical maximum FPS number.

---

### 10. Verify Every Important Change

After a modification, verify that:

- the intended configuration changed
- Windows remains healthy
- the system remains stable
- no unexpected errors were introduced
- the expected benefit is observable where measurable

If verification fails, stop and consider rollback.

---

### 11. Honest Reporting

The system must distinguish between:

- Measured improvement
- No measurable improvement
- Regression
- Expected improvement
- Technically justified but unmeasured improvement
- Not measurable

Never convert an expected improvement into a claimed performance improvement.

Never fabricate FPS numbers.

---

### 12. Continuous Learning

If a proposed optimization is rejected because evidence is insufficient, record the reason.

If a modification produces no measurable improvement, record that result.

If a modification causes a regression, record the regression and rollback.

The system should become more conservative over time rather than accumulating unsupported tweaks.

---

## Optimization Decision Model

For each proposed optimization evaluate:

### Evidence Quality

How strong is the technical evidence supporting the change?

### Expected Benefit

What specific problem is the change expected to improve?

### Risk

What could go wrong?

### Reversibility

Can the original state be reliably restored?

### Verification

Can the result actually be measured?

---

## Preferred Optimization Profile

Prefer changes that have:

- strong evidence
- clear purpose
- low risk
- high reversibility
- measurable results

Avoid changes that have:

- weak evidence
- unclear purpose
- high risk
- poor rollback capability
- no measurable outcome

---

## Final Principle

The goal of vzjRR PC Jet is not to make the Windows installation look "optimized."

The goal is to make the computer measurably healthier, more stable, and better suited for gaming while changing as little as necessary.
