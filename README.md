<div align="center">

<a href="https://tobyn-smith.github.io/energyosint/">
  <img src="https://raw.githubusercontent.com/tobyn-smith/energyosint/main/outputs/exposure_map.png" width="100%" alt="US grid exposure map">
</a>

# Tobyn Smith

**Energy security · Critical infrastructure · OSINT**

<a href="https://tobyn-smith.github.io/me/"><img src="https://img.shields.io/badge/Bio-111111?style=for-the-badge&logoColor=white" alt="Bio"></a>
<a href="https://www.linkedin.com/in/tobyn-smith"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://substack.com/"><img src="https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white" alt="Substack"></a>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white">
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Quarto-75AADB?style=flat-square&logo=quarto&logoColor=white">
<img src="https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white">
<img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white">

</div>

---

International Relations graduate with a research focus on **energy security and the politics of
critical infrastructure**. Coding is a hobby. The projects below are independent research
projects.

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Grid Resilience Exposure Index](https://github.com/tobyn-smith/energyosint)

<a href="https://tobyn-smith.github.io/energyosint/">
  <img src="https://raw.githubusercontent.com/tobyn-smith/energyosint/main/outputs/ranked_states.png" width="100%" alt="Ranked states">
</a>

One 0–100 exposure score for all 50 US states, built only from public EIA, EPA and NOAA data.

`Python` `R` `SQLite` `FastAPI` `geopandas`

**[Interactive deck](https://tobyn-smith.github.io/energyosint/)** · **[Georgia deep dive](https://tobyn-smith.github.io/energyosint/georgia.html)** · [Methodology](https://github.com/tobyn-smith/energyosint/blob/main/METHODOLOGY.md)

</td>
<td width="50%" valign="top">

### [Baltic Energy Transit Risk](https://github.com/tobyn-smith/transit)

<a href="https://tobyn-smith.github.io/transit/">
  <img src="https://raw.githubusercontent.com/tobyn-smith/transit/main/docs/assets/og.png" width="100%" alt="Baltic LNG transit risk">
</a>

How concentrated and exposed Baltic LNG infrastructure became after 2022, by capacity, distance and chokepoint.

`R` `sf` `Quarto` `Natural Earth`

**[Interactive site](https://tobyn-smith.github.io/transit/)**

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

### [Schedule Reader](https://github.com/tobyn-smith/reader)

Parses course syllabi and tracks weekly readings. Runs entirely in the browser via WebAssembly. No upload, no account, no keys.

`Python` `WASM` `PDF.js` `Pyodide`

**[Try it](https://tobyn-smith.github.io/reader/)**

</td>
<td width="50%" valign="top">

### Findings at a glance

- Six states stay in the **top 10 under every weighting** tried
- Mississippi and West Virginia have the **two most fuel-concentrated** supplies in the country
- Damaging weather **barely predicts** storm-driven outage minutes (ρ = 0.21)
- Two Baltic terminals hold **~60% of regional LNG capacity**
- **Every Baltic cargo** transits the Danish Straits

</td>
</tr>
</table>

---

<details>
<summary><b>What the grid index actually found</b></summary>

<br>

| # | State | Score | Mostly driven by | Outage minutes, 2023 |
|---:|---|---:|---|---:|
| 1 | West Virginia | 100.0 | concentration | 752 |
| 2 | Mississippi | 99.4 | concentration | 878 |
| 3 | Maine | 93.0 | outages | 1,863 |
| 4 | Oklahoma | 76.6 | outages | 1,339 |
| 5 | Arkansas | 72.6 | thin spare capacity | 915 |

The same score means different things in different places. Mississippi and West Virginia top
the table on fuel concentration alone. Maine is third for the opposite reason: it has the least
concentrated fuel mix in the country and still lost thirty one hours of power in 2023. That
changes the policy lever, because spreading a fuel mix is not the same job as hardening lines.

<img src="https://raw.githubusercontent.com/tobyn-smith/energyosint/main/outputs/validation_storms.png" width="100%" alt="Storms against storm-driven outages">

Checked against NOAA's Storm Events Database, how much damaging weather a state gets barely
predicts how many outage minutes it loses to storms. Texas and Georgia log the most storm
events in the country and lose few minutes. Maine logs a fraction as many and lost the most.
An argument against treating exposure as fate.

</details>

<details>
<summary><b>How I work</b></summary>

<br>

- Public data only, cited, with the fallback state printed on every run
- Reproducible pipelines, not notebooks
- Tested where the maths matters
- Written for someone who has to think about policy, not wiring

</details>

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=tobyn-smith&show_icons=true&hide_border=true&hide_title=true&theme=graywhite&icon_color=0A66C2" height="150">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tobyn-smith&layout=compact&hide_border=true&theme=graywhite&langs_count=6" height="150">

</div>

## Contact

Further details on my background, writing, and how to reach me are available at **[tobyn-smith.github.io/me](https://tobyn-smith.github.io/me/)**.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" />
