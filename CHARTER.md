# Studio Charter: <project name>

> Filled in live during the **Studio Charter** session in week 3. Every section below is committed in the same commit at the end of that class block. See [Studio Charter (single-session inception)](https://courses.lpcordova.phd/data510/project-framework/charter-inception.html) for the script and time-boxes.

**Owner team:** Dane Herrin, Alexander Jackson

**Owner Product Lead:** Dane Herrin

**Peer Stakeholder POs:** Ben Dyer, Luca Casano, Manish Reddy Kallu

**Instructor / Sponsor:** Lucas Cordova (`LucasCordova` on GitHub)

**GitHub repo:** https://github.com/awjackson00/data510--Quant-Back-Testing-/

**GitHub Projects board:** <link>

**Discord category:** `#Project 4`

**Studio Session:** 3

**Studio formed:** 5/25/2026

## Vision

To create an innovative lens through which shareholders can view risk and portfolio construction by evaluating how different asset allocations perform during periods of financial uncertainty. This project aims to move beyond return-focused investing and develop a more disciplined framework for balancing projected gains, diversification, and drawdown resistance.

## Mission

This project aims to develop a portfolio optimization framework that balances projected gains with drawdown resistance. By testing specially constructed portfolios across historical market crises, the project will evaluate which asset allocations, sectors, and diversification strategies produce stronger risk-adjusted performance. The broader goal is to help shareholders make more disciplined investment decisions by understanding not only how portfolios grow in normal markets, but also how they survive during financial uncertainty.

## Context

- **Users / affected parties:** who benefits, who is at risk, who might use the result.
    - Financial Analysis
    -  Investment Firms
    -   Independent Investors
    - Portfolio Managers,
    - Retail Investors
    - Investment Clubs
    -  Financial Educators
    -   Institutional investors
    -    Anyone seeking building asset portfolios (wanting to resist asset volatility)

- **Data sources (proposed):** named sources, access status, license / ethics notes.


  
- **Constraints:** time, compute, access, skills, scope.

*1. Data Availability*

The project depends on access to reliable historical financial data for stocks, ETFs, sectors, and benchmarks. Some data sources may have missing values, limited history, adjusted prices, or restrictions on download volume.

*2. Crisis Period Selection*

The results will depend heavily on which financial crises are selected. A portfolio may perform well during one crisis but poorly during another, so the project needs a clear and limited set of crisis periods, such as the 2008 financial crisis, COVID-19 crash, and 2022 inflation/rate-hike period.

*3. Portfolio Scope*

The number of student-constructed portfolios must stay manageable. Too many portfolios, assets, or rebalancing rules could make the analysis too broad for one term.

*4. Asset Comparability*

Different portfolios may contain different asset types, such as stocks, ETFs, bonds, crypto, or commodities. To keep the project fair and comparable, the analysis may need to use standardized asset classes or ETF proxies.

*5. Backtesting Assumptions*

Backtesting requires assumptions about starting capital, portfolio weights, rebalancing frequency, transaction costs, dividends, and whether short selling is allowed. These assumptions can significantly affect results.

*6. Historical Bias*

Past performance does not guarantee future results. The project can show how portfolios would have performed historically, but it cannot prove how they will perform in future crises.

*7. Investment Advice Risk*

The project should be framed as an educational analysis, not financial advice. Results should not be presented as recommendations to buy, sell, or avoid specific assets.

*8. Time and Technical Scope*

The project must be realistic for a term-length capstone. The analysis should focus on a small number of crisis periods, a clear set of portfolios, and a manageable number of performance metrics.

*9. Student Privacy and Fairness*

If student-created portfolios are used, they should be anonymized. The goal should be to analyze portfolio construction patterns, not embarrass or rank individual students.

*10. Market Regime Differences*

Each crisis has different causes, such as credit collapse, pandemic shock, inflation, or interest-rate changes. The project must be careful when comparing results across crises because the same portfolio may react differently depending on the type of market stress.
  
- **Ethics risks:** consent, retention, PII, fairness, deployment risk.
  
  Due to the nature of the data that we are sourcing, currently there are no ethical concerns. All of the data is public, and all of the corporations we would be looking into are publicly traded. All the industries we would be comparing against, post their data publicly. The only concern could be that we would be taking aggregates and averages, which is not a complete look into specific industries / areas.

## Success criteria by milestone

- **M1, proposal (W4):** Complete proposal, research questions, scope of work, and next steps
  
- **M2, data summary (W7):** All historical data is collected, pipeline established, EDA started
  
- **M3, poster rough draft (W10):** Digital mock up of the poster fully done with all information on it (graphs, findings, research questions)
  
- **M4, write-up rough draft (W12):** Write the research paper and checked it by the professor.
  
- **M5, final write-up and poster (W14):** Physical copies of both that is checked by the professor and exceeds the rubric.

## Working agreements (internal to owner team)

- **Sync rhythm:** <e.g., one async standup per weekday in `#<project>-standup`>
  - Async and check-in (Fridays 8pm, potental call 7pm)
    
- **Code review:** <who reviews what, by when
  - Both check over eachother code (due by Fridays 8pm)
    
- **Decision rule:** 
  - Talk through, Dane has final say

## Working agreements (triad with peer POs)

- **Studio Brief due:** <example: by 5 pm the day before class, committed to `studio/briefs/W<NN>-<peer>.md` and linked in `#<project>-studio` on Discord>. If the owner team needs the peer POs to read or review something specific *before* the Studio Session (a data preview, model results, a draft figure), file the Brief earlier so the peer POs actually have time to do that homework. Otherwise the default is "before the Studio Session starts."
- **Studio Critique due:** <example: by the end of class for the in-person discussion, or at an agreed-upon time within one day after class (e.g., 5 pm the next day) if the peer PO needs extra time to draft a thoughtful write-up>.
- **Priority conflict resolution:** owner team integrates briefs in good faith; the instructor arbitrates (as Process Expert) if peer POs and owner team disagree.

## Response SLAs (Service Level Agreements)

A **Service Level Agreement** is a written promise the triad makes about *how fast* each side responds when a specific signal arrives. Every row must have an answer before this Charter is committed. See [Response SLAs](https://courses.lpcordova.phd/data510/project-framework/charter-inception.html#response-slas-service-level-agreements) for the full definition.

| When this signal arrives... | Who responds | By when |
|-----------------------------|--------------|---------|
| Peer PO files a **Studio Brief** (commits to `studio/briefs/...`, links in `#<project>-studio`) | Owner team | <e.g., acknowledge in `#<project>-studio` within 24 hours, with a first-pass adopt / defer / decline call for each item> |
| Peer PO files a **Studio Critique** | Owner team | <e.g., respond in `#<project>-studio` within 24 hours and capture follow-up items into the backlog> |
| Owner team posts an **Iteration Review** in `README.md` | Both peer POs | <e.g., read before filing the next Brief and Critique> |
| Owner team flags a **blocker** in `#<project>-blockers` | Instructor, plus any tagged peer PO | <e.g., responds by the next Studio Session at the latest; faster if online> |
| Anyone asks a clarifying question in `#<project>-general` | Whoever is tagged (default: owner team) | <e.g., reply within 48 hours, even if the reply is "we will look at this next iteration"> |

## Definition of Ready (PBI)

A PBI is ready to be pulled out of `Backlog` and moved into `Create` when it has:

- A one-sentence hypothesis or user story.
- A named **Create**, **Observe**, **Analyze** triple.
- A milestone tag (`M1-proposal`, `M2-data-summary`, `M3-poster-draft`, `M4-writeup-draft`, `M5-final`, `infra`, `ethics`).
- A T-shirt size estimate (S, M, L, XL).
- WIP slack on the board: `Create + Observe + Analyze` is below the team's WIP cap (owners + 1).

## Definition of Done (PBI)

A PBI is done, and may be moved from `Analyze` into `Done`, when:

- The Create artifact is in the repo or linked from the issue.
- The Observe results are recorded somewhere referenceable (notebook output, processed dataset, draft results section).
- The Analyze writeup names a next step (continue, pivot, kill, or decompose into new PBIs).
- A peer PO has either signed off in `#<project>-studio` or filed a Studio Critique covering it.
- The card is linked under *Completed PBIs* in the next Iteration Review in `README.md`.

## Context map

> Optional. Replace this block with a Mermaid `flowchart LR` showing how users, data, constraints, and ethics risks flow into the owner team and out to the capstone outcome. See the [`charter-inception.qmd` template](https://courses.lpcordova.phd/data510/project-framework/charter-inception.html) for a starting Mermaid diagram.

## Stakeholder alignment memo (one-page summary)

### Why we exist
<two sentences from Vision and Mission>

### What we will deliver to peer POs every week
- An Iteration Review in this `README.md` by <day / time>
- A summary of which Studio Brief items we adopted, deferred, or declined and why

### What we need from peer POs every week
- A Studio Brief by <day / time> next class (next iteration's requirements, questions, risks)
- A Studio Critique by <day / time> next class (assessment of last week's delivery)

### How to reach us
- Discord category: `#<project>-general` (day-to-day), `#<project>-studio` (Briefs and Critiques), `#<project>-blockers` (impediments)
- GitHub repo: <link>
- GitHub Projects board: <link>
