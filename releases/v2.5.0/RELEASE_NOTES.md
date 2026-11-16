# Release Notes: v2.5.0

## Security Fixes
- #74 — Session fixation vulnerability in login callback (P1)
- #78 — Batch update endpoint missing CSRF validation (P2)

## Bug Fixes
- #73 — SSO token refresh returns 401 after session rotation (P1)
- #76 — Audit log pagination returns duplicate rows (P2)
- #77 — Avatar upload fails for files over 8 MB (P3)

## Improvements
- #79 — Add feature-flag rollout dashboard (P1)
- #75 — Search index rebuild stalls for large tenants (P2)

## Excluded
- #80 — Refresh onboarding documentation screenshots (non-shippable type: documentation)
- #81 — Rate-limit bypass via spoofed client header (targets v2.6.0)
- #82 — WebSocket worker leaks memory under reconnect storms (targets v2.6.0)
- #83 — Replace deprecated structured logger (non-shippable type: chore)
