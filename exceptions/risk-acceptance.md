# Risk Acceptance Register

## Purpose
Document CIS controls that are not enforced and the rationale for acceptance.

## Risk Acceptance Criteria
- Control causes service instability
- Control requires application-specific tuning
- Control overlaps with external governance

## Accepted Risks

| Control | Risk | Mitigation |
|-------|------|-----------|
| Firewall rule enforcement | Inconsistent workloads | Network team ownership |
| Password complexity | App-managed auth | Central IAM |

## Review Process
- Reviewed quarterly
- Reassessed after major incidents
- Approved by platform owner
