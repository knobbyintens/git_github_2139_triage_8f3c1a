# Release Notes: v2.5.0

## Security Fixes
- #15 — Session fixation vulnerability in login callback (P1)
- #19 — Batch update endpoint missing CSRF validation (P2)

## Bug Fixes
- #14 — SSO token refresh returns 401 after session rotation (P1)
- #17 — Audit log pagination returns duplicate rows (P2)
- #18 — Avatar upload fails for files over 8 MB (P3)

## Improvements
- #20 — Add feature-flag rollout dashboard (P1)
- #16 — Search index rebuild stalls for large tenants (P2)

## Excluded
- #21 — Refresh onboarding documentation screenshots (type: documentation)
- #22 — Rate-limit bypass via spoofed client header (target: v2.6.0)
- #23 — WebSocket worker leaks memory under reconnect storms (target: v2.6.0)
- #24 — Replace deprecated structured logger (type: chore)
