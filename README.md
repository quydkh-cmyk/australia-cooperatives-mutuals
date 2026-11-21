# Australian Co-operatives and Mutuals: BCCM Data Exploration Dashboard

A Power BI dashboard, dataset and report built for the **Business Council of Co-operatives and Mutuals (BCCM)**, the peak body for Australia's co-operatives, mutuals and member-owned enterprises (CMEs). Project for BUSA3021 PACE: Business Analytics Project, Macquarie University, Semester 2, 2026.

## The problem

BCCM asked how Australia's CME sector can grow stronger. Its own reports describe the sector one year at a time. The people who use BCCM's data need answers that join data across sources, countries and years, which no single report gives. We harvested public data into one dataset and built a dashboard around three user personas, each with three questions.

| Persona | Role | What they need to know |
|---|---|---|
| Persona 1 | BCCM CEO | How far Australia's leading co-operatives are from French and US leaders, who could be a partner, and how stable those partners are |
| Persona 2 | BCCM Research officer | How the sector has grown, and where activity is concentrated by industry and state |
| Persona 3 | Housing Policy Analyst | Where co-operative housing could help most, and what growth it could support |

## What is in this repository

| Folder | Content |
|---|---|
| [`report/`](report) | Report (Word): design templates, data sample, visual answers, data quality and ethics, recommendations |
| [`data/`](data) | Dataset (Excel): a Metadata sheet plus 32 data tables, about 3,200 rows, from public sources only. The report refers to this file by its original submission name, `BUSA3021_Wed1230_Group1_Dataset.xlsx` |
| [`dashboard/persona-1-ceo/`](dashboard/persona-1-ceo) | Dashboard pages for Persona 1 (BCCM CEO), with problem, findings and recommendation for each page |

## Key findings and recommendations

### Persona 1: BCCM CEO

**Problem.** Is Australia's scale gap to France and the US closable by organic growth, and who should BCCM partner with?

**Key findings**
- Australia's leading co-operatives are **13 to 52 times smaller** than French and US peers, measured as turnover divided by GDP per capita (2022). The gap has not closed since 2018.
- Closing the gap in 10 years would need **29% to 48% growth a year**, and 14% to 22% over 20 years. Observed growth is about 0.4% a year in agri-food and 4.0% in retail and purchasing.
- France has 19 agri-food and 9 retail organisations in the World Cooperative Monitor Top 300, the US has 24 and 9. Australia has 1 in each.
- Co-operatives hold 24% of homes in Sweden and 14% in Norway, but 0.05% in Australia.
- Through FY2020-21, US dairy, US fruit and vegetables and Cooperl Arc Atlantique never fell below their 2019 revenue. Sodiaal Union was the least stable. French groups recovered in nominal terms but not after adjusting for inflation.

**Key recommendations**
1. Make partnerships a core part of BCCM's growth strategy, because organic growth cannot close the gap.
2. Open due diligence with the top five agri-food candidates, starting with In Vivo and Growmark, which run the same farm supply and grain marketing model as CBH. In retail, start with Leclerc and Système U after confirming their figures against a second source.
3. Favour partners that build their capital, and judge recovery after inflation, not in nominal revenue.
4. Treat housing as a growth opportunity (see Persona 3).

### Persona 2: BCCM Research officer

**Problem.** How has the sector grown, and is the growth spread across industries, states and organisations?

**Key findings**
- Between FY2017-18 and FY2024-25, turnover grew 59.44%, employment 55.67% and memberships 20.77%. Memberships fell 10.54% in FY2018-19.
- Financial Services is the largest industry (39 organisations, $191.2bn in assets in FY2024-25). Medical Services had the highest turnover growth (41.4%) and Motoring Services the highest EBIT margin (11.62%).
- New South Wales had the highest turnover in every year except FY2021-22 and FY2022-23, when Western Australia did.
- Australian Unity had the largest turnover increase and RAC the largest EBIT increase over two years.

**Key recommendations**
1. Track whether gains are shared as the sector grows, by comparing member benefits (rebates, discounts and dividends) with turnover growth each year.
2. Read industry and state views together. Where an industry or state is large but earns a low margin, ask whether members are well served before treating size as strength.
3. Ask the fastest-growing CMEs to report to members how growth in capital is used and how members can vote on it.

### Persona 3: Housing Policy Analyst

**Problem.** Where is housing stress worst, and what could co-operative housing contribute if it scaled?

**Key findings**
- New South Wales and Queensland hold **57%** of Australia's low-income households in rental stress but only **33%** of its rental co-operative households.
- Co-operative housing is 0.06% of Australian homes, against 4% to 19% in peer countries (Switzerland, Austria, Norway, Poland).
- The Top 100 co-operative and mutual sector grew turnover 54% from FY2020-21 to FY2024-25. Community housing households grew 53% from 2016 to 2025.
- A first step of 1% of homes needs about 4,300 homes a year, within what Austria's co-operative sector builds. Matching Switzerland would mean about 19,700 homes a year and 5,700 to 28,300 net jobs a year, depending on how much of the building is additional. These are scenarios, not forecasts.

**Key recommendations**
1. Start where need is greatest (New South Wales and Queensland) and learn from Victoria's common equity model.
2. Put in place the three enablers that worked overseas: long-term finance, access to land, and a legal model for co-operative housing.
3. Make the case with a first step and a range: 1% of homes, with net jobs shown across additionality scenarios.

## Data quality and limits

- Persona 1 figures use one year (2022 for the gap, 2023 for partner candidates) because that is the latest year with data for all three countries. Partner candidate figures are labelled "WCM only", meaning no second source has confirmed them.
- US figures in Persona 1's stability page are USDA sector totals, not individual organisations.
- Two figures appear on two bases across personas (Top 100 growth: 47.9% and 54.2%; co-operative housing share: 0.05% and 0.06%). The report explains each.
- Housing stress data pre-dates the 2022-26 rent rises.
- All data are published, aggregated, organisation-level figures. No personal data was collected.

## Data sources and rights

The dataset reuses published figures from BCCM National Mutual Economy reports, the World Cooperative Monitor (ICA and Euricse), Coop FR, the NCB Co-op 100, USDA, French group accounts, the World Bank, INSEE, the US Bureau of Labor Statistics, ABS, the Productivity Commission, PHIDU, Housing Europe, NHFIC and others. Full references are in the report. The original publishers keep their rights to their data; check each source's terms before reusing it.
