<p align="center">
  <img src="assets/banner.svg" alt="Nilson Lopes. Planning and MIS analyst. Data, BI and automation, grounded in operations." width="100%"/>
</p>

<p align="center">
  <a href="https://jounimn.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-live_site-FF4A2B?style=for-the-badge" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/nilsondgwm/"><img src="https://img.shields.io/badge/LinkedIn-Nilson_Lopes-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Carmo,_RJ-Brazil-1f2933?style=for-the-badge" alt="Carmo, RJ, Brazil"/>
</p>

> I learned the network from the inside, then the operation, then the data behind it. That is why my dashboards get used: I have sat on the side of the desk that reads them.

<img src="assets/divider.svg" width="100%" alt=""/>

### At a glance

| | |
|---|---|
| **Role** | Planning & MIS Analyst (Jr.) at Alloha Fibra |
| **Works on** | Business metrics, Power BI dashboards, data pipelines, automations, RPA and AI agents |
| **Languages** | Português, English (Cambridge PET), SQL, Python |
| **Superpower** | Turning "we update this by hand every morning" into "it refreshes itself" |
| **Believes** | A KPI nobody trusts is worse than no KPI. If it can run on a free tier, it should. |

<img src="assets/divider.svg" width="100%" alt=""/>

### Where most of my work lives: Alloha Planejamento

The code belongs to the company and stays private, so each tool is told as a short story: what was broken, what I did, and what changed. The longer version, with an animated demonstration of each tool, is on the [portfolio site](https://jounimn.github.io/portfolio/#alloha).

<table>
<tr>
<td width="50%" valign="top">

#### Dispatch report collector
<sub>Report collector</sub>

Dispatch reports arrived scattered, and someone gathered and read them by hand every round. I started by mapping how each report arrives and what each reading needs to show. Then I wrote a collector that reads the files, standardizes the fields and puts everything in one place. Reading no longer depends on manual assembly: the team looks at organized data instead of preparing it.

</td>
<td width="50%" valign="top">

#### Reddir presentation refresh
<sub>Presentation automation</sub>

The follow-up presentation was rebuilt by hand at every update. I listed what changed each cycle and what stayed fixed, and separated the data source from the presentation layout. That made automation possible: the numbers go in and the presentation rebuilds itself. Updating stopped being a task of every cycle and now runs on its own.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### M code parameterizer
<sub>Power Query tool</sub>

In Power Query, every query had values locked into the code, and changing a source or a filter meant rewriting and checking everything by hand. I identified what changed from one query to the next, took those values out of the code and created named parameters. Then I built the tool that generates the M code from them. Changing a source became adjusting a parameter, with less rework and fewer typing errors.

</td>
<td width="50%" valign="top">

#### [Planning Intelligence](https://github.com/jounimn/website-analytics)
<sub>Data pipeline · public sample</sub>

Planning lived in a huge tree of spreadsheets, hard to trace and hard to reuse in analysis. I read the structure of the tree, defined what each level means, and built a versioned, provider-independent pipeline covered by tests, where every value comes out with its origin. The result is a structured dataset in which you can walk from the number back to the cell. The public sample is sanitized; names and data are fictional.

</td>
</tr>
</table>

**Side project: df-DnD** (on hold, private). A character-sheet app that keeps the rules of each D&D edition (AD&D 2e, 5e 2014 and 5e 2024) separate, so the math is right for whichever one the table plays, with a print-ready sheet. Built with Next.js and Supabase.

<img src="assets/divider.svg" width="100%" alt=""/>

### The route so far

```mermaid
timeline
    2021 : Design : print and web graphics at a language school
    2023 : Networks : GPON, ONU provisioning, DHCP, WAN, L1 to L2 support, supervision assistant
    2024 : Operations : Control Desk B2C, real-time ops, SLA, KPIs, Power Query ETL
    2026 : Data : Planning & MIS, metrics, Power BI, pipelines, automations
```

<img src="assets/divider.svg" width="100%" alt=""/>

### Toolbox

<p>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Power_Query-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power Query"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="Excel"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code"/>
</p>

<details>
<summary><b>How I build</b></summary>
<br/>

```mermaid
flowchart LR
    A[Idea] --> B[Brainstorm the spec]
    B --> C[Plan in small tasks]
    C --> D[Failing test]
    D --> E[Make it pass]
    E --> F[Review by a second agent]
    F -->|needs fixes| D
    F -->|clean| G[Ship]
```

I pair with AI agents the way I would pair with a senior dev: every change gets a plan first, a test second, code third, and a review before it merges.

</details>

<details>
<summary><b>In the lab (private, for now)</b></summary>
<br/>

| Project | What it is |
|---|---|
| **Social Media Content Factory** | Provider-agnostic AI media generation (image, video, voice) orchestrated by n8n, with a provider registry, automatic fallback and scheduled health checks. The goal is zero or near-zero cost. |
| **Local business websites** | Conversion-focused sites for businesses in my region, with end-to-end tests, accessibility checks and LGPD-compliant privacy pages. |

</details>

<img src="assets/divider.svg" width="100%" alt=""/>

<p align="center">
  <b>Open to conversations about data, BI, automation and AI tooling.</b><br/>
  <sub>Best way to reach me: <a href="https://www.linkedin.com/in/nilsondgwm/">LinkedIn</a></sub>
</p>
