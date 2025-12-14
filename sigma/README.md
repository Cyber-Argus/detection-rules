# Sigma Detection Rules

Sigma rules are platform-agnostic detection rules that can be converted to various SIEM query languages.

## Organization

Rules are organized by:
- Operating system (windows, linux, macos)
- Log source (process_creation, network, registry, etc.)
- MITRE ATT&CK technique

## Naming Convention

`[technique-id]_[brief-description].yml`

Example: `t1059-001_suspicious_powershell_execution.yml`

## Rule Status

- **Experimental** - Newly created, not yet tested
- **Testing** - Currently being validated in homelab
- **Stable** - Tested and tuned for production use

---

**Total Sigma Rules:** 0
