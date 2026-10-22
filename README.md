# Paywall Audit — Deepstash

**Live:** https://bterzic123.github.io/deepstash-paywall-audit/

This audit covers the Deepstash iOS paywall. It has five ranked paywall ideas, each backed by a number from Adapty's State of Paywalls 2026, and a scorecard of the live paywall against the report. It also has a clickable rebuild of the paywall and the close moment in Deepstash's own design. The rebuild has a Today / Proposed switch, light/dark, EN / FR / ES and report pins.

| # | Idea | Report anchor | Outcome |
| :-- | :-- | :-- | :-- |
| 1 | Give the close a second chance | 4.5: only 4% of apps show a second paywall; it converts at 0.88× the main one and beats it in 45% of apps | ARPU +10–15% · based on Adapty data |
| 2 | Show both plans on the first screen | 5.2: number-of-plans changes win 57% of LTV tests (visual 35%); 3.2: only 12% hide plans behind "View all plans" | Report finding: wins 57% of plan-count tests (no 5.3 range) |
| 3 | Put your 4.8 and 10 million readers on the paywall | 3.1: 27% of top paywalls use social proof; 5.3 social proof on the paywall | CR +10–30% · observed in winning A/B tests |
| 4 | Name what they picked in the headline | 3.5: only 2% personalize the headline; 5.3 onboarding personalization | CR +8–17% · observed in winning A/B tests |
| 5 | Hold the X for three seconds | 3.7: 22% of apps delay the close button, 3–5 s is the most common delay; 5.3 delay before the close button | CR +8–15% · observed in winning A/B tests |

**Benchmark slice:** Education (App Store category) × all regions. App Store data, Oct 2025–Sep 2026.

**Report:** [State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=deepstash)

**Grounding.** Prices (€99.99 yearly shown as €8.33 a month, €22.99 monthly, 7-day trial on Yearly, "Save 64%") come from the live in-app paywall on a euro storefront. The 4.8 rating, "100K+ worldwide App Store ratings", "10,000,000+ people in the Deepstash Community" and Forbes / Mashable / Macworld / Entrepreneur come from Deepstash's own onboarding loading screen. The feature lines and 3D icons come from the paywall's "See what you get" view. The second-chance price (€54.99, €4.58 a month) applies the 45% off Yearly that Deepstash published in July 2026 to the €99.99 price. Nothing else is discounted. The headline example uses topics picked during onboarding (Philosophy, Mindfulness).

Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Deepstash.

Run locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
