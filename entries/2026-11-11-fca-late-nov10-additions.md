# FCA Warning List: late-10/11 additions missed in the 10/11 morning read (recorded 11/11/2026)

- **Recorded:** 11/11/2026
- **Source:** FCA Warning List - https://www.fca.org.uk/consumers/warning-list-unauthorised-firms
- **Why:** the 10/11 entry was a morning read; the FCA published more later that day. Nothing new was dated 11/11 at this morning's read.

## Alerts

New, first published 10/11/2026, missed yesterday:

- **Chartsking.com** - https://www.fca.org.uk/news/warnings/chartskingcom (generic "London" address; chartsking.com)

Updated on the list 10/11/2026, missed yesterday:

- **National-Debt-Helpline** (first published 12/06/2020) - https://www.fca.org.uk/news/warnings/national-debt-helpline
- **LW Management** (clone of an FCA-registered firm; first published 29/10/2026) - https://www.fca.org.uk/news/warnings/lw-management-clone-fca-registered-firm

## Scheme

Per the FCA, Chartsking.com is a firm it lists as unauthorised, saying it
appears to offer or promote financial services without FCA authorisation; its
notice gives only a generic London address. The two updates extend existing
warnings: one long-running entry first published in 2020, and one clone of a
genuinely registered firm first warned about on 29/10/2026. Clone updates
matter because the impersonated firm's details can be refreshed by the
impersonator, keeping the warning current.

## Typology

unauthorised firm; clone firm; debt-help impersonation (National-Debt-Helpline); progressive-publication read lag

## Candidate detection signals (hypotheses)

- `[hypothesis]` Clone-refresh monitoring: updated clone warnings indicate an
  active impersonator re-using a registered firm's identity; weight register
  cross-checks when a counterparty's name matches a recently updated clone
  warning.
- `[hypothesis]` Read-lag control (reaffirmed): a single morning snapshot
  missed 3 of 10 items dated 10/11; a second same-day read or next-morning
  correction pass closes the gap.

## Notes

FCA warnings concern authorisation status; they do not by themselves prove
fraud. Phone numbers and emails from the notices are not reproduced here. OFAC
and FTC had no new items since the last review (OFAC through 09/11, FTC
through 05/11).
