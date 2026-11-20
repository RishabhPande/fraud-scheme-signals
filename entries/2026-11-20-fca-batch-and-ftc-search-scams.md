# FCA Warning List batch + FTC holiday search-scam alert (20 Nov 2026)

- **Recorded:** 20 Nov 2026
- **Sources:** FCA Warning List - https://www.fca.org.uk/consumers/warning-list-unauthorised-firms; FTC Consumer Alerts - https://consumer.ftc.gov/consumer-alerts
- **Why:** eight new warnings and one update dated 20 Nov at the morning read (full first page), one catch-up item published late 19 Nov after yesterday's read, plus a new FTC alert dated 19 Nov.

## Alerts

New on the FCA Warning List, first published 20/11/2026:

- **Blockholdings.co** - https://www.fca.org.uk/news/warnings/blockholdingsco (Chester address)
- **Fizino-groups.ltd** - https://www.fca.org.uk/news/warnings/fizino-groupsltd (domain-only identity)
- **CIPHERNEXUS** - https://www.fca.org.uk/news/warnings/ciphernexus (Wilmington, Delaware address)
- **citiprimecorporate.com (Clone of FCA authorised firm)** - https://www.fca.org.uk/news/warnings/citiprimecorporatecom-clone-fca-authorised-firm (clone posing as Citibank, N.A.; the genuine firm has no connection to it)
- **www.surexo.com** - https://www.fca.org.uk/news/warnings/wwwsurexocom (Canary Wharf, London address)
- **www.aimdigitalassets.org** - https://www.fca.org.uk/news/warnings/wwwaimdigitalassetsorg (London address, digital-assets branding)
- **Aurexoptions.net** - https://www.fca.org.uk/news/warnings/aurexoptionsnet (domain-only identity)
- **Globalcoretraders.com** - https://www.fca.org.uk/news/warnings/globalcoretraderscom (domain-only identity)

Updated on the list 20/11/2026:

- **Nuviobank.com** (first published 19/11/2026) - https://www.fca.org.uk/news/warnings/nuviobankcom

Catch-up, first published 19/11/2026 after yesterday's morning read:

- **BD Management Global Ltd** - https://www.fca.org.uk/news/warnings/bd-management-global-ltd (Covent Garden, London address; sites bdmbond.com and bdmfixedreturns.com)

FTC consumer alert, published 19/11/2026:

- **How to avoid holiday shopping scams in your search results** - https://consumer.ftc.gov/consumer-alerts/2026/11/how-avoid-holiday-shopping-scams-your-search-results

## Scheme

Per the FCA, the 20 Nov batch is nine unauthorised-firm items plus one clone: citiprimecorporate.com copies the identity of the genuine Citibank, N.A. to look authorised, the classic clone-firm play. The rest split between domain-only operations with no stated corporate details and firms fronting UK or US addresses, including BD Management Global Ltd, which pairs a London virtual-office-style address with bond and "fixed returns" sites that appeared after yesterday's read. Per the FTC, scammers buy paid search ads so their fake shops sit at the top of results next to legitimate retailers, catching shoppers hunting hard-to-find items; its counters are to scroll past the ads to organic results, search the seller's name with "complaint" or "scam", and type known web addresses directly.

## Typology

unauthorised firm; clone firm (authorised-firm impersonation); domain-only identity; fixed-returns / bond lure; digital-assets branding; search-ad impersonation; malvertising; progressive-publication read lag

## Candidate detection signals (hypotheses)

- [hypothesis] A firm whose name or domain closely imitates a well-known authorised institution (misspellings, "corporate"/"prime" affixes) while giving contact details that differ from the register entry - clone-firm marker.
- [hypothesis] "Fixed returns" or bond-style products from firms with no authorisation, especially paired with prestigious-area addresses that correspond to virtual offices.
- [hypothesis] Paid search ads for retail or financial brands where the landing domain differs from the brand's canonical domain; top-of-results placement used as a trust proxy.
- [hypothesis] Warnings updated within 24 hours of first publication (Nuviobank.com) mark operations whose infrastructure is still being assembled; watching fresh warnings for next-day edits surfaces added domains early.
- [hypothesis] Brand-family clustering: same-day appearance of lookalike naming families (here "Aurex": aurexvixtrade.net on 19 Nov, Aurexoptions.net on 20 Nov) suggests a shared operator cycling domains.

## Other sources

- OFAC recent actions: nothing new since 19 Nov 2026 (18-19 Nov actions recorded in watchlist-diff).
