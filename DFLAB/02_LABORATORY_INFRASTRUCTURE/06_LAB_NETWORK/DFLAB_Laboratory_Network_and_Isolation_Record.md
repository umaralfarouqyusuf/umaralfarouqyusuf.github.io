# DFLAB Laboratory Network and Isolation Record

**Document ID:** DFLAB-INF-NET-001 · **Version:** 1.0 · **Status:** Design requirements recorded; implementation/testing pending

## Scope
Record network interfaces, laboratory boundaries, access needs and isolation tests. This public record intentionally excludes addresses, credentials and sensitive configuration.

## Design requirements

- Identify host and guest network interfaces and their intended purpose.
- Document which environments may access ordinary networks and under what authorization.
- Separate or isolate examination and training environments as required by the approved design.
- Avoid bridged networking by default for malware-analysis VMs; document and review any exception.
- Disable unnecessary shared folders, shared clipboard and drag-and-drop in higher-risk analysis environments.
- Record firewall, logging and access-control decisions without publishing exploitable configuration.
- Ensure test data and controlled exercises do not expose personal or confidential information.

| Control / test | Status | Evidence |
|---|---|---|
| Network topology approved | Pending | — |
| Host/guest interfaces inventoried | Pending | — |
| Isolation behavior tested | Pending | — |
| Access rules reviewed | Pending | — |
| Logging and change record | Pending | — |

A virtual machine alone does not guarantee malware containment. Do not claim network isolation until an appropriate test is completed and recorded.
