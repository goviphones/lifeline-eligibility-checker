# Lifeline Eligibility Checker (2026)

A free, self-contained web tool that helps US households check whether they likely
qualify for the federal **Lifeline** program discount on phone or broadband service.

Just open `index.html` in any browser. No build step, no dependencies, no data
leaves your device: everything runs locally in the page.

## What it checks

* **Income route:** household income at or below 135% of the 2026 federal poverty
  guidelines (e.g. $21,546/year for a one-person household in the 48 contiguous
  states and DC; full 1-8+ person table included).
* **Program route:** participation in Medicaid, SNAP/EBT, SSI, Federal Public
  Housing Assistance, Veterans Pension/Survivors Benefit, or qualifying Tribal
  programs.
* **Benefit shown:** up to $9.25/month standard, or up to $34.25/month on
  qualifying Tribal lands.

## Important

This tool gives an **estimate only**. It is not an official eligibility
determination and not an application. Official eligibility is verified through
USAC's National Verifier (Oregon and Texas use state processes). Only one
Lifeline benefit is allowed per household.

## Data sources

* HHS 2026 Federal Poverty Guidelines (48 contiguous states + DC)
* FCC/USAC Lifeline program rules ($9.25 standard / $34.25 Tribal benefit)

## License

MIT. See LICENSE.

## More resources

Full 2026 Lifeline Eligibility & State Carrier Comparison guide:
https://goviphone.com/ and https://goviphone.com/plans/

Gov iPhone is an independent resource, not a government agency, and is not
affiliated with USAC or the FCC.
