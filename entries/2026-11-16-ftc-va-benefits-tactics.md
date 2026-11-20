# FTC Consumer Alert: three new tactics targeting VA benefits, 16 Nov 2026 (recorded 16 Nov 2026)

- **Recorded:** 16 Nov 2026
- **Source:** FTC Consumer Alerts - https://consumer.ftc.gov/consumer-alerts/2026/11/three-new-tactics-scammers-use-go-after-va-benefits
- **Other sources:** FCA Warning List quiet since 13 Nov; OFAC quiet since 13 Nov.

## Alert

**Three new tactics scammers use to go after VA benefits** (FTC, published 16 Nov 2026) - https://consumer.ftc.gov/consumer-alerts/2026/11/three-new-tactics-scammers-use-go-after-va-benefits

## Scheme

Per the FTC, scammers posing as the VA charge illegal upfront fees and promise guaranteed disability ratings or fast-tracked claims. The three newer twists: lookalike phone numbers one digit off real VA hotlines that catch misdials, social media ads for fake veterans grant programs that harvest direct-deposit details to reroute payments, and mailed postcards for a nonexistent "Veterans Savings Program" that fish for Social Security and bank numbers. The FTC's counters: apply only through VA.gov or a regional office, verify helpers in the VA's accreditation tool, and never pay upfront to file a claim.

## Typology

government impersonation (VA); benefits fraud; lookalike phone number; social-media ad lure; direct-mail lure; payment redirection

## Candidate detection signals (hypotheses)

- [hypothesis] Toll-free number registrations one edit away from published VA hotline numbers, matched against an official-number registry (typo-squatting in the phone space).
- [hypothesis] Social ads referencing "veterans grants" that lead to domains with no .gov or accredited-VSO presence and request direct-deposit changes.
- [hypothesis] Inbound calls or mailers naming programs ("Veterans Savings Program") that have no matching entry in VA program directories.
- [hypothesis] Any upfront-fee demand tied to filing a benefits claim, which VA-accredited representatives are barred from charging.
