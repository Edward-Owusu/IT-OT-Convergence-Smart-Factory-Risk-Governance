# Risk Assessment

## Assessment Method

Risks are evaluated using:

- Likelihood: 1–5
- Impact: 1–5
- Risk Score: Likelihood × Impact

## Risk Register

### RSK-OT-001 — Unauthorized HMI Access

- **Inherent Likelihood:** 4/5
- **Inherent Impact:** 5/5
- **Inherent Risk:** 20/25
- **Risk:** Unauthorized or unauthenticated access to factory-floor Human-Machine Interfaces.
- **Mitigation:** Deploy localized MFA or unique user profiles for physical plant workstations and isolate HMI subnets.
- **Residual Likelihood:** 2/5
- **Residual Impact:** 4/5
- **Residual Risk:** 8/25

### RSK-OT-002 — Legacy Industrial Endpoint Exposure

- **Inherent Likelihood:** 5/5
- **Inherent Impact:** 4/5
- **Inherent Risk:** 20/25
- **Risk:** Legacy operating systems supporting PLCs may not support modern EDR or antivirus agents.
- **Mitigation:** Implement rigid network segmentation using zones and conduits, supported by hardware-enforced unidirectional controls where appropriate.
- **Residual Likelihood:** 2/5
- **Residual Impact:** 4/5
- **Residual Risk:** 8/25

### RSK-OT-003 — OT Incident Response Gaps

- **Inherent Likelihood:** 4/5
- **Inherent Impact:** 5/5
- **Inherent Risk:** 20/25
- **Risk:** Lack of dedicated safety-aware incident-response playbooks for production lines during a corporate ransomware event.
- **Mitigation:** Develop and test an OT-specific incident-response and availability playbook with defined air-gapping and isolation criteria.
- **Residual Likelihood:** 2/5
- **Residual Impact:** 3/5
- **Residual Risk:** 6/25

## Risk Treatment Summary

The proposed treatments reduce exposure through network isolation, stronger identity controls, and rehearsed response procedures. Residual risk should be validated through recurring technical testing, operational exercises, and management review.
