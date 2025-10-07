# HTTPS & DNS Baseline

- Domain registrar: [Provider]; 2FA enabled; recovery email up to date
- DNS: A/AAAA for www/root; CAA record present; no orphan/legacy records
- TLS: 301 redirect to HTTPS; HSTS enabled (if stable); cert valid ≥30 days
- Admin access: limited IP (if possible); no shared logins
- Backups: daily DB + weekly files; encrypted at rest (provider setting)
