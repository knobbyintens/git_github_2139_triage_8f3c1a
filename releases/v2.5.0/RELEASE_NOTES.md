# Release Notes: v2.5.0

## Security Fixes
- #39 — Session fixation vulnerability in login callback (P1)
- #43 — Batch update endpoint missing CSRF validation (P2)

## Bug Fixes
- #38 — SSO token refresh returns 401 after session rotation (P1)
- #41 — Audit log pagination returns duplicate rows (P2)
- #42 — Avatar upload fails for files over 8 MB (P3)

## Improvements
- #44 — Add feature-flag rollout dashboard (P1)
- #40 — Search index rebuild stalls for large tenants (P2)

## Excluded
- #45 — Refresh onboarding documentation screenshots (type: documentation)
- #46 — Rate-limit bypass via spoofed client header (target: v2.6.0)
- #47 — WebSocket worker leaks memory under reconnect storms (target: v2.6.0)
- #48 — Replace deprecated structured logger (type: chore)
