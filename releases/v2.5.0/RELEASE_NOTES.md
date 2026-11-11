# Release Notes: v2.5.0

## Security Fixes
- #27 — Session fixation vulnerability in login callback (P1)
- #31 — Batch update endpoint missing CSRF validation (P2)

## Bug Fixes
- #26 — SSO token refresh returns 401 after session rotation (P1)
- #29 — Audit log pagination returns duplicate rows (P2)
- #30 — Avatar upload fails for files over 8 MB (P3)

## Improvements
- #32 — Add feature-flag rollout dashboard (P1)
- #28 — Search index rebuild stalls for large tenants (P2)

## Excluded
- #33 — Refresh onboarding documentation screenshots (type: documentation)
- #34 — Rate-limit bypass via spoofed client header (target: v2.6.0)
- #35 — WebSocket worker leaks memory under reconnect storms (target: v2.6.0)
- #36 — Replace deprecated structured logger (type: chore)
