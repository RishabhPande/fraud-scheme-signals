# fraud-scheme-signals

A dated record of fraud and scam alerts from primary sources, with each alert
broken down into a short scheme summary, typology tags, and candidate detection
signals a fraud team could evaluate.

> **Status: active since Nov 2, 2026.** The FCA Warning List and FTC Consumer
> Alerts below are checked daily; the other listed sources are planned. Entries
> are added only when there is something worth recording, through pull requests
> reviewed by the owner; quiet days produce no commits.

## What this is

- Short, attributed summaries of real alerts, always linking the primary source.
- Typology tags that accumulate as schemes evolve (clone-firm impersonation,
  government impersonation, QR phishing, AI voice clones, and so on).
- **Candidate detection signals, clearly labeled as hypotheses.** They are
  starting points for evaluation, not validated detection rules.

## What this is not

- Not a blocklist, threat feed, or indicator-of-compromise dump.
- Not validated or tested detection logic. Nothing here has been run against
  production data.
- Not a republication of source content. Entries are brief summaries with
  attribution and links; read the source for the full alert.

## Update model

The daily-checked sources (FCA, FTC) are read each day, with entries added only
when there is something worth recording; quiet days produce no commits.
Substance over cadence.

## Sources (primary only)

| Source | Link | Status (as of Nov 9, 2026) |
| --- | --- | --- |
| FCA Warning List | https://www.fca.org.uk/consumers/warning-list-unauthorised-firms | Checked daily (near-daily publication; entries added every weekday Oct 26-30, 2026) |
| FTC Consumer Alerts | https://consumer.ftc.gov/consumer-alerts | Checked daily (publishes roughly 1-2 alerts per week) |
| FBI IC3 PSAs | https://www.ic3.gov/PSA/2026 | Planned; not yet checked (2026 index page is JS-rendered; individual dates unverified) |
| FinCEN advisories | (URL to verify) | Planned; not yet checked |

## Entry format

Each entry in `entries/` is one markdown file named `YYYY-MM-DD-<source>-<slug>.md`:

- **Alert**: title, source, date, link.
- **Scheme**: 2-3 sentence summary, attributed to the source.
- **Typology**: tags.
- **Candidate detection signals (hypotheses)**: ideas to evaluate, each labeled
  `[hypothesis]`. These are proposed by this repo, not asserted by the source.

## Disclaimer

Not legal, compliance, or investment advice. No detection signal here makes or
replaces a determination; anything flagged still needs human review. Firm and
brand names belong to their owners; "clone firm" warnings concern unauthorised
firms impersonating genuine, authorised firms. Verify any firm against the
relevant official register (e.g. the FCA Firm Checker) before acting.
