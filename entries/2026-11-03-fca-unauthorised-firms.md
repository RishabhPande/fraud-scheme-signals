# FCA Warning List: two new unauthorised firms, one updated warning

- **Date added:** 02/11/2026 and 03/11/2026
- **Source:** FCA Warning List - https://www.fca.org.uk/consumers/warning-list-unauthorised-firms

## Alerts

- **Equity Plus Options / equityplusoptions.com** - unauthorised firm (new, 03/11/2026) - https://www.fca.org.uk/news/warnings/equity-plus-options-equityplusoptionscom
- **Prime Yield Assets** - unauthorised firm (new, 02/11/2026) - https://www.fca.org.uk/news/warnings/prime-yield-assets
- **Momentum Peak Trade** - existing warning updated (02/11/2026; first published 22/04/2026) - https://www.fca.org.uk/news/warnings/momentum-peak-trade

## Scheme

According to the FCA, Equity Plus Options and Prime Yield Assets appear to
offer or market financial services without FCA authorisation; neither is
authorised or registered by it, so consumers dealing with them could not turn
to the Financial Ombudsman Service or the FSCS. Equity Plus Options lists a Brighton address and
Prime Yield Assets a Taunton address; per standard FCA caution, such details
may be false or borrowed from another business. Separately, the FCA updated
its April 2026 warning on Momentum Peak Trade: the notice now spans five
domains and subdomains across .io, .com, .co and .ac, consistent with an
operator rotating web infrastructure after being flagged.

## Typology

unauthorised firm; unregistered financial promotion; domain rotation (Momentum Peak Trade)

## Candidate detection signals (hypotheses)

- `[hypothesis]` Register-absence check: the firm names do not appear on the
  FCA register at all; onboarding or payment references to an unregistered
  name warrant review.
- `[hypothesis]` Successor-domain monitoring: once a firm is warned, watch for
  new domains echoing the same brand across other TLDs or client-portal
  subdomains, as the Momentum Peak Trade update illustrates.
- `[hypothesis]` Returns-implying naming: unauthorised investment promoters
  favor names evoking profit ("Prime Yield", "Equity Plus Options"); such
  naming in inbound payment or onboarding references merits a register check.
- `[hypothesis]` Contact-detail reuse: published phone numbers or addresses
  match details linked to other warned or unrelated businesses.

## Notes

Prime Yield Assets is dated 02/11 but appeared after the Nov 2 10am ET check
(FCA publishes on UK time). Momentum Peak Trade is an update to an existing
warning, not a new firm. Exact phone numbers and email addresses are not
reproduced here; see the linked notices.
