---
layout: default
title: "Chapter 13: Statistics and Evidence Appraisal"
nav_order: 13
---

> **⚠️ AI-generated content — requires human review.**
> This chapter was produced automatically by a large language model and has not been verified by a clinician. It may contain errors or omissions. Do not rely on it for clinical decisions until it has been reviewed and approved by a qualified specialist.

# Chapter 13: Statistics and Evidence Appraisal

---

## Why this matters in anaesthesia

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


You make decisions under time pressure using imperfect evidence. A basic grasp of statistics helps you read a paper quickly, spot a trap, and apply guidance without blindly following or recklessly discarding it. You do not need to be a statistician — you need a reliable mental framework.

---

## Core concepts: effect, uncertainty, and bias

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


### Effect size

Every paper should answer: *what happened, and by how much?*

- **Absolute risk difference** tells you how many patients actually benefit. Relative measures (relative risk, odds ratio, hazard ratio) can make modest effects look impressive.
- Always ask: "What is the baseline risk?" A 50% relative risk reduction means very little if the baseline risk is 1%.
- **Minimal clinically important difference (MCID):** a result can be statistically significant yet clinically trivial. Ask whether the effect size would actually change what you do for a patient.

### Uncertainty

- **Confidence intervals (CIs)** express the range of plausible effects. Wide CIs mean the study is imprecise — be cautious about acting on it.
- **P-values** tell you how likely your result is under the null hypothesis. A small p does not mean the effect is large or important. A large p does not mean there is no effect — the study may simply have been too small.
- Small studies tend to overestimate effects. Treat single small studies as hypothesis-generating, not practice-changing.

### Bias and confounding

These are the reasons a study can mislead even when conducted honestly.

- **Selection bias:** the patients recruited are not representative of yours.
- **Confounding:** a third variable influences both the treatment and the outcome — the classic example is sicker patients being more likely to receive an intervention, making the intervention appear harmful.
- **Performance bias:** groups receive different co-interventions or levels of care.
- **Publication bias:** positive or exciting results are more likely to be published. A meta-analysis built on published studies may therefore overestimate benefit.
- **Regression to the mean:** patients tend to be recruited when things are at their worst and improve regardless. This can masquerade as treatment benefit in uncontrolled studies and QI projects alike.

---

## Study designs you will meet

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


### Randomised controlled trial (RCT)

The gold standard for establishing causality. Key features to look for:

- **Randomisation and allocation concealment** — if the person enrolling a patient knows which group they will go into, selection bias creeps back in.
- **Blinding** — of patients, clinicians, and outcome assessors where feasible.
- **Pre-registered protocol and pre-specified primary outcome** — registered before the trial started, ideally on a public database.
- **Intention-to-treat (ITT) analysis** — patients are analysed in the group they were randomised to, regardless of what actually happened. This preserves the benefits of randomisation. Per-protocol analysis can be informative but is more prone to bias.

### Observational studies

Useful when RCTs are impractical, unethical, or when you need long-term or rare-event data.

- **Cohort studies** follow exposed and unexposed groups forward — good for harms.
- **Case–control studies** start from the outcome and look backwards — efficient for rare outcomes.
- **Cross-sectional studies** are snapshots — fine for prevalence, poor for causality.
- Statistical adjustments (propensity scores, regression) reduce but never eliminate confounding. Observe the result; do not simply trust the adjusted number.

### Perioperative-specific designs

- **Cluster randomised and stepped-wedge trials** randomise theatres or wards rather than individuals — common in quality improvement research. Clustering must be accounted for in the analysis.
- **Crossover trials** — each patient is their own control. Require a washout period and are unsuitable where effects persist.
- **Adaptive and platform trials** — modify the study as data accumulate. Require pre-specified rules to avoid false positives.

---

## Outcomes that matter

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


Favour **patient-centred outcomes**: mortality, return to baseline function, pain, delirium, serious complications. Be cautious about **surrogate outcomes** (biomarkers, imaging findings) — they are easier to measure but may not translate into patient benefit.

**Subgroup analyses** should be pre-specified, biologically plausible, and tested for interaction. A subgroup finding that was not planned in advance is hypothesis-generating only — it should not change your practice without corroborating evidence.

---

## Diagnostic and monitoring tests

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


### The core principle: conditional probability

- **Sensitivity** and **specificity** are fixed properties of a test. **Predictive values** shift with the pre-test probability of disease.
- **Likelihood ratios** are more useful in practice — they tell you how much a positive or negative result shifts your probability estimate.
- A highly sensitive test is most useful for ruling out; a highly specific test is most useful for ruling in.
- A negative test is not reassuring if your pre-test probability was already very high.

### Practical points

- **ROC curves and AUC** summarise how well a test discriminates across thresholds. **Calibration** — whether predicted risk matches observed outcomes — also matters for scores used in clinical decisions (e.g. risk stratification tools).
- Be aware that airway scores and clinical assessments carry significant inter-observer variability. No single sign rules in or out a difficult airway.

---

## Hypothesis testing, power, and sample size

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


- **Type I error (false positive):** concluding there is an effect when there is not.
- **Type II error (false negative):** missing a real effect because the study was too small.
- A well-designed study declares its primary outcome, the clinically important effect size it is powered to detect, and how it will handle missing data — all *before* the data are collected.
- **Early-stopped trials** tend to overestimate benefit. Treat them with caution.

