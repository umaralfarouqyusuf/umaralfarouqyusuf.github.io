# DFLAB-INF-004 — CSI Linux External SSD Deployment Record

**Deployment ID:** DFLAB-DEP-CSI-001 · **Version:** 1.0 · **Status:** Pending deployment

## Deployment details

| Field | Value |
|---|---|
| Source | CSI Linux official Triage Drive raw `.dd` image |
| Source location | Existing external HDD |
| Source SHA-256 | Refer to image-verification record; value not transcribed |
| Destination device/model/capacity | Pending procurement and identification |
| Restoration tool/version | Pending |
| Date/operator | Pending |
| Restoration/read-back result | Pending |

## Pre-deployment checklist

- [ ] Confirm the official source and record source hash/reference.
- [ ] Complete read-only partition inspection and capacity assessment.
- [ ] Identify the destination by make/model/capacity; keep serial number in controlled internal record.
- [ ] Positively distinguish destination from the internal Windows SSD.
- [ ] Confirm the destination has no data requiring preservation.
- [ ] Check Windows recovery and device-encryption status before any firmware or disk changes.
- [ ] Preserve the source image unchanged.

## Controlled restoration
Only after the checklist is complete, use a selected imaging utility to restore the `.dd` source to the positively identified dedicated external SSD. Review source and destination before confirming; restoration overwrites the destination. Record the tool output, errors, date, operator and evidence location.

Verify the restored image using a validated tool method or a read-back comparison over the image-length region. Hashing the entire larger target device may not match the source image because of additional capacity.

## Acceptance
Deployment is not accepted until restoration verification, partition review, successful boot test and independent Windows startup (with the CSI drive disconnected) are recorded. Current decision: **not deployed**.
