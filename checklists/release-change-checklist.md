# Release & Change Checklist

System: [Website]   Date: [YYYY-MM-DD]   Performed by: [Name]   Approved by: [Owner]

## Pre-checks
- [ ] Ticket/decision recorded in change log (ID: [ID])
- [ ] Backup completed <24h (link to proof: [/records/...])
- [ ] Critical paths listed (booking, payment, login)
- [ ] Rollback plan noted (how to revert / who approves)

## Execute
- [ ] Apply updates (core/plugins/themes/code)
- [ ] Verify environment and versions recorded
- [ ] No new admin roles created; least privilege intact

## Post-update verification (tick critical paths)
- [ ] Home loads and no major console errors
- [ ] Booking flow: search → select → confirm
- [ ] Auth: login/out works; 2FA required for admins
- [ ] Payment (if applicable): test mode / stub ok
- [ ] Error logs: no new critical entries

## Close
- [ ] Change log updated (what/when/who, links)
- [ ] Backup snapshot label added (post-release)
- [ ] Owners notified (brief note)
