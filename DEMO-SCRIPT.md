# Pulse demo script

## Start and stop

1. Double-click **Start Demo.command**. Chrome opens at **http://pulse.localhost:8080**.
2. Close that Terminal window when you're done. That stops the demo.

The first time, macOS may ask whether Terminal can access your Downloads folder: click **Allow**.
No internet needed; React and the fonts are bundled in `vendor/`.

## The story (same numbers on every screen)

- **Compliance:** Marek Kowalski's Safe Pass has expired, so he's blocked from Castleview. 4 more certs expire within 30 days (3 Safe Pass, 1 Manual Handling). 2 lads haven't uploaded through the Lad Portal.
- **Invoicing, Week 38:** 15 of 17 timesheets in; Jason Doyle and Liam Grogan are missing. 5 invoices drafted, €25,194, awaiting approval.
- **Forecast:** add 3 lads at €38 charge / €28 pay and monthly margin goes from €28,700 to €33,770 (+€5,070).

Where to show it: Home (briefing card), Agents › Briefing, Compliance › Expiring, Work › Timesheets and Invoices, Dashboard › Forecast, Activity.

## Questions Helios answers

Type these on Home, or click the matching suggestion. The wording can change; Helios listens for the key words.

| Ask | Helios shows | Key words it listens for |
|---|---|---|
| Which certs expire this month? | Marek expired, 4 more due, table of all 5 | cert, safe pass, expire, compliance, Marek |
| Who hasn't sent a timesheet? | 15 of 17 in; Jason and Liam missing | timesheet, hours, missing |
| Who owes me money? | €21,600 overdue: Ardmore €13,200, Fenlon €8,400 | overdue, owe, money, Ardmore, Fenlon |
| Are the invoices ready? | 5 Week 38 drafts, €25,194 | invoice, billing |
| What if I add 3 lads? | Margin €28,700 → €33,770 (+€5,070) | forecast, what if, add, margin, rates |
| Draft a chase email for Ardmore Civils | A write tool: drafts it and waits for your yes | chase, email, draft |
| Text all four a reminder | A write tool: 4 cert reminders, waits for your yes | text, remind |

Anything else gets: "Everything I reach goes through a registered tool with a declared permission, and none of them covers that question yet." It then offers buttons for the questions above.

## Watch out for

- **Write tools:** stop at the **NEEDS YOUR YES** card, which is the point to make. **Confirm and send** replies that it replayed the stored arguments.
- **Light mode is the Walsh look** (orange on white). Dark mode keeps the same orange accent.
- **Old link:** `localhost:8080/Pulse%20v4%20Glass.dc.html` no longer works. Use http://pulse.localhost:8080.
