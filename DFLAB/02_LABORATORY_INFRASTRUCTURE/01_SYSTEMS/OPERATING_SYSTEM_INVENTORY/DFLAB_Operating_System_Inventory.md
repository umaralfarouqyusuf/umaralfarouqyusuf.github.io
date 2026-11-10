# DFLAB Operating-System Inventory

**Document ID:** DFLAB-INF-OS-001 · **Version:** 1.0 · **Status:** Initial inventory; several entries require verification

| System | Deployment arrangement / role | Status based on supplied pack | Required record |
|---|---|---|---|
| Windows 11 | Internal SSD; primary host | Existing, user-confirmed | Edition, build, UEFI, Secure Boot, TPM, encryption and update state |
| CSI Linux | Dedicated external SSD; forensic Linux environment | Image hash reportedly matched; deployment pending | Image source/hash, image inspection, restoration, read-back and boot tests |
| CAINE | Forensic examination environment | Existing or planned; not verified | Version, installation medium, boot test and intended use |
| Kali Linux | Live USB or virtual machine for authorized security research/testing | Arrangement not finalized | Version, medium/VM details, isolation and boot test |

This inventory does not imply that CAINE or Kali Linux is installed. Update entries only after inspection. Keep case data and sensitive configuration out of this public record.

**Revision history:** v1.0, 10 November 2026, created from supplied DFLAB pack.
