# Trends in America, 1940–2024

An interactive, single-page data visualization of how the United States has changed across eight and a half decades — health, diet, the economy, crime and incarceration, politics and elections, demographics, mental health, homelessness, religion, culture, and more. Every chart is drawn from named, primary statistical sources (CDC, Census Bureau, BJS, HUD, FEC/National Archives, BLS, NIH/SAMHSA, USDA, and peer-reviewed literature), and a companion dossier documents the source behind each series.

## Live site (GitHub Pages)

### Data
[https://pilotsdiscretion.github.io/Trends_In_America_From_1940_2024/Trends_in_America_From_1940_2024.html](https://pilotsdiscretion.github.io/Trends_In_America_From_1940_2024/Trends_in_America_From_1940_2024.html)

### Citations and Sources
[https://pilotsdiscretion.github.io/Trends_In_America_From_1940_2024/Sources_and_Citations.html](https://pilotsdiscretion.github.io/Trends_In_America_From_1940_2024/Sources_and_Citations.html)

## What's inside

The dashboard is organized into topic tabs (listed alphabetically, with **Conclusion** always last):

Alcohol & Overdoses · Cancer · Crime Rates · Demographics · Diet & Nutrition · Economics · Entertainment · Fast Food · Gov. Spending · Healthcare · Homeless · Incarceration · Marriage & Family · Mental Health · Mortality · Obesity · Pharmaceuticals · Politics · Poverty · Religion · Sex & Partners · Vaccines · **Conclusion**

Each tab combines headline statistics, multiple charts, a "key timeline events" panel, and a methodology/footnote ("data note") explaining the series and its caveats.

### Highlighted sections

- **Politics & Elections** — every presidential election from 1940 to 2024 by popular vote and Electoral College; third-party and independent vote share; party identification over time (Gallup); voter turnout; and a full state-level breakdown shown three ways: an **interactive state picker**, a scrollable **winner heatmap** (all 50 states + DC × every election), and a **regional-realignment** view tracing the South's flip from Democratic to Republican.
- **Incarceration** — national rates plus breakdowns by state, by city/county jail system, by race, by most-serious offense, how that offense mix shifted over time, repeat-offending (recidivism), time served versus sentence imposed, and prison gangs / security threat groups.
- **Homeless** — total population over time (HUD point-in-time counts), by race, by gender, and serious mental illness as a function of the homeless population (general → sheltered → chronic → unsheltered).
- **Mental Health** — depression and antidepressant trends, deinstitutionalization, and common diagnoses over time (anxiety, depression, bipolar, schizophrenia) with prevalence and trend charts.
- **Alcohol & Overdoses** — per-capita alcohol use and the three opioid waves, including **fentanyl** as a share of all overdose deaths and its rise and recent decline.
- **Poverty** — official vs. Supplemental Poverty Measure over time, and breakdowns by age, race, gender/family structure, and state, alongside the economic drivers (unemployment, recessions, income, minimum wage).
- **Cancer** — incidence and mortality over time, the most common and deadliest cancers by type, 5-year survival over time and by type (treatment progress), survival by stage at diagnosis (why early detection matters), cancer-screening-rate trends, and how risk rises with age.
- **Vaccines** — measles/MMR coverage and case resurgence, the childhood immunization schedule's growth over time (doses and diseases protected), the current schedule broken down by individual vaccine (~60 doses by age 18), and autism-spectrum prevalence alongside the scientific consensus that vaccines do not cause autism.

## Features

- **Mobile-responsive with auto-detect** — the layout adapts to phones and tablets (single-column charts, resized typography, touch-friendly controls); on small screens the topic menu starts collapsed and closes itself after you pick a tab.
- **Collapsible topic header** — a "☰ Topics" toggle shows or hides the full tab list on any screen size.
- **Click-to-zoom charts** — every chart has a zoom (⤢) control that opens it full-screen for closer inspection; press Esc or click outside to close.
- **Interactive politics tools** — pick any state to see how it voted in every election against the national trend, and scroll the full state-by-election heatmap.

## Data & methodology

The project prioritizes accuracy. Figures come from the responsible statistical authority for each domain (for example: mortality and overdose data from CDC/NCHS; incarceration from BJS; homelessness from HUD's AHAR; poverty and demographics from the Census Bureau; election results from the FEC and National Archives; party ID and turnout from Gallup and the U.S. Elections Project). Where a series relies on estimates, changing definitions (e.g., DSM revisions, HUD's 2024 race/gender category changes), or pre-survey-era reconstructions, the relevant chart's data note says so. State-level presidential results reflect each state's statewide Electoral College winner; third-party state wins (1948, 1960, 1968) are marked separately, and exact state vote margins can be found via the MIT Election Data + Science Lab and Dave Leip's Atlas.

## Files

- `Trends_in_America_From_1940_2024.html` — the interactive dashboard (self-contained; loads Chart.js from a CDN).
- `Sources_and_Citations.html` — the primary-source dossier backing each data series.
- `README.md` — this file.

## Viewing locally

The dashboard is a single self-contained HTML file. Open `Trends_in_America_From_1940_2024.html` in any modern browser — no build step or server is required (an internet connection is used only to load the Chart.js charting library from a CDN).

## Tech

Plain HTML, CSS, and JavaScript with [Chart.js](https://www.chartjs.org/) for visualizations. No framework, no build tooling, no tracking.

## Disclaimer

This project is provided for general informational and educational purposes only, on an "as is" and "as available" basis, **without warranties of any kind**, express or implied, including accuracy, completeness, timeliness, or fitness for a particular purpose. The data is compiled from third-party public sources and **may contain errors, omissions, or out-of-date figures**. Nothing here is medical, legal, financial, or other professional advice. **Always verify any figure against the cited primary source before relying on it.** To the maximum extent permitted by law, PilotsDiscretion and contributors accept no liability for any loss or damage arising from use of, or reliance on, this project or its data. Use is at your own risk.

## Copyright

© 2026 [PilotsDiscretion](https://github.com/pilotsdiscretion). All rights reserved.
