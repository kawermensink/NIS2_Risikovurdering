# NIS2 Risikovurdering
 
An Excel template for carrying out and documenting a systematic cybersecurity risk assessment under the Danish NIS2 Act (*Lov om foranstaltninger til sikring af et højt cybersikkerhedsniveau*), § 6, stk. 1, nr. 1.
 
The workbook is in Danish, sector-neutral, and can be adapted to any organisation covered by NIS2.
 
## What's inside
 
| Sheet | Purpose |
|---|---|
| **Vejledning** | Guide: purpose, process, scales, definitions and the 10 NIS2 measures in § 6, stk. 1 |
| **Risikovurdering** | The template you fill in: one row per risk, grouped into six risk categories |
| **Risikomatrix** | Auto-updating 5×5 risk matrix, before/after distribution and key figures per category |
| **Trusselskatalog** | Catalogue of suggested threats and vulnerabilities with IDs (e.g. `T-3.2 Ransomware`) |
| **Eksempel - Politik** | Example risk management policy you can adapt |
| **Eksempel - Risikovurdering** | Completed example for a fictional mid-sized company |
 
**Risk categories:** net- og informationssystemer · applikationer og tjenester · data og informationsaktiver · medarbejdere og processer · forsyningskæde · hændelser og beredskab
 
## How it works
 
Each risk is scored on two 1–5 scales:
 
- **Sandsynlighed** (likelihood within one year)
- **Konsekvens** (impact)
**Risikoscore = Sandsynlighed × Konsekvens** (1–25), calculated automatically:
 
| Score | Level | Handling |
|---|---|---|
| 1–4 | Lav | Can normally be accepted by the risk owner |
| 5–9 | Middel | Mitigate within a planned period; justify accepted residual risk |
| 10–25 | Høj | Requires action; residual risk must be approved by management |
 
Each assessment also records a **validitet** score (1–3) for how well-founded it is, existing and planned measures, a residual risk score (*restrisiko*), the responsible owner, and whether documentation exists.
 
## Getting started
 
1. Download `NIS2_Risikovurdering.xlsx` and open it in Excel (or another spreadsheet app that supports formulas).
2. Read **Vejledning**, then adapt **Eksempel - Politik** into your own risk management policy.
3. Fill in **Risikovurdering**. White cells are inputs; grey cells are calculated. Use **Trusselskatalog** for inspiration.
4. In **Risikomatrix**, set *Vis data fra* to `Risikovurdering` to see your own results (default shows the example).
5. Have management (*ledelsesorganet*) approve the result and residual risks, implement the measures, and review at least annually or after significant changes.
> **Note:** The assets, risks and ratings in the example sheets describe a fictional company. They are illustrative only. Always adapt them to your own organisation, IT environment, business model, threat landscape and maturity level.
 
## Useful links
 
- [SAMSIK – vejledning om cybersikkerhedsforanstaltninger](https://samsik.dk/wp-content/uploads/2025/08/Vejledning-til-implementering-af-cybersikkerhedsforanstaltninger.pdf)
- [SAMSIK – information om NIS2](https://samsik.dk/nis2/)
- [NIS2-tjek – er I omfattet?](https://www.nis2tjek.dk/)
## Disclaimer
 
This template is a support tool and does not constitute legal advice. Using it does not by itself ensure compliance with the NIS2 Act.
 
## Author
 
Developed by Kasper Mensink.
