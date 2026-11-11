# Release Notes: v2.5.0

## Security Fixes
- #51 — Session fixation vulnerability in login callback (P1)
- #55 — Batch update endpoint missing CSRF validation (P2)

## Bug Fixes
- #50 — SSO token refresh returns 401 after session rotation (P1)
- #53 — Audit log pagination returns duplicate rows (P2)
- #54 — Avatar upload fails for files over 8 MB (P3)

## Improvements
- #56 — Add feature-flag rollout dashboard (P1)
- #52 — Search index rebuild stalls for large tenants (P2)

## Excluded
- #57 — Refresh onboarding documentation screenshots (type: documentation)
- #58 — Rate-limit bypass via spoofed client header (target: v2.6.0)
- #59 — WebSocket worker leaks memory under reconnect storms (target: v2.6.0)
- #60 — Replace deprecated structured logger (type: chore)
