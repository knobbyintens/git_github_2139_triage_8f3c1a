# Release Notes: v2.5.0

## Security Fixes
- #3 — Session fixation vulnerability in login callback (P1)
- #7 — Batch update endpoint missing CSRF validation (P2)

## Bug Fixes
- #2 — SSO token refresh returns 401 after session rotation (P1)
- #5 — Audit log pagination returns duplicate rows (P2)
- #6 — Avatar upload fails for files over 8 MB (P3)

## Improvements
- #8 — Add feature-flag rollout dashboard (P1)
- #4 — Search index rebuild stalls for large tenants (P2)

## Excluded
- #9 — Refresh onboarding documentation screenshots (type: documentation)
- #10 — Rate-limit bypass via spoofed client header (target: v2.6.0)
- #11 — WebSocket worker leaks memory under reconnect storms (target: v2.6.0)
- #12 — Replace deprecated structured logger (type: chore)
