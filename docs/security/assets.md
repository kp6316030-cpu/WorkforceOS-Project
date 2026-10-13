# WorkforceOS Security Assets

## Purpose

Identify the information, systems, and services that must be protected.

## Assets

| ID | Asset | Why it matters | Confidentiality | Integrity | Availability |
|---|---|---|---|---|---|
| A01 | Employee personal details | Protect employee privacy | High | High | Medium |
| A02 | Salary and bank data | Prevent financial harm | High | High | High |
| A03 | Payslips | Prevent unauthorized disclosure or modification | High | High | Medium |
| A04 | Passwords and authentication credentials | Prevent account takeover | High | High | High |
| A05 | Access and refresh tokens | Prevent unauthorized sessions | High | High | High |
| A06 | AI predictions | Prevent manipulation and inappropriate disclosure | Medium | High | Medium |
| A07 | Audit logs | Preserve evidence of important actions | High | High | High |
| A08 | Database backups | Prevent large-scale data loss | High | High | Medium |
| A09 | API keys and deployment secrets | Prevent unauthorized system access | High | High | High |
| A10 | Source code and deployment artifacts | Preserve software integrity | Medium | High | High |

## Questions to confirm with the teams

- Which assets actually exist?
- Which team owns each asset?
- Where is each asset stored?
- Which users and services can access it?
- Is it encrypted in transit and at rest?
- What would happen if it were disclosed, modified, or unavailable?

## Notes

The classifications above are initial estimates. Confirm them with the relevant teams and the project owner before finalizing the threat model.
