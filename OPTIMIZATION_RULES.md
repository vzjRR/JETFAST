# Optimization Rules

## Priority

Optimization decisions should prioritize:

1. Stability
2. Reliability
3. Frame-time consistency
4. Background-load reduction
5. Storage responsiveness
6. GPU efficiency
7. CPU efficiency
8. Network stability
9. Raw FPS

---

## Safe Optimization Categories

Potentially safe:

- startup cleanup
- unnecessary application cleanup
- verified temporary-file cleanup
- correcting incorrect display refresh rate
- correcting incorrect power configuration
- Windows health repair
- freeing verified temporary storage
- reducing unnecessary background applications

---

## Conditional Optimization

Require evidence:

- service changes
- scheduled task changes
- power-plan changes
- GPU scheduling changes
- network adapter power management
- advanced Windows gaming configuration

---

## High-Risk Optimization

Require explicit approval:

- registry modification
- driver removal
- BCD modification
- security configuration
- boot configuration
- filesystem repair
- system-wide service modifications

---

## Forbidden Default Tweaks

Never perform by default:

- HPET disabling
- arbitrary BCD timer changes
- random TCP registry tweaks
- random GPU registry hacks
- disabling Defender
- disabling Firewall
- disabling Windows Update
- disabling Secure Boot
- disabling Memory Integrity
- forced realtime priority
- arbitrary CPU affinity
- arbitrary interrupt affinity
- fake RAM optimization
- mass service disabling
