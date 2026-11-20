# FTC Consumer Alerts, 29 Oct - 5 Nov 2026 (backfill roundup)

- **Dates:** 29/10/2026 - 05/11/2026 (recorded 07/11/2026)
- **Source:** FTC Consumer Alerts - https://consumer.ftc.gov/consumer-alerts
- **Why backfilled:** the daily read of the FTC listing page served a stale view and these alerts were missed when published. They are recorded here on first sighting, dated by their own publication dates.

## Alerts

- **Seeing lots of ads for health insurance plans during open enrollment? Read this** (29/10/2026) - https://consumer.ftc.gov/consumer-alerts/2026/10/seeing-lots-ads-health-insurance-plans-during-open-enrollment-read
- **Tell the FTC about imposter ads online** (02/11/2026) - https://consumer.ftc.gov/consumer-alerts/2026/11/tell-ftc-about-imposter-ads-online
- **Booking holiday travel? Hidden fees can cost you** (03/11/2026) - https://consumer.ftc.gov/consumer-alerts/2026/11/booking-holiday-travel-hidden-fees-can-cost-you
- **Help veteran-owned small businesses avoid scams during National Veterans Small Business Week** (05/11/2026) - https://consumer.ftc.gov/consumer-alerts/2026/11/help-veteran-owned-small-businesses-avoid-scams-during-national-veterans-small-business-week

## Schemes

- **Misleading health insurance ads** - during Marketplace open enrollment (Nov 1 - Jan 15), ads and phone pitches can promise comprehensive coverage but deliver limited-benefit plans or medical discount cards that are not insurance at all.
- **Imposter ads** - ads that pose as familiar businesses or government bodies, appearing in social feeds, search results and shopping platforms. The FTC is collecting reports of these ads.
- **Travel drip pricing** - extra charges tacked on late in a flight or hotel booking flow, or buried in fine print, so the real price appears only at payment or on the receipt.
- **Small-business impersonation scams** - timed to National Veterans Small Business Week, scams targeting veteran-owned businesses, including impersonation of government contracting and grant programs (per the alert's theme of informed-workforce defense).

## Typology

imposter advertising; misleading insurance marketing; drip pricing / hidden fees; small-business impersonation

## Candidate detection signals (hypotheses)

- `[hypothesis]` Seasonal scam cadence: open enrollment, holiday travel and awareness weeks predict spikes in themed lures; weight register and licence checks more heavily in these windows.
- `[hypothesis]` Ad-claim versus licence: an insurance ad whose seller is not a licensed broker or whose product is a discount card is a review signal when marketing says "comprehensive".
- `[hypothesis]` Price-shifting flows: a checkout that adds mandatory fees after the advertised price is a deceptive-pricing signal independent of the merchant's brand.

## Notes

The FTC also published a report on protecting older adults (04/11/2026); it is a report, not an alert, and is not summarised here. FTC pages are US consumer-education alerts, not enforcement findings against named firms.
