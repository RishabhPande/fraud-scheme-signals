# FCA Warning List: 29 new unauthorised-firm warnings (06/11/2026)

- **Date added:** 06/11/2026
- **Source:** FCA Warning List - https://www.fca.org.uk/consumers/warning-list-unauthorised-firms
- **Correction (07/11/2026):** the first version of this entry listed the 10 warnings seen when the list was first read that morning. The FCA kept publishing through the day; this version covers the full batch of 29 new warnings dated 06/11/2026, plus one update.

## Alerts

Twenty-nine warnings first published 06/11/2026:

- **www.rubizio.com** - https://www.fca.org.uk/news/warnings/wwwrubiziocom (40 Bank Street, Canary Wharf)
- **www.nex-investment.com** - https://www.fca.org.uk/news/warnings/wwwnex-investmentcom
- **www.icumarkets.com** - https://www.fca.org.uk/news/warnings/wwwicumarketscom (Tooley Street, London)
- **www.vyberfx.net** - https://www.fca.org.uk/news/warnings/wwwvyberfxnet (Harpenden)
- **www.primemineblock.com** - https://www.fca.org.uk/news/warnings/wwwprimemineblockcom (Kemp House, City Road)
- **REVOLVE TRUST** - https://www.fca.org.uk/news/warnings/revolve-trust ("401 Broadway, 24th Floor, Orchard View, London" - a New York street name given as a London address)
- **Mega Pro Forex Trade** - https://www.fca.org.uk/news/warnings/mega-pro-forex-trade (One Canada Square, Canary Wharf)
- **www.apex-globalassets.com** - https://www.fca.org.uk/news/warnings/wwwapex-globalassetscom (Newhaven)
- **Crypto Global Brokerage** - https://www.fca.org.uk/news/warnings/crypto-global-brokerage
- **Invexel FX Trade** - https://www.fca.org.uk/news/warnings/invexel-fx-trade (85 Great Portland Street, London)
- **Veracore Finance** - https://www.fca.org.uk/news/warnings/veracore-finance
- **smartea.trading** - https://www.fca.org.uk/news/warnings/smarteatrading
- **First Islamic Cooperative Investment Bank PLC** - https://www.fca.org.uk/news/warnings/first-islamic-cooperative-investment-bank-plc
- **Nova Financial group limited or NV-Group** - https://www.fca.org.uk/news/warnings/nova-financial-group-limited-or-nv-group
- **marketexpertgroup.co.uk** - https://www.fca.org.uk/news/warnings/marketexpertgroupcouk
- **ottowealthpartners.com** - https://www.fca.org.uk/news/warnings/ottowealthpartnerscom
- **divinegold.co.uk** - https://www.fca.org.uk/news/warnings/divinegoldcouk
- **wealthstockltd.co.uk** - https://www.fca.org.uk/news/warnings/wealthstockltdcouk
- **tuffminers.org** - https://www.fca.org.uk/news/warnings/tuffminersorg
- **rmtradingltd.com** - https://www.fca.org.uk/news/warnings/rmtradingltdcom
- **intelliwealthgp.com** - https://www.fca.org.uk/news/warnings/intelliwealthgpcom
- **gforex.co.uk** - https://www.fca.org.uk/news/warnings/gforexcouk
- **apexihl.com** - https://www.fca.org.uk/news/warnings/apexihlcom
- **davisandcole.com** - https://www.fca.org.uk/news/warnings/davisandcolecom
- **novabridgeinc.uk** - https://www.fca.org.uk/news/warnings/novabridgeincuk
- **algospheremarkets.com** - https://www.fca.org.uk/news/warnings/algospheremarketscom
- **fivonix.com** - https://www.fca.org.uk/news/warnings/fivonixcom
- **majestiglobal.com** - https://www.fca.org.uk/news/warnings/majestiglobalcom
- **profitaipilot.com** - https://www.fca.org.uk/news/warnings/profitaipilotcom

The FCA also updated its September 2020 warning on **ukisacomparison.com** (updated 06/11/2026) - https://www.fca.org.uk/news/warnings/ukisacomparisoncom

## Scheme

All 29 are firms the FCA lists as unauthorised, saying they appear to offer or promote financial services without FCA authorisation. The batch is dominated by FX, crypto, "AI trading" and "investment" brand names, several of which exist only as a domain; two present as banks. Several notices list London or UK addresses, including prestige ones (Canary Wharf twice) and well-known virtual-office or mail-drop addresses (Kemp House, 85 Great Portland Street). One notice mixes a New York street name with a London address. An address on a warning page is what the firm claims, not a verified location.

## Typology

unauthorised firm; fake trading / FX / crypto / AI-trading platform; fake bank; virtual-office and prestige-address dressing; batch publication pattern

## Candidate detection signals (hypotheses)

- `[hypothesis]` Address-versus-register: a claimed Canary Wharf or City address with no FCA or Companies House match is a review signal; prestige postcodes are cheap to print.
- `[hypothesis]` Address implausibility: geographic inconsistencies in a firm's stated address (foreign street names, virtual offices) combined with a new domain.
- `[hypothesis]` Burst publishing: a same-day cluster of warnings with similar naming (FX, mining, AI, brokerage) may reflect one operator network; shared addresses, phone blocks or site templates across the cluster are worth joining.
- `[hypothesis]` Trend naming: names riding current themes ("AI pilot", "smart trading") deserve the same register-absence check as older FX-style names.
- `[hypothesis]` Reading the list late in the day: large batches can publish progressively; a morning-only read undercounts a day like this one.

## Notes

FCA warnings concern authorisation status; they do not by themselves prove fraud. Phone numbers and emails from the notices are not reproduced here.
