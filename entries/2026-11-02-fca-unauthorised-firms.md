# FCA Warning List: two unauthorised-firm warnings

- **Date added:** 02/11/2026
- **Source:** FCA Warning List - https://www.fca.org.uk/consumers/warning-list-unauthorised-firms

## Alerts

- **Global Pip Markets** - unauthorised firm (not flagged as a clone) - https://www.fca.org.uk/news/warnings/global-pip-markets
- **CMLC Ltd** - unauthorised firm (not flagged as a clone) - https://www.fca.org.uk/news/warnings/cmlc-ltd

## Scheme

According to the FCA, Global Pip Markets and CMLC Ltd appear to offer or
market financial services without FCA authorisation, and neither firm is
authorised or registered by it. That means consumers dealing with either
firm could not turn to the Financial Ombudsman Service or the FSCS. The FCA cautions that such firms may publish contact details that
are false, or that belong to another business, so the information looks
genuine. Per the notices, Global Pip Markets lists a Great Neck, New York
address (globalpipmarkets.com) and CMLC Ltd lists a Lincoln, Lincolnshire
address (cmlcltd.uk).

## Typology

unauthorised firm; unregistered financial promotion

## Candidate detection signals (hypotheses)

- `[hypothesis]` Register-absence check: unlike clone firms, these names do
  not impersonate a register entry - the firm name simply does not appear on
  the FCA register. Onboarding or payment references to an unregistered name
  warrant review.
- `[hypothesis]` Contact-detail reuse: phone numbers, email addresses, or
  postal addresses quoted by the firm match details published for other warned
  or unrelated businesses, consistent with the FCA's caution that details may
  be false or borrowed.
- `[hypothesis]` Jurisdiction mismatch: the operator solicits UK customers
  while listing only an overseas address and holding no UK authorisation
  (Global Pip Markets lists a US address).

## Notes

Neither warning is flagged as a clone, and the notices carry the FCA's
standard boilerplate plus published contact details only, so the source does
not describe a specific scheme. Exact phone numbers and email addresses are
not reproduced here; see the linked notices.
