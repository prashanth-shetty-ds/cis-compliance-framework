# CIS Kubernetes Benchmark Interpretation

## Scope
This document defines how CIS Kubernetes Benchmark controls are interpreted
for managed Kubernetes platforms.

## Focus Areas
- Control plane security
- RBAC and authentication
- Namespace isolation
- Audit logging

## Key Principles
- Platform team owns control plane compliance
- Application teams own workload security
- Admission controls preferred over manual checks

## Example Controls
| Control | Responsibility |
|-------|----------------|
| API server auth | Platform team |
| etcd encryption | Platform team |
| Pod security | Shared |
| Image provenance | Application teams |
