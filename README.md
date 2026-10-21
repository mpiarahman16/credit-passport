# Credit Passport

**A credit-building copilot for people new to the US.**

About 1 in 8 US adults has no scored credit record (CFPB, 2020 data). Many of them pay rent and bills on time every month, but the credit system can't see it. No history means no card, and no card means no history.

Credit Passport breaks that loop. A newcomer answers six questions, with no credit check and no account numbers, and gets a personalized 6–12 month plan that explains every step in plain language.

**[Try the live prototype →](https://YOUR-USERNAME.github.io/credit-passport/)**

## What it does

- **Six-question intake:** time in the US, taxpayer ID (SSN, ITIN or not yet), income, rent, savings and goal
- **Personalized recommendations:** secured card, rent reporting, credit-builder loan, utility and phone reporting, and home-country credit history where relevant
- **Plain-language reasoning:** each step says why it fits this person, with their own numbers (for example, "keep each statement under $30")
- **Month-by-month timeline:** milestones shown as passport stamps, including when a first FICO score is likely
- **Transparency panel:** lists exactly which inputs shaped the plan, and which data is never used (age, gender, race, religion, country of birth)

## Product decisions

| Decision | Why |
|---|---|
| No credit check or account numbers at intake | Newcomers are wary of hard pulls and sharing data with a brand-new app; trust comes first |
| Rules-based, explainable recommendations | Every suggestion can be traced to an input, which supports fair lending reviews and adverse-action-style explanations |
| Rent reporting framed as a boost, not the base | Not every scoring model counts rent data |
| Taxpayer ID handled as step zero | Credit files are matched to an SSN or ITIN; nothing else works without one |

## Why it matters to a bank or card network

- Brings well-prepared, first-time customers into secured and starter products
- Builds trust with an underserved segment early, which supports long-term retention
- Designed with explainability and responsible AI from the first screen

## Status

Prototype with fictional example profiles (Sofia, Diego, Li). It offers education and planning, not credit decisions or financial advice. Built as a single HTML file with no dependencies beyond Google Fonts.

## About

Product concept and prototype by **Pia Rahman**, two-time fintech co-founder and product leader with 10+ years across fintech, regulatory reporting and accounting software.
