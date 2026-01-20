# Automation Enforcement Mapping

This document maps CIS controls to automation mechanisms.

| CIS Control | Enforcement Mechanism | Repo |
|-----------|----------------------|------|
| Disable core dumps | cis-linux Ansible role | config-management-ansible |
| SSH root login | ssh-hardening role | config-management-ansible |
| Log forwarding | logging role | config-management-ansible |
| OS patching | patching.yml | config-management-ansible |
| Kubernetes RBAC | Platform policy | sre-platform-lab |

Controls not listed here require manual assessment or risk acceptance.
