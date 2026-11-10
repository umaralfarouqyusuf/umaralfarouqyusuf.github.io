# DFLAB-INF-003A — CSI Linux Image Inspection Record

**Version:** 1.0 · **Status:** Pending inspection

## Purpose and handling
Record the image's structure before restoration. Preserve the source image and perform inspection read-only. Do not execute a write or restore operation as part of this inspection.

## Image details

- Image: CSI Linux Triage Drive, raw `.dd`
- Approximate file size: 52 GB (reported)
- Partition table: GPT (reported; not independently confirmed here)
- Source SHA-256: refer to `../Image_Verification/DFLAB_CSI_Linux_Image_Verification.md`

## Inspection results

| Item | Result |
|---|---|
| Logical image capacity | Pending |
| Partition count | Pending |
| GPT disk identifier | Pending |
| EFI System Partition and size | Pending |
| CSI Linux partition and filesystem | Pending |
| Partition start/end sectors | Pending |
| Unallocated space | Pending |
| Boot configuration observations | Pending |
| Inspection tool/version and date | Pending |
| Evidence/screenshots location | Pending |

A suitable read-only image examination tool may be used. If using The Sleuth Kit, `mmls CSI-Linux-Triage.dd` can display partition layout; preserve the output and record the tool version. Do not modify the source image.

## Destination capacity decision
Confirm the complete logical image geometry and destination capacity before procurement/restoration. The proposed 256 GB SSD is a target, not a confirmed compatible device.

**Conclusion:** Inspection and capacity assessment are outstanding. No partition-level results are asserted.
