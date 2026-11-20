# FCA Warning List: three clone-firm warnings

- **Date added:** 30/10/2026
- **Source:** FCA Warning List - https://www.fca.org.uk/consumers/warning-list-unauthorised-firms

## Alerts

- **shardcreditpartners.uk** - clone of FCA firms
- **Client.octopus-firm.com** - clone of FCA authorised firm
- **Northern Index** - clone of FCA authorised fund

## Scheme

The FCA flagged three operations presenting as legitimate UK financial firms.
Each copies the identity of a genuine authorised firm or fund - same or similar
name, convincing web presence - so a victim checking the name alone may believe
they are dealing with the real, regulated entity. The genuine firms are not
involved.

## Typology

clone-firm impersonation; investment fraud; unauthorised firm

## Candidate detection signals (hypotheses)

- `[hypothesis]` Domain-vs-register check: the contact domain does not match the
  domain registered against the genuine firm's FCA register entry.
- `[hypothesis]` Recency check: the web domain was registered recently relative
  to the claimed operating history of the firm it imitates.
- `[hypothesis]` Identifier mismatch: the firm reference number (FRN), address,
  or phone number quoted by the operator does not match the register entry for
  the firm it claims to be.
- `[hypothesis]` Outbound-monitoring angle: customer payments or onboarding
  journeys referencing a firm name whose only web presence is a lookalike
  domain.

## Notes

Three clone warnings in a single day is typical of the FCA list's current
tempo; clone-firm impersonation was the dominant typology in the Oct 26-30
window (7 of the entries added that week were clones).
