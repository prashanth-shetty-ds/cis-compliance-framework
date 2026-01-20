# Linux CIS Baseline Assessment

## Objective
Assess current Linux hosts against selected CIS benchmark controls.

## Assessment Methodology
- Configuration review
- Runtime verification
- Automation validation

## Assessment Results

| Control | Status | Notes |
|-------|--------|------|
| Disable core dumps | Compliant | Enforced via Ansible |
| SSH root login | Compliant | ssh-hardening role |
| Audit logging | Partial | Forwarding enabled |
| Firewall rules | Exception | Managed externally |

## Gaps Identified
- Firewall management not standardized
- Periodic audit review missing

## Recommendations
- Centralize firewall enforcement
- Add quarterly compliance review cadence
