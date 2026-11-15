# 🇨🇦 Canadian Tech Hiring Calendar

A community-maintained tracker of **application opening dates, deadlines, and recruitment windows** for Canadian tech internships, co-ops, new-grad programs, and early-career roles.

**Focus:** Software Engineering · Data Science & Analytics · AI/ML · DevOps/SRE/Cloud · Cybersecurity · Product & Design

> **Last researched:** November 14, 2026. Historical recruiting dates are included to help plan future cycles; they are **not promises** that the same windows will recur. Always verify on the employer's application page.

## Quick navigation

- [How to use this tracker](#how-to-use-this-tracker)
- [Recruiting seasons](#recruiting-seasons)
- [Startups and scaleups: sourced examples](#startups-and-scaleups-sourced-examples)
- [By technical field](#by-technical-field)
- [By company scale](#by-company-scale)
- [Contribute](#contribute)

## How to use this tracker

- **Term** = when the internship takes place, **not** the application period.
- **Opens** = the employer's explicitly stated application-opening date. A first-seen posting date must instead be marked **First seen**.
- **Deadline** = employer-published closing date; `—` means not found.
- **Status** = `Past deadline`, `Upcoming deadline (verify)`, or `Window not verified`. We do **not** label listings open solely because a cached page is searchable.
- **Evidence** = employer posting wherever possible. Secondary sources are flagged.
- A company may appear in multiple technical fields. The tiers below reflect approximate scale and maturity, **not** a ranking of desirability.

## Recruiting seasons

| Work term | General planning period (not company-specific) |
| --- | --- |
| Winter (Jan–Apr) | Look for postings in the preceding summer and fall |
| Summer (May–Aug) | Start monitoring in late summer/fall of the preceding year; continue through winter |
| Fall (Sep–Dec) | Monitor the preceding spring and summer |

These are **general planning guidelines**, not verified application windows. Some startups recruit ad hoc or close listings as soon as positions fill.

## Startups and scaleups: sourced examples

Below are **2027 internship records backed by dated evidence**. All deadlines are listed in the employer's stated calendar date, without attempting to reconcile conflicting timezone metadata. None of these historical listings should be assumed open today.

| Company | Technical field | Term | Canada location | Opens | Deadline / evidence | Status | Source |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **Wealthsimple** | Software Engineering, Data Science | Winter 2027 | Toronto (hybrid) | Not published | **Sep 18, 2026** | Past deadline | [Employer listing](https://jobs.ashbyhq.com/wealthsimple/de09418a-8a12-46aa-a371-34bafaf5be26/) |
| **Super.com** | Software Engineering — Full Stack | Winter 2027 | Canada (remote) | Not published | **Sep 17, 2026** | Past deadline | [Employer listing](https://jobs.ashbyhq.com/super.com/b2615f7e-c6d2-46d6-9699-5027da9b5757) |
| **Super.com** | DevOps / Infrastructure | Winter 2027 | Canada (remote) | Not published | **Sep 17, 2026** | Past deadline | [Employer listing](https://jobs.ashbyhq.com/super.com/97bd1ee5-1b97-496b-836c-453d105f0eb3) |
| **Super.com** | Data Engineering | Winter 2027 | Canada (remote) | Not published | **Sep 17, 2026** | Past deadline | [Employer listing](https://jobs.ashbyhq.com/super.com/5251792e-093d-42c6-ae9e-08c656e90807) |
| **Harvey** | Software Engineering, Infrastructure | Winter 2027 | Toronto (hybrid) | Not published | **Oct 12, 2026** | Past deadline | [Employer listing](https://jobs.ashbyhq.com/harvey/d40e15aa-2351-4be8-ac8f-1faf60bfcdbf) |
| **NationGraph** | Software Engineering | Winter 2027 | Toronto (on-site) | Not published | **Oct 25, 2026** | Past deadline | [Employer listing](https://jobs.ashbyhq.com/NationGraph/a1bcdd3e-d863-42b6-8469-ec587190ad68/) |
| **Rivian and Volkswagen Group Technologies** | Software Engineering — Vehicle Controls | Jan–Aug 2027 | Vancouver (hybrid) | Not published | **Oct 9, 2026** | Past deadline | [Employer listing](https://jobs.ashbyhq.com/rivianvw.tech/e00c49b7-44c1-4f0c-af3c-2c7a7402185b) |
| **Lyft** | Backend Software Engineering | Summer 2027 | Montréal (hybrid) | **First seen Oct 24, 2026** (not confirmed opening) | **Nov 23, 2026** (third-party) | Upcoming deadline — **verify** | [Secondary listing](https://www.owlindex.com/service-explorer/internship-co-op-explorer/details/889a157b-f986-402a-8368-389f8139538f/) |

**Evidence policy:** A role enters this table only when its 2027 term **and a dated recruitment signal** (employer-published deadline or clearly labeled third-party first-seen date/deadline) can be documented. A listing's presence here does not prove that applications remain open. Lyft is included as a larger former-startup/scaleup comparison, not as an early-stage startup. Rivian/VW Technologies is a corporate joint venture, also included for ecosystem breadth rather than categorized as an independent startup.

## By technical field

| Field | Companies with sourced examples above |
| --- | --- |
| Software Engineering (frontend, backend, full stack) | Wealthsimple, Super.com, Harvey, NationGraph, Rivian/VW Technologies, Lyft |
| Data Science & Analytics | Wealthsimple |
| Data Engineering | Super.com |
| AI / Machine Learning | *No sufficiently dated company-specific example included yet* |
| DevOps / SRE / Cloud | Super.com, Harvey (infrastructure track) |
| Cybersecurity | *No sufficiently dated company-specific example included yet* |
| Product / UX | *No sufficiently dated company-specific example included yet* |

## By company scale

These are **informal organizational groupings**, not official revenue/headcount classifications:

- **Tier 1 — Large and global:** major technology employers and multinational organizations. *(To populate.)*
- **Tier 2 — Established and mid-sized:** mature Canadian technology employers. *(To populate.)*
- **Tier 3 — Startups and scaleups:** Harvey, NationGraph, Super.com, Wealthsimple. The remaining sourced examples are listed for completeness but need a scale-category review.

A useful future structure is `data/2027.csv` as the single source of truth, with fields:

```csv
company,role,field,company_tier,location,work_mode,term,application_opens,first_seen,deadline,status,source_url,last_verified,notes
```

Keep unknown values blank rather than guessing. One company can have multiple entries for different roles and terms.

## Contribute

Know a verified internship window? Open a pull request or issue with:

1. Company and exact role title
2. Canadian location or confirmation that remote work is Canada-eligible
3. Technical field, work term, and role type (intern/co-op/new grad)
4. Application opening date, **if explicitly published**
5. Application deadline, **if explicitly published**
6. Direct employer source link, access date, and any special eligibility conditions

**Verification checklist:** Prefer the employer's career site; don't confuse the internship start date with the application opening date; don't turn first-seen dates into officially announced opening dates; and mark expired positions as historical, not open. Preserve historical windows so future applicants can plan, but don't predict next year's exact dates.

## Disclaimer

This is an independent community project. It is not affiliated with the listed employers. Recruitment timelines can change without notice. Verify all eligibility criteria and submission deadlines directly before applying.

## License

Consider adding a `LICENSE` file (for example, MIT for code, or CC BY 4.0 for the curated dataset and documentation) before accepting contributions.

