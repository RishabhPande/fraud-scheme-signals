# FTC: "Spot scammers impersonating well-known charities and sweepstakes"

- **Date:** October 26, 2026
- **Source:** FTC Consumer Alert - https://consumer.ftc.gov/consumer-alerts/2026/10/spot-scammers-impersonating-well-known-charities-and-sweepstakes

## Scheme

Scammers impersonate reputable charities, and in a combined variant tell past
donors they have won a charity-sponsored sweepstakes. The borrowed brand does
the trust-building; the "prize" creates the reason to engage and pay (fees,
"taxes", or verification details).

## Typology

charity impersonation; sweepstakes/prize scam; brand impersonation

## Candidate detection signals (hypotheses)

- `[hypothesis]` Donation-to-prize pivot: contact referencing a real past
  donation, then introducing an unexpected "win" - the pivot is the anomaly.
- `[hypothesis]` Pay-to-claim: any request for payment or sensitive data to
  release a prize from a charity the target supports.
- `[hypothesis]` Sender mismatch: outreach domains or sender identities that
  approximate, but do not match, the charity's official channels.

## Notes

Charity impersonation also spikes around disasters and holidays; expect
seasonal clustering in future entries.
