# DFLAB Infrastructure Testing and Validation Register

**Document ID:** DFLAB-INF-VAL-001 · **Version:** 1.0 · **Status:** Initial register; tests mostly pending

A completed test report should identify methodology, environment, expected and actual results, evidence, conclusion, operator and reviewer/date where applicable. Do not claim validation from installation alone.

| Test ID | Component / objective | Acceptance condition | Current result/status |
|---|---|---|---|
| INF-AT-001 | Hardware identification | Inventory details recorded | User-confirmed summary; detailed inventory pending |
| INF-AT-002 | Internal SSD availability | Windows storage accessible | Reported operational; evidence not attached |
| INF-AT-003 | External HDD availability | Existing drive accessible | Reported available |
| INF-AT-004 | CSI image integrity | Calculated hash matches trusted reference | Match reported by owner; values/source to record |
| INF-AT-005 | CSI GPT inspection | Partition structure recorded | Pending |
| INF-AT-006 | Destination preparation | Correct external SSD identified and suitable | Pending |
| INF-AT-007 | CSI restoration | Restore completes without error | Pending |
| INF-AT-008 | CSI read-back verification | Restored image region verified | Pending |
| INF-AT-009 | CSI UEFI boot | CSI Linux starts as intended | Pending |
| INF-AT-010 | Independent Windows boot | Windows starts with CSI SSD disconnected | Pending |
| INF-AT-011 | Storage allocation | Roles documented and implemented | Pending |
| INF-AT-012 | Independent backup | Selected data backed up to separate device | Pending |
| INF-AT-013 | Recovery | Sample restored and expected hash verified | Pending |
| INF-AT-014 | Virtualization | Selected guest systems operate | Pending |
| INF-AT-015 | Toolkit register | Tools and versions recorded | Pending |
| INF-AT-016 | Tool validation | Defined tool tests completed and documented | Pending |
| INF-AT-017 | Network isolation | Controls tested and recorded | Pending |
| INF-AT-018 | Infrastructure review | Risks and limitations recorded | Pending |

Tests may be accepted in stages: hardware, storage, OS deployment, virtualization, backup/recovery and full infrastructure. Overall status remains **implementation in progress**.
