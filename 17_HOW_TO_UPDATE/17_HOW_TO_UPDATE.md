# How to Update — OPENEMS

**Project:** `OPENEMS`
**Category:** ELECTRICITY_MANAGEMENT
**Domain:** electricity management and energy
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
OPENEMS --version
OPENEMS check-update
```

### Applying Updates
```bash
pip install --upgrade OPENEMS
```

### Rolling Back
```bash
pip install OPENEMS==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
