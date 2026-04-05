# Competitive Intelligence from Scientific Literature & Patents

Mapping who is doing what, with what funding, at what maturity, and what it means for your position. This is strategic reading — not evaluating the science, but evaluating the landscape.

## Intelligence Sources

### Academic Publications
- **What they reveal:** Technical capabilities, preliminary results, research direction
- **What they don't reveal:** Timeline, funding level, commercial intent, unpublished failures
- **Lag time:** 6-18 months from experiment to publication (faster for preprints)

### Patents and Patent Applications
- **What they reveal:** Commercial intent, claimed scope, specific embodiments
- **What they don't reveal:** Whether it actually works at scale, commercial progress
- **Lag time:** 18 months from filing to publication (for applications); may be granted years later
- **Key signal:** A company filing patents in an area = serious commercial interest

### Funding Announcements
- **DOE, DARPA, ARPA-E, NSF awards** are publicly searchable
- **SBIR/STTR awards** reveal startup activity in the space
- **Federal Reporter / USASpending.gov** for US government awards
- **CORDIS** for EU-funded projects
- **Key signal:** Multiple groups funded in the same area = agency believes the field is ready

### Conference Presentations and Abstracts
- **Most current data** — often 6-12 months ahead of publications
- Poster sessions especially — less formal, more preliminary, sometimes more revealing
- Conference proceedings and abstract books are searchable

### Job Postings
- A company hiring for "lignin valorization scientist" or "metabolic engineer — aromatic catabolism" signals active programs
- Tracks emerging competitors before they publish

### Press Releases and News
- Usually overhyped but signal strategic direction
- Partnership announcements reveal who is working with whom

---

## Landscape Mapping Protocol

### Step 1: Identify Active Groups

Create a tracker of groups actively publishing or patenting in the relevant space:

| Group | Institution | Focus | Key People | Recent Output | Funding |
|-------|-----------|-------|------------|---------------|---------|
| Beckham Lab | NREL | Biological funneling, P. putida | Gregg Beckham | Science Advances 2023 (β-KA, 44.5 g/L) | DOE BETO |
| Donohue Lab | UW-Madison/GLBRC | N. aromaticivorans, PDC | Tim Donohue | ACS ES&T Eng 2026 (PDC MBR) | DOE GLBRC |
| Kamimura Group | Nagaoka U. | SYK-6 platform, PDC | Naofumi Kamimura | JAFC 2026 (SYK-6 BL) | JSPS |
| Sels Group | KU Leuven | RCF catalysis | Bert Sels | Nat Commun 2022 (RuN/ZnO/C) | EU Horizon |

### Step 2: Map Technical Positions

For each group, assess their position on your pipeline:

```
FA1 (Deconstruction):
├── RCF specialists: Sels (KU Leuven), Luterbacher (EPFL), Román-Leshkov (MIT)
├── C-C cleavage: Stahl (UW-Madison), Wang (Dalian), Electrocatalytic (multiple)
└── Enzymatic: Masai/Kamimura (SYK-6 enzymes), Bugg (Warwick)

FA2 (Conversion):
├── P. putida: Beckham (NREL), Nikel (DTU), Wierckx (Jülich)
├── N. aromaticivorans: Donohue (UW-Madison) [essentially sole group]
├── SYK-6: Masai/Kamimura (Nagaoka) [essentially sole group]
└── Other organisms: Johnson (NREL, Acinetobacter), Vardon (NREL, Rhodococcus)
```

### Step 3: Assess Competitive Threats

For each competitor, evaluate:

| Dimension | Assessment |
|-----------|-----------|
| **Technical overlap** | How similar is their approach to ours? |
| **Maturity** | Lab → bench → pilot → demo → commercial |
| **Funding** | What programs fund them? Competing for the same programs? |
| **IP position** | Have they filed patents that could block us? |
| **Partnership potential** | Could they be a collaborator instead of a competitor? |
| **Publication velocity** | How fast are they publishing? (Signals activity level) |

### Step 4: Identify White Space

Map what's NOT being done:
- Combinations no one has tried (e.g., specific catalyst + specific organism)
- Feedstocks not yet tested (the Fleetwood "feedstock-agnostic" requirement)
- Scale-up gaps (most work is bench-scale)
- Integration gaps (chemical + biological integration is rare)
- Economic analysis gaps (few TEA studies on real process data)

White space = opportunity for differentiation in proposals.

---

## Patent Landscape Mapping

### Building a Patent Map

For a defined technology area (e.g., "lignin depolymerization + biological conversion"):

1. **Search broadly** — capture 50-200 relevant patents/applications
2. **Triage** — sort into "directly relevant," "adjacent," and "background"
3. **Map by assignee** — who owns what?
4. **Map by claim type** — method claims, composition claims, product claims
5. **Map by filing date** — activity trends over time
6. **Identify blocking patents** — patents that could prevent your approach

### Patent Landscape Table

| Patent/Application | Assignee | Filing Date | Key Claims | Relevance | FTO Risk |
|-------------------|----------|-------------|------------|-----------|----------|
| US 11,XXX,XXX | NREL | 2022 | Engineered P. putida for muconate from lignin | High | Medium |
| WO 2024/XXXXXX | KU Leuven | 2023 | RCF catalyst composition | Medium | Low (different catalyst) |

### Trend Analysis
- Increasing patent filings = growing commercial interest
- Shift from academic to corporate assignees = technology maturation
- Convergence of claims toward specific methods = emerging standard approaches
- Geographic distribution of filings = market targeting

---

## Competitive Intelligence Output

### Landscape Brief (1-2 pages)
For executives or proposal teams, summarizing the competitive landscape:

1. **Key competitors** (top 5-10) with 2-sentence assessments
2. **Technology maturity map** (where the field stands)
3. **Our differentiation** (what we do that others don't)
4. **Threats** (what could undermine our position)
5. **Opportunities** (gaps we can exploit)

### Detailed Competitor Profile
For deep-dive on a specific competitor or group:

```
## Competitor Profile: [Group/Company]

**Overview:** [1-2 sentences]
**Key people:** [Names, roles]
**Technical focus:** [What they work on]
**Recent publications:** [Last 2-3 years, most relevant]
**Patents:** [Filed/granted, key claims]
**Funding:** [Known grants, awards]
**Facilities/Scale:** [What infrastructure they have]
**Strengths:** [What they do well]
**Weaknesses:** [Where they're limited]
**Relationship to our work:** [Competitor, potential collaborator, or neutral]
**Recommended action:** [Monitor, engage, differentiate, etc.]
```