---

## Equivalence and non-inferiority trials

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


These trials aim to show a new intervention is not unacceptably worse than an existing one.

- The **non-inferiority margin** must be clinically justified — a wide margin makes a meaningless difference look acceptable.
- Both ITT and per-protocol analyses are important here: if patients deviate from treatment, ITT may artificially make two treatments look similar.
- The control must perform as it did in the historical trials that set the margin — if it does not, the comparison collapses.

---

## Reading an RCT quickly: a five-minute framework

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


1. **PICO** — does the population, intervention, and outcome match your clinical question?
2. **Primary outcome** — is it patient-important and pre-specified?
3. **Effect size with CI** — absolute measures preferred; does it exceed the MCID?
4. **Methods** — randomisation, allocation concealment, blinding, registration, ITT.
5. **Baseline table** — large imbalances between groups despite randomisation are a warning sign.
6. **Harms** — systematically collected and reported?
7. **Applicability** — does this translate to your patients and your setting?
8. **Cross-check** — consistent with NICE, Cochrane, or national guidance? If not, find out why before acting.

---

## Systematic reviews and meta-analyses

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


A good systematic review is pre-registered (e.g. on PROSPERO), uses a comprehensive search, and assesses risk of bias in each included study.

- **Forest plots:** look at the direction and size of individual study effects and whether the overall estimate is driven by one or two outliers.
- **Heterogeneity** means studies are giving different answers. This is a signal to investigate — different populations, interventions, or quality — not something to average away.
- **Publication bias** can be explored with funnel plots. Asymmetry suggests smaller, positive studies are over-represented.
- **Network meta-analysis** allows indirect comparison of multiple interventions simultaneously. Its conclusions rest on assumptions of similarity between trials; treat them with appropriate scepticism.

### GRADE

This framework rates the certainty of evidence as high, moderate, low, or very low. It weighs risk of bias, inconsistency, indirectness, imprecision, and publication bias. Even high-certainty evidence may not apply to your patient if the population differs meaningfully.

---

## Translating evidence to your patient

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


Ask three questions:

1. **Are my patients similar?** Age, comorbidity, surgical complexity, and local context all matter.
2. **What is the baseline risk?** High-risk patients gain more absolute benefit from an effective intervention — but are also more exposed to harms.
3. **Can we deliver this?** Implementation fidelity matters. A result from a high-volume specialist centre may not transfer automatically.

In UK practice, align with RCoA curriculum principles, Association of Anaesthetists guidance, DAS airway guidelines, and Resuscitation Council UK standards. Follow local protocols as the default. If you deviate, have a documented, defensible reason and ensure the team is aware.

---

## Quality improvement and audit

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


### Measurement for improvement

- QI uses **small, rapid PDSA cycles** with frequent data collection. The goal is trend detection, not statistical significance.
- **Run charts** plot data over time against a median. Simple rules identify non-random patterns.
- **Statistical process control (SPC) charts** account for natural variation and are more sensitive to genuine change. Choose the chart type appropriate to your data (counts, proportions, or continuous measurements).

### Common traps

- **Regression to the mean:** improvement may reflect natural variation returning to baseline. Look for sustained change over multiple data points.
- **Seasonal and casemix variation** can mimic or mask true change — annotate your charts with context.
- **Funnel plots** for benchmarking adjust for volume. Outliers require investigation, not automatic blame.

### Governance

Know whether your project is audit, service evaluation, or research — this determines the approvals pathway and data governance requirements. When in doubt, ask your local R&D or clinical governance team.

---

## Common statistical pitfalls

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


- **SD versus SEM:** the standard error of the mean shrinks with sample size and does not describe individual variability. If a paper uses SEM to make data look tighter, it is misleading.
- **Parametric methods on non-normal data** — check whether assumptions are justified.
- **Dichotomising continuous variables** (e.g. "elderly" vs "not elderly") loses information and can obscure real relationships.
- **Interpreting a wide CI as "no difference"** — the study may simply have been underpowered. Absence of evidence is not evidence of absence.
- **Relative risks without absolute context** — always find the absolute numbers.
- **Ignoring clustering** — patients within the same theatre or ward are not independent. Analyses that ignore this overstate precision.
- **Single-centre efficacy trials** — may not generalise.
- **Clinical prediction models and AI tools** — check calibration, discrimination, and external validation before trusting them in your patient population.

---

## Safe habits and reliable sources

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


- Default to **Cochrane, NICE, and national specialty guidelines** before changing practice on the basis of a single paper.
- Check local protocols and formularies for doses and thresholds — never rely on memory alone.
- Discuss major practice changes at governance or QI meetings and monitor outcomes afterwards.
- In emergencies, use guideline-backed defaults. Fragile or preliminary evidence is not the moment to experiment.

---

## Key takeaways

> _This is a project on AI content generation. It is **not a clinical reference** and must not be relied on for clinical decisions._


- **Effect size with uncertainty and risk of bias** determine how much to trust a result.
- Prefer **absolute measures**, **pre-registered primary outcomes**, and **ITT analyses**.
- A statistically significant result is not automatically clinically important — apply the MCID.
- **Applicability** to your patient and pathway matters as much as the statistics.
- In QI, think in **trends and systems**, not single data points.
- When in doubt, slow down, find a trusted source, and choose the safest well-supported option.
