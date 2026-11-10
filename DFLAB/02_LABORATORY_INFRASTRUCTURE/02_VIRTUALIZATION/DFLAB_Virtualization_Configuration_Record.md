# DFLAB Virtualization Configuration Record

**Document ID:** DFLAB-INF-VIRT-001 · **Version:** 1.0 · **Status:** Hypervisor not selected; implementation pending

## Hypervisor decision
Potential platforms identified in the planning pack: Hyper-V, Oracle VirtualBox and VMware Workstation. The selected platform and rationale have not been recorded. Selection should account for Windows edition, hardware support, compatibility and required isolation. Do not assume multiple hypervisors should run simultaneously.

| Decision item | Record |
|---|---|
| Selected hypervisor and version | Pending |
| Selection rationale | Pending |
| Host virtualisation enabled | Pending verification |
| Network isolation design | Pending |
| Shared folders/clipboard policy | Pending |
| Snapshot and recovery approach | Pending |

## Proposed VM inventory — not deployed status

| Guest / purpose | Status |
|---|---|
| Windows 10 — legacy artefact examination | Planned |
| Windows 11 — modern artefact examination | Planned |
| Windows Server — server investigation/log analysis | Planned |
| Ubuntu / Linux Mint — Linux examination | Planned |
| Android environment — mobile forensics learning | To evaluate |
| Malware lab — controlled training | Planned |
| Network lab — investigation/monitoring | Planned |
| CSI Linux VM — alternative testing environment | Not selected |

For every deployed VM, record guest version, CPU/RAM allocation, virtual disk, network mode, sharing settings, snapshot identifier/date, intended use and limitations. Malware-analysis environments require deliberate containment; a VM alone does not guarantee containment. Avoid bridged networking by default, disable unnecessary sharing, use clean snapshots and document any controlled connectivity. No VM is represented as currently deployed.
