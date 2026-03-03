# IPConfig Protocol: GitHub Provenance Requirement

Protocol ID: IPCONFIG-PROT-GITHUB-PROVENANCE-2026-03-03
Status: Active
Effective date: 2026-03-03

## Rule

IPConfig/IPClaim evidence is considered operational only when anchored in GitHub repository provenance (commit history + pushed remote state + timestamp workflow outputs when configured).

## Minimum Validity Conditions

1. Changes are committed in git.
2. Commit is pushed to `origin`.
3. Repository contains timestamp automation at `.github/workflows/timestamp.yml`.
4. Timestamp artifacts are preserved in `.timestamps/` after workflow execution.

## Continuity Rule (No Reset)

License updates and IPClaim linkage updates are additive records and do not replace original disclosure dates documented in prior records.

## Linked Records

- `docs/legal/IPCONFIG_PROTOCOL_DATE_CONTINUITY_2026-03-02.md`
- `docs/legal/IP_PROVENANCE_REGISTER.md`
- `docs/legal/IPCONFIG_PROOF.md`
