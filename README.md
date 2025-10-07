# Website Operations Hardening Pack

This pack documents how we run a production website safely and predictably.
It covers releases/changes, access reviews, backups/restore checks, incident notes,
and a few operational baselines (HTTPS, DNS, credentials).

**How to use**
1. Do the thing (release / access review / backup test / incident).
2. Tick the matching checklist.
3. Drop the filled template into `/records/YYYY-MM`.
4. Keep all docs short and current. If a step is never done, remove it; if it’s done, write it.

**Out of scope**
- Pen-testing, regulated validation, or formal QMS. This is pragmatic ops hardening.

**Ownership**
- Operational Owner: `[Name, role]`
- Technical Admin(s): `[Name]`

## Limits
- This pack is not a formal quality management system and does not replace regulated validation.
- No penetration testing or formal vulnerability management is included.

## Next steps (if needed)
- Add a monthly “release window” and a quarterly restore rehearsal.
- Add a tiny CI to run link checks or basic tests after content updates.
