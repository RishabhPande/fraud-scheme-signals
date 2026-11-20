# FTC: "The FTC is not calling to deactivate your phone number"

- **Date:** October 22, 2026
- **Source:** FTC Consumer Alert - https://consumer.ftc.gov/consumer-alerts/2026/10/ftc-not-calling-deactivate-your-phone-number

## Scheme

A caller claims to be an FTC official and says a phone registered under the
victim's name and number is being used in criminal activity. It is a government-impersonation script: manufactured authority plus urgency, designed to move the
victim toward "cooperating" - typically identity disclosure or payment.

## Typology

government impersonation; vishing; FTC impersonation

## Candidate detection signals (hypotheses)

- `[hypothesis]` Authority-plus-threat pattern: unsolicited contact combining a
  regulator/agency identity with a claim that the target is linked to a crime.
- `[hypothesis]` Channel anomaly: real agencies do not call to threaten account
  deactivation; contact initiated by the "agency" over voice is itself a signal.
- `[hypothesis]` Escalation marker: the script steers toward secrecy, urgency,
  or moving money/verifying identity within the first contact.

## Notes

FTC impersonation is a recurring family - the FTC maintains a standing page on
impersonators (https://consumer.ftc.gov/ftc-impersonators). Worth a typology
tag that aggregates across these alerts over time.
