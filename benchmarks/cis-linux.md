# CIS Linux Benchmark Interpretation

## Scope
This document summarizes the interpretation of CIS Linux Benchmark controls
as applied to platform hosts.

## Benchmark Version
- CIS Linux Benchmark v1.x (generic interpretation)

## Control Categories
- Filesystem configuration
- Access control and authentication
- Logging and auditing
- Kernel parameters

## Interpretation Guidelines
- Controls impacting system boot or application runtime are evaluated carefully
- Controls requiring manual tuning are not enforced automatically
- Preference is given to controls enforceable via configuration management

## Example Controls
| Control | Interpretation |
|-------|----------------|
| Disable core dumps | Enforced |
| SSH root login | Enforced |
| Firewall rules | Platform-dependent |
| Password complexity | OS policy-dependent |
