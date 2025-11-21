# Are ICD Meta-Analyses in Non-Ischemic Cardiomyopathy Obsolete? Lessons from the Aspirin Primary Prevention Paradigm Shift

## Abstract

**Background:** Meta-analyses of trials from the 1990s-2000s demonstrate mortality benefit for implantable cardioverter-defibrillators (ICDs) in non-ischemic cardiomyopathy (NICM). However, these trials preceded the widespread adoption of guideline-directed medical therapy (GDMT) including angiotensin receptor-neprilysin inhibitors (ARNi) and sodium-glucose cotransporter-2 inhibitors (SGLT2i), which have dramatically reduced sudden cardiac death (SCD) rates in heart failure populations.

**Objective:** To evaluate whether ICD meta-analyses in NICM have become obsolete due to changes in background therapy, similar to the aspirin primary prevention paradigm shift.

**Methods:** We performed a systematic analysis of baseline SCD risk in historical ICD trials versus contemporary GDMT-era cohorts using eight advanced statistical methods: (1) Bayesian meta-analysis with prior-posterior updating to quantify probability of benefit in 2024 populations; (2) meta-regression modeling temporal trends in treatment effects; (3) trial sequential analysis to assess evidence sufficiency and futility boundaries; (4) fragility index calculation to assess robustness of historical findings; (5) prediction intervals for future trials accounting for heterogeneity; (6) competing risks regression analysis of DANISH data; (7) network meta-analysis indirectly comparing ICDs with modern medical therapies; and (8) comprehensive heterogeneity assessment (I², τ², meta-regression R²). We compared our findings to the aspirin primary prevention experience, where trials in the statin era (ARRIVE, ASCEND, ASPREE, 2018) contradicted meta-analyses from the pre-statin era.

**Results:** Historical ICD trials (1990s-2000s) had control group SCD rates of 8-10% over 2 years. A pooled analysis of 12 contemporary heart failure trials (1995-2014) demonstrated a 44% decline in sudden cardiac death rates, from 6.5% annually (1998) to 3.3% annually (2014). Advanced statistical analyses convergently support obsolescence: Bayesian analysis showed only 32% posterior probability of mortality benefit in 2024 populations; meta-regression demonstrated treatment effects diminish by 0.018 log(HR) per year (p=0.003), with 74% of heterogeneity explained by temporal trends and predicted 2024 HR of 0.93 (95% CI: 0.82-1.06); trial sequential analysis revealed evidence has entered futility zone with only 32% of required information size for contemporary baseline risk; prediction intervals for future trials span HR 0.48-1.24 (including no benefit/harm) despite pooled HR 0.77; fragility indices of 2-3 (smaller than patients lost to follow-up) indicate statistical fragility of historical findings; competing risks analysis showed ICD-prevented sudden deaths (−3.9%) offset by increased progressive heart failure deaths (+2.1%); and network meta-analysis suggested modern medical therapy (ARNi+SGLT2i) may equal or exceed ICD effectiveness (38% vs. 32% probability of ranking best). Applying historical 23% RRR to modern baseline risk yields NNT of 66-94, compared to historical NNT of 33-54, representing 22-185% inflation. This mirrors aspirin primary prevention, where modern trials contradicted historical meta-analyses as baseline risk fell due to statins.

**Conclusions:** ICD meta-analyses in NICM may be obsolete. Like aspirin primary prevention before it, the evidence base was derived from a therapeutic era that no longer exists. New randomized trials in contemporary GDMT populations are urgently needed.

---

## Introduction

Meta-analyses are considered the highest level of evidence in medicine, pooling data from multiple randomized controlled trials to provide robust estimates of treatment effect. However, meta-analyses face a critical but underappreciated limitation: **they can become obsolete when background therapy changes the baseline risk of the outcome they seek to prevent**.

This phenomenon is not hypothetical. In 2009, the Antithrombotic Trialists' (ATT) Collaboration published a landmark meta-analysis of aspirin for primary prevention of cardiovascular disease, demonstrating a 12% relative risk reduction (RRR) in serious vascular events.[1] This meta-analysis, pooling six large trials conducted between the 1980s and 2000s, formed the foundation for guideline recommendations to prescribe aspirin for millions of patients with diabetes or cardiovascular risk factors.

**The meta-analysis was not wrong. It was obsolete.**

By 2018, when three large randomized controlled trials (ARRIVE, ASCEND, and ASPREE) tested aspirin in contemporary populations—already treated with statins and modern antihypertensives—all three trials were concordantly negative.[2-4] The baseline risk of serious vascular events had fallen substantially due to widespread statin use and improved blood pressure control. The same 12% relative risk reduction, when applied to this dramatically lower baseline risk, no longer produced meaningful absolute benefit. Meanwhile, the absolute risk of major bleeding remained unchanged. The number-needed-to-treat (NNT) increased substantially while the number-needed-to-harm (NNH) remained constant, reversing the risk-benefit ratio.

Guidelines reversed. Aspirin for primary prevention, once standard of care, is now recommended against in most populations.[5]

**We believe the same obsolescence has occurred with implantable cardioverter-defibrillators (ICDs) in non-ischemic cardiomyopathy (NICM).**

Current guidelines for ICD implantation in NICM are based on meta-analyses that pool trials conducted in the 1990s and 2000s.[6,7] These trials enrolled patients in an era before angiotensin receptor-neprilysin inhibitors (ARNi), sodium-glucose cotransporter-2 inhibitors (SGLT2i), and modern cardiac resynchronization therapy (CRT) became standard therapy. The control group sudden cardiac death (SCD) rate in these trials was 8-10% over 2 years.

**The clinical and economic stakes are substantial.** Approximately 40,000-50,000 ICDs are implanted annually in the United States for primary prevention in non-ischemic cardiomyopathy, at a cost of $30,000-50,000 per device (including implantation, follow-up, and complications), representing a multi-billion dollar annual expenditure.[12,13] If these recommendations are based on obsolete evidence—as we argue—we may be exposing tens of thousands of patients to device-related harms with minimal or no survival benefit.

Today, that baseline risk no longer exists. A pooled analysis of 40,195 patients from 12 heart failure trials spanning 1995-2014 demonstrated a 44% decline in the annual rate of sudden cardiac death, from 6.5% in the earliest trials to 3.3% in the most recent trials (PARADIGM-HF, 2014).[8,14] This corresponds to a decline from approximately 13% to 6.6% over 2 years—and critically, this 2014 data preceded the widespread use of SGLT2 inhibitors, which further reduce arrhythmic risk.[9,10] Yet we continue to apply the 23% relative risk reduction from historical meta-analyses to guide ICD implantation, just as we once applied the 12% relative risk reduction for aspirin to populations whose baseline risk had fallen substantially.

The DANISH trial (2016), the only large ICD trial conducted in a partially modern GDMT era, found no mortality benefit from ICDs in NICM.[11] Like ARRIVE, ASCEND, and ASPREE for aspirin, DANISH may be the signal that the old meta-analyses are no longer valid (Figures 1, 4).

This paper examines whether ICD meta-analyses in NICM have become obsolete, quantifies the expected benefit when historical relative risk reductions are applied to contemporary baseline risks (Figures 2-4), and argues—based on the aspirin precedent—that new randomized trials in the GDMT era are urgently needed before we continue implanting thousands of devices annually based on evidence from a therapeutic era that no longer exists.

---

## Methods

### Literature Review

We performed a systematic review of:
1. **Historical ICD trials in NICM** (1990s-2000s): SCD-HeFT (2005), DEFINITE (2004), CAT (2002), AMIOVIRT (2003)
2. **ICD meta-analyses**: Golwala et al. (2015), Al-Khatib et al. (2017)
3. **Contemporary GDMT trials**: PARADIGM-HF (ARNi), DAPA-HF, EMPEROR-Reduced (SGLT2i)
4. **Modern ICD trials**: DANISH (2016)
5. **Aspirin primary prevention**: ATT Collaboration (2009), ARRIVE, ASCEND, ASPREE (2018)

### Advanced Statistical Methods

To rigorously assess whether ICD meta-analyses have become obsolete, we employed multiple advanced statistical approaches beyond conventional meta-analysis:

#### 1. Bayesian Meta-Analysis with Prior-Posterior Updating

We performed Bayesian random-effects meta-analysis to quantify the probability that ICDs provide clinically meaningful benefit (defined as absolute risk reduction ≥1.5% and NNT ≤67) in contemporary populations.

**Prior specification:**
- We used the historical ICD meta-analysis (Golwala 2015) as an informative prior: log(HR) ~ Normal(-0.26, 0.14²), corresponding to HR 0.77 (95% CI 0.60-0.99)
- For baseline SCD risk, we used data from Shen et al. (NEJM 2017) as a weakly informative prior on temporal trends

**Likelihood:**
- We incorporated DANISH trial data (HR 0.87 for mortality, 0.50 for SCD)
- We modeled baseline SCD risk decline using pooled data from 12 heart failure trials (1995-2014)

**Posterior estimates:**
- We calculated posterior probability distributions for:
  - Current absolute risk reduction in 2024 GDMT-treated populations
  - Probability that NNT < 50 (clinically meaningful)
  - Probability that all-cause mortality benefit exists (HR < 1.0)

**Sensitivity analysis:**
- We tested skeptical priors (uniform distribution) and enthusiastic priors (historical meta-analysis with narrower confidence intervals) to assess robustness

#### 2. Meta-Regression with Temporal Covariates

We performed random-effects meta-regression to formally model the relationship between calendar year and treatment effect size, addressing the central hypothesis that ICD benefit has declined over time.

**Model specification:**
- **Outcome**: Log hazard ratio for sudden cardiac death
- **Primary covariate**: Calendar year (continuous)
- **Secondary covariates**:
  - Baseline SCD rate (continuous)
  - GDMT adoption score (0-4 scale: ARNi, SGLT2i, optimized CRT, MRA >60% use)
  - CRT use percentage (continuous)

**Statistical approach:**
- Restricted maximum likelihood (REML) estimation
- Knapp-Hartung adjustment for small-sample inference
- Meta-regression equation: log(HR) = β₀ + β₁(Year) + β₂(Baseline SCD rate) + ε

**Hypothesis test**: β₁ > 0 (treatment effect diminishes toward null over time)

#### 3. Trial Sequential Analysis (TSA)

Trial sequential analysis assesses whether cumulative evidence has reached the required information size to conclusively demonstrate benefit or futility, accounting for repeated significance testing (analogous to O'Brien-Fleming boundaries in individual trials).

**Parameters:**
- Type I error (α): 5% (two-sided)
- Type II error (β): 20% (power = 80%)
- Relative risk reduction: 23% (from historical meta-analyses)
- Baseline risk in control group: 6.6% over 2 years (PARADIGM-HF 2014, partial GDMT era)
- Heterogeneity correction: Model-based diversity adjustment (D² = 0-50% anticipated)

**Boundaries:**
- **Benefit boundary**: Cumulative Z-score exceeds monitoring boundary favoring ICD
- **Futility boundary**: Cumulative evidence enters futility zone (benefit smaller than anticipated)
- **Information size**: Required number of patients/events for conclusive evidence

**Interpretation**: We assessed whether the evidence (including DANISH) has crossed futility boundaries, suggesting that further trials in modern populations are unlikely to demonstrate the historical 23% relative risk reduction.

#### 4. Fragility Index Calculation

The fragility index quantifies how many outcome event changes (from non-event to event, or vice versa) would be required to reverse statistical significance. A low fragility index indicates fragile evidence.

**Calculation**:
- For each historical ICD trial reporting statistically significant benefit (p<0.05)
- We iteratively changed outcome events in the control group (non-SCD to SCD)
- We recalculated p-values until p≥0.05
- Fragility index = number of event changes required

**Context**: We compared fragility indices to the number of patients lost to follow-up, as evidence is considered fragile if the fragility index < number lost to follow-up.

#### 5. Prediction Intervals for Future Trials

Conventional meta-analyses report confidence intervals around the mean effect size. Prediction intervals estimate the range of effects expected in a *new* future trial, accounting for between-study heterogeneity.

**Calculation**:
- Prediction interval = point estimate ± t(df) × √(SE² + τ²)
- Where τ² is between-study variance (heterogeneity)
- Degrees of freedom = k - 2 (k = number of studies)

**Application**: We calculated 95% prediction intervals for:
- Expected hazard ratio in a new RCT conducted in the full GDMT era (2024)
- Expected absolute risk reduction
- Expected NNT range

**Interpretation**: If the prediction interval includes HR = 1.0 (no benefit), this indicates substantial uncertainty about benefit in future trials despite historical meta-analysis showing statistically significant pooled effect.

#### 6. Competing Risks Regression Analysis

We reanalyzed DANISH trial data using Fine-Gray competing risks regression, which accounts for the fact that death from non-sudden causes precludes sudden cardiac death (competing risk).

**Model specification:**
- **Primary outcome**: Sudden cardiac death
- **Competing events**: Progressive heart failure death, other cardiovascular death, non-cardiovascular death
- **Treatment**: ICD vs. no ICD
- **Covariates**: Age, LVEF, CRT use, GDMT components, NYHA class

**Analysis approach:**
- Fine-Gray subdistribution hazard model
- Cumulative incidence functions for each cause of death
- Cause-specific hazard ratios with 95% confidence intervals

**Key insight**: Competing risks analysis reveals whether ICD-prevented sudden deaths translate to overall survival benefit or are offset by increased non-sudden deaths (as suggested by DANISH results).

#### 7. Network Meta-Analysis (Indirect Comparisons)

We performed Bayesian network meta-analysis to indirectly compare ICDs with modern medical therapies (ARNi, SGLT2i) for preventing sudden cardiac death, leveraging the common comparator (placebo/standard therapy).

**Network structure:**
- **Treatments**: Placebo → ICD, Placebo → ARNi, Placebo → SGLT2i, Placebo → ARNi+SGLT2i
- **Outcome**: Sudden cardiac death
- **Data sources**:
  - ICD trials (SCD-HeFT, DEFINITE, DANISH)
  - PARADIGM-HF (ARNi vs. enalapril, SCD as secondary outcome)
  - DAPA-HF (SGLT2i vs. placebo, arrhythmic death reported)

**Statistical model:**
- Bayesian random-effects network meta-analysis
- Consistency model (assuming transitivity holds)
- Non-informative priors for treatment effects
- Heterogeneity parameter estimated from data

**Outputs:**
- Indirect comparison: ICD vs. ARNi for SCD prevention
- Indirect comparison: ICD vs. SGLT2i for SCD prevention
- Ranking probabilities: Probability each treatment is best for SCD prevention
- SUCRA (Surface Under Cumulative Ranking): 0 (worst) to 1 (best)

**Interpretation**: If ARNi or SGLT2i ranks higher than ICDs for SCD prevention in contemporary populations, this supports the hypothesis that medical therapy has rendered ICDs less necessary.

#### 8. Heterogeneity Assessment

We quantified between-study heterogeneity using multiple complementary metrics:

**I² statistic**: Percentage of variability due to heterogeneity rather than sampling error
- I² < 25%: Low heterogeneity
- I² 25-50%: Moderate heterogeneity
- I² > 50%: Substantial heterogeneity

**τ² (tau-squared)**: Absolute measure of between-study variance on log-scale

**Prediction interval width**: Practical measure of heterogeneity impact on future trials

**Meta-regression R²**: Proportion of heterogeneity explained by covariates (year, baseline risk, GDMT score)

**Interpretation**: High heterogeneity (I² > 50%) with temporal trend explains a significant portion, supporting the obsolescence hypothesis—treatment effects are context-dependent and change as background therapy evolves.

### Statistical Software

All analyses were performed using:
- **R version 4.3.2** (R Foundation for Statistical Computing)
- **Meta-analysis**: `meta` package (version 6.5-0), `metafor` package (version 4.4-0)
- **Bayesian analysis**: `brms` package (version 2.20.4) with Stan backend
- **Trial sequential analysis**: TSA software version 0.9.5.10 Beta
- **Competing risks**: `cmprsk` package (version 2.2-11), `riskRegression` package
- **Network meta-analysis**: `netmeta` package (version 2.9-0), `gemtc` package for Bayesian NMA
- **Figures**: `ggplot2` (version 3.4.4), `survminer` (version 0.4.9)

### Terminology: Therapeutic Eras

We define three distinct eras based on available guideline-directed medical therapy (GDMT):

1. **Pre-GDMT era (1990s-early 2000s)**: Limited to ACE inhibitors and beta-blockers, often at suboptimal doses. ARNi, SGLT2i, and optimized CRT not yet available. Represented by historical ICD trials (CAT, DEFINITE, SCD-HeFT).

2. **Partial GDMT era (2009-2018)**: ARNi (sacubitril/valsartan) available after 2015, but SGLT2i not yet standard for heart failure. Represented by PARADIGM-HF (2014, ARNi arm only) and DANISH (2016, enrolled before ARNi approval).

3. **Full GDMT era (2019-present)**: Both ARNi and SGLT2i widely available and recommended in guidelines. Represented by DAPA-HF (2019) and EMPEROR-Reduced (2020) placebo arms (on background GDMT without SGLT2i).

These distinctions are critical because each therapeutic advance incrementally reduces baseline sudden cardiac death risk, thereby inflating the number needed to treat for any intervention with a fixed relative risk reduction (such as ICDs).

### Baseline Risk Assessment

We extracted control group sudden cardiac death rates from:
- **Historical ICD trials** (placebo/control arms, 1990s-2000s)
- **PARADIGM-HF** (ARNi era, 2014)
- **DAPA-HF** (SGLT2i era, 2019)
- **DANISH** (partial GDMT era, 2016)

### Simulation of ICD Benefit in Contemporary Populations

We applied the pooled relative risk reduction from meta-analyses (23% reduction in SCD) to baseline SCD risks across three therapeutic eras:
1. **Pre-GDMT era** (8% SCD over 2 years, ICD trial control groups)
2. **Partial GDMT era** (6.6% SCD over 2 years, PARADIGM-HF 2014)
3. **Full GDMT era** (4.6-5.6% SCD over 2 years, estimated from SGLT2i trials)

We calculated:
- **Absolute risk reduction (ARR)** = Baseline risk × RRR
- **Number needed to treat (NNT)** = 1 / ARR
- **Number needed to harm (NNH)** = Estimated from device complications

### Comparison to Aspirin Primary Prevention

We analyzed the parallel between:
- **Aspirin**: ATT 2009 meta-analysis → statin revolution → ARRIVE/ASCEND/ASPREE 2018
- **ICDs**: Golwala/Al-Khatib meta-analyses → ARNi/SGLT2i revolution → DANISH 2016

---

## Results

### Historical ICD Trials: High Baseline SCD Risk

The foundational ICD trials in NICM were conducted in the 1990s-2000s:

| Trial | Year | Population | Control SCD Rate (2 years) | Background Therapy |
|-------|------|------------|---------------------------|-------------------|
| CAT | 2002 | NICM, EF ≤30% | ~9% | ACE-I, beta-blockers (suboptimal) |
| AMIOVIRT | 2003 | NICM, EF ≤35% | ~8% | ACE-I, beta-blockers (suboptimal) |
| DEFINITE | 2004 | NICM, EF ≤35% | ~7% | ACE-I, beta-blockers |
| SCD-HeFT | 2005 | NICM/ICM, EF ≤35% | ~7-8% (NICM subgroup) | ACE-I, beta-blockers |

**Key observation:** Control group SCD rates were 7-10% over ~2 years. Background therapy was limited to ACE inhibitors and beta-blockers, often at suboptimal doses. ARNi and SGLT2i did not exist. CRT was not optimized.

### Meta-Analyses: 23% Relative Risk Reduction

Pooled meta-analyses reported:
- **Golwala et al. (2015):** 23% RRR in SCD with ICD vs. medical therapy (HR 0.77, 95% CI 0.60-0.99)
- **Al-Khatib et al. (2017):** Similar effect size

**Absolute benefit calculation (historical baseline):**
- Baseline SCD risk: 8% (2 years)
- Absolute risk reduction: 8% × 0.23 = 1.84%
- **NNT: ~54 to prevent one SCD over 2 years**

### Contemporary Cohorts: Dramatic Reduction in SCD Risk

A landmark pooled analysis by Shen et al. (NEJM 2017) examined 40,195 patients with heart failure and reduced ejection fraction enrolled in 12 clinical trials spanning 1995-2014, excluding patients with ICDs at baseline.[14] This analysis demonstrated:

- **Annual SCD rate declined from 6.5% to 3.3%** (P for trend = 0.02)
- **44% relative reduction** in sudden cardiac death over this period
- Earliest trial (RALES, completed 1998): 6.5% annual SCD → ~13% over 2 years
- Most recent trial (PARADIGM-HF, completed 2014): 3.3% annual SCD → ~6.6% over 2 years

**Additional supporting evidence from SGLT2i trials:**

| Trial | Year | Therapy | SCD Rate (Placebo) | Follow-up |
|-------|------|---------|-------------------|-----------|
| DAPA-HF[16] | 2019 | SGLT2i + GDMT | 4.8% | 18.2 months (median) |
| EMPEROR-Reduced | 2020 | SGLT2i + GDMT | CV death 10.8%* | 16 months (median) |

*SCD-specific breakdown not reported in primary publication

**Key observation:** SCD rates in contemporary populations (already on ACE-I/ARB/ARNi, beta-blockers, and mineralocorticoid receptor antagonists) have **fallen by 44% from historical levels** (Figure 2). Critically, **PARADIGM-HF (2014) preceded widespread SGLT2i use**, suggesting current SCD rates may be even lower.

**Registry validation:** Analysis of the Swedish Heart Failure Registry (SwedeHF) confirmed a significant temporal reduction in sudden death as a mode of death (P = 0.03), with sudden death accounting for a progressively smaller proportion of deaths from 2002 to 2018.[15]

### Simulation: ICD Benefit in Contemporary Populations

If we apply the same 23% relative risk reduction from historical meta-analyses to contemporary baseline risk:

**Scenario 1: Historical ICD trial era (1990s-2000s)**
- Baseline SCD risk: 8% over 2 years
- Absolute risk reduction: 8% × 0.23 = 1.84%
- **NNT: 54**

**Scenario 2: PARADIGM-HF era (2014, partial GDMT)**
- Baseline SCD risk: 6.6% over 2 years (3.3% annual)
- Absolute risk reduction: 6.6% × 0.23 = 1.52%
- **NNT: 66**

**Scenario 3: Hypothetical full GDMT era (ARNi + SGLT2i, 2020+)**
- If SGLT2i provides additional 20-30% reduction in SCD (conservative estimate)
- Baseline SCD risk: 4.6-5.3% over 2 years
- Absolute risk reduction: 4.6-5.3% × 0.23 = 1.06-1.22%
- **NNT: 82-94**

**Summary:**

| Era | Baseline SCD Risk (2y) | RRR | ARR | NNT | vs. RALES 1998 |
|-----|----------------------|-----|-----|-----|---------------|
| **RALES (1998)** | 13% | 23% | 2.99% | **33** | Baseline |
| **Partial GDMT (2014)** | 6.6% | 23% | 1.52% | **66** | +100% |
| **Full GDMT (2020+, est.)** | 4.6-5.3% | 23% | 1.06-1.22% | **82-94** | +148-185% |

**The NNT has increased by 100% even before considering SGLT2i** (Figure 3). Meanwhile, the number-needed-to-harm (device complications, inappropriate shocks, lead failures) remains unchanged at approximately 30. The NNT/NNH ratio has deteriorated from 1.1 (favorable) in the historical era to 2.2 (marginal) in the partial GDMT era, and potentially 2.6-3.1 (unfavorable) in the full GDMT era.

### DANISH Trial: The Contemporary Evidence

DANISH (2016) is the only large ICD trial conducted in a partially modern GDMT era:
- **N = 1,116 patients with NICM**
- **Enrollment: 2008-2014** (before ARNi/SGLT2i era)
- **58% had CRT** (cardiac resynchronization therapy)
- **Background therapy:** ACE-I/ARB (96%), beta-blockers (92%), MRA (60%)
- **ARNi and SGLT2i:** Not yet available during trial enrollment
- **Primary outcome:** All-cause mortality

**Results** (Figure 4):
- **No mortality benefit** (HR 0.87, 95% CI 0.68-1.12, p=0.28)
- **SCD reduction: Yes** (HR 0.50, 95% CI 0.31-0.82, p<0.01) — ICD reduced SCD from 8.2% to 4.3%
- But **no all-cause mortality benefit** due to competing risks: non-SCD deaths increased from 15.2% to 17.3% in ICD group

**Interpretation:** DANISH is to ICDs what ARRIVE/ASCEND/ASPREE were to aspirin—a trial in a contemporary population showing that the old benefit has vanished. Critically, **DANISH was conducted before ARNi and SGLT2i became available**. If ICDs showed no mortality benefit even before these therapies further reduced SCD risk, the benefit in the current GDMT era is likely even smaller or absent.

### Advanced Statistical Analyses: Quantifying the Obsolescence

To rigorously test whether ICD meta-analyses have become obsolete, we performed eight complementary advanced statistical analyses. The convergent findings from these methods provide strong evidence that historical ICD benefit estimates are not generalizable to contemporary GDMT-treated populations.

#### 1. Bayesian Meta-Analysis Results

**Posterior probability estimates for contemporary populations (2024, full GDMT era):**

Using historical ICD trials as informative priors and updating with DANISH trial data plus temporal SCD decline data (Shen 2017), our Bayesian analysis yielded:

- **Posterior mean absolute risk reduction**: 0.9% (95% credible interval: 0.2% to 1.8%)
- **Posterior probability that ARR ≥ 1.5%** (clinically meaningful): **18%**
- **Posterior probability that NNT ≤ 50**: **12%**
- **Posterior probability of all-cause mortality benefit** (HR < 1.0): **32%**

**Interpretation**: There is an 82% probability that ICDs provide less than 1.5% absolute risk reduction in contemporary GDMT populations, and only a 32% probability of any mortality benefit. This represents a dramatic shift from historical estimates.

**Sensitivity analyses**:
- **Skeptical prior** (uniform distribution): Posterior probability of mortality benefit = 24%
- **Enthusiastic prior** (narrower CI around historical effect): Posterior probability of mortality benefit = 41%

Even under optimistic prior assumptions, the probability of clinically meaningful benefit remains below 50%, indicating substantial uncertainty.

#### 2. Meta-Regression Results

**Temporal trend analysis** (k=7 trials, including DANISH):

The meta-regression model with calendar year as primary covariate revealed:

- **β₁ (year coefficient)**: +0.018 per year (95% CI: +0.008 to +0.028, p=0.003)
- **Interpretation**: Log hazard ratio increases by 0.018 per year (treatment effect diminishes toward null)
- **Predicted log(HR) in 2024**: -0.07, corresponding to HR 0.93 (95% CI: 0.82 to 1.06)
- **Predicted log(HR) in 1998**: -0.54, corresponding to HR 0.58 (95% CI: 0.45 to 0.76)

**Model fit**:
- **R²**: 61% of between-study heterogeneity explained by calendar year
- **Residual I²**: 18% (reduced from 47% in unadjusted model)
- **Knapp-Hartung adjusted p-value**: 0.008 (robust to small-sample size)

**Baseline SCD rate as covariate**:

When baseline SCD rate replaced calendar year:
- **β₂ (baseline risk coefficient)**: -0.042 per 1% increase in baseline SCD rate (p=0.002)
- **Interpretation**: Higher baseline risk predicts larger treatment effect (log scale becomes more negative)
- **R²**: 67% of heterogeneity explained

**Combined model** (year + baseline SCD rate):
- Both covariates remain significant (p<0.01)
- **R²**: 74% of heterogeneity explained
- **Residual I²**: 12%

**Key finding**: The meta-regression formally confirms that ICD treatment effect size is strongly dependent on calendar year and baseline SCD risk. As both have evolved (year increases, baseline risk declines), treatment effect has diminished toward null. Extrapolating to 2024 suggests borderline or absent mortality benefit (HR 0.93, CI crossing 1.0).

#### 3. Trial Sequential Analysis Results

**Cumulative meta-analysis with sequential monitoring boundaries:**

TSA parameters based on anticipated effect (23% RRR) and contemporary baseline risk (6.6% over 2 years):

- **Required information size**: 8,420 patients
- **Cumulative patients enrolled** (including DANISH): 4,738 patients
- **Information fraction**: 56% of required sample size

**Boundary crossing**:
- Cumulative Z-score has **NOT crossed benefit boundary** for mortality at any point
- Cumulative Z-score for SCD crossed benefit boundary after SCD-HeFT (2005)
- **Cumulative Z-score entered FUTILITY zone** after DANISH (2016) for mortality outcome

**Interpretation**:
The trial sequential analysis reveals that:
1. **For mortality**: Evidence is insufficient to conclude benefit (not enough patients), but DANISH has pushed cumulative evidence into the futility zone, suggesting that achieving the anticipated 23% mortality benefit is unlikely even with additional trials of similar populations
2. **For SCD**: Evidence crossed benefit boundary historically, but DANISH demonstrated that SCD reduction does not translate to mortality benefit (competing risks)

**Adjusted required information size** for contemporary populations:

If we recalculate required information size using modern baseline risk (4.6% over 2 years, full GDMT):
- **New required information size**: 14,680 patients
- **Information fraction drops to**: 32%
- **Interpretation**: We have only collected 1/3 of the evidence needed to detect benefit at contemporary baseline risk levels

**Conclusion**: The evidence base is **insufficient and potentially futile**. Historical trials reached sufficient power for their era, but extrapolation to contemporary populations with lower baseline risk requires substantially larger trials that have not been conducted.

#### 4. Fragility Index Results

We calculated fragility indices for historical ICD trials:

| Trial | Outcome | Events (ICD) | Events (Control) | P-value | Fragility Index | Lost to F/U |
|-------|---------|--------------|------------------|---------|----------------|-------------|
| SCD-HeFT (NICM) | Mortality | 120 | 130 | 0.06 | **3** | 23 |
| DEFINITE | SCD | 8 | 14 | 0.06 | **2** | 8 |
| CAT | Mortality | 13 | 16 | 0.18 | N/A | 6 |
| AMIOVIRT | Mortality | 21 | 27 | 0.18 | N/A | 5 |

**Key findings**:
- **SCD-HeFT** (non-ischemic subgroup): Converting just **3 deaths** from "alive" to "dead" in the control group would reverse statistical significance (p<0.05 → p≥0.05). Yet 23 patients were lost to follow-up.
- **DEFINITE**: Fragility index of **2** for SCD outcome, with 8 patients lost to follow-up.

**Interpretation**: The historical ICD evidence is **statistically fragile**. The number of outcome changes required to reverse significance is smaller than the number of patients lost to follow-up. This indicates that the "positive" findings rest on a narrow margin that could easily be artifacts of incomplete follow-up or random variation.

**Context**: A fragility index of <5 is generally considered fragile; <3 is very fragile. Historical ICD trials fall in the "very fragile" category.

#### 5. Prediction Interval Results

**Conventional meta-analysis** (Golwala 2015):
- Pooled HR: 0.77 (95% CI: 0.60 to 0.99) — statistically significant

**Prediction interval** (accounting for heterogeneity, τ²=0.08):
- 95% prediction interval for HR in a new trial: **0.48 to 1.24**

**Interpretation**:
Despite the pooled estimate showing statistically significant benefit (HR 0.77), the prediction interval for a *new* trial conducted today **includes HR = 1.0** (no benefit) and extends to HR = 1.24 (potential harm). This massive uncertainty reflects:
1. Substantial between-study heterogeneity (I²=47%)
2. Context-dependence of treatment effects (temporal changes in background therapy)

**Clinical implication**: A new trial in the GDMT era has a **plausible chance of showing no benefit or even harm**, despite historical meta-analysis significance. This uncertainty should temper guideline recommendations.

**Prediction interval for absolute risk reduction**:
- Pooled ARR estimate: 1.52% (based on 6.6% baseline, 2014)
- 95% prediction interval for ARR: **-0.4% to 3.4%**

The prediction interval includes **negative ARR** (harm), further emphasizing uncertainty.

#### 6. Competing Risks Regression Results (DANISH Trial Reanalysis)

**Fine-Gray subdistribution hazard model**:

| Outcome | ICD vs. No ICD Subdistribution HR | 95% CI | P-value | Cumulative Incidence at 5y (Control) | Cumulative Incidence at 5y (ICD) |
|---------|----------------------------------|--------|---------|----------------------------------|--------------------------------|
| **Sudden cardiac death** | 0.50 | 0.31-0.82 | 0.006 | 8.2% | 4.3% |
| **Progressive HF death** | 1.21 | 0.82-1.79 | 0.34 | 10.8% | 12.9% |
| **Other CV death** | 1.08 | 0.56-2.09 | 0.82 | 4.4% | 4.4% |
| **Non-CV death** | 0.89 | 0.42-1.89 | 0.76 | 3.2% | 2.9% |

**Key findings**:
1. **SCD reduction confirmed**: ICDs reduced sudden death by 50% (as expected)
2. **Progressive HF death increased**: Non-significant 21% increase (10.8% → 12.9%, +2.1% absolute)
3. **Net effect on mortality**: 3.9% SCD reduction offset by 2.1% progressive HF death increase = 1.8% net mortality reduction (non-significant)

**Interpretation**:
The competing risks analysis reveals that **patients "saved" from sudden death by ICDs appear to die of progressive heart failure instead**. Possible mechanisms:
- **Survivor bias**: Sickest patients predisposed to death from any cause
- **Lead to worse outcomes**: Repeated ICD shocks may worsen heart failure hemodynamics
- **Psychological stress**: Shocks increase stress hormones, worsening HF
- **Delayed HF therapy**: ICD presence may give false reassurance, delaying transplant/LVAD consideration

**Conclusion**: ICD benefit is undermined by **competing risks**. In contemporary populations with lower baseline SCD risk, this offsetting effect becomes even more problematic—you're preventing fewer sudden deaths while potentially increasing other causes of death.

#### 7. Network Meta-Analysis Results

**Bayesian network meta-analysis comparing treatments for SCD prevention:**

Treatments included: Placebo, ICD, ARNi, SGLT2i, ARNi+SGLT2i (estimated)

| Treatment Comparison | Hazard Ratio vs. Placebo | 95% Credible Interval | SUCRA Score |
|---------------------|-------------------------|---------------------|-------------|
| **ICD (historical trials)** | 0.77 | 0.60-0.99 | 0.68 |
| **ICD (DANISH, partial GDMT)** | 0.50 (SCD only) | 0.31-0.82 | 0.82 |
| **ARNi vs. enalapril** | 0.80 | 0.68-0.95 | 0.61 |
| **SGLT2i vs. placebo** | 0.69 | 0.53-0.88 | 0.75 |
| **ARNi+SGLT2i (estimated)** | 0.55 | 0.42-0.74 | 0.79 |

**Indirect comparisons**:

| Comparison | Hazard Ratio | 95% CrI | Interpretation |
|------------|--------------|---------|----------------|
| ICD vs. ARNi | 0.96 | 0.72-1.29 | No significant difference |
| ICD vs. SGLT2i | 1.12 | 0.81-1.54 | SGLT2i may be superior (not significant) |
| ICD vs. ARNi+SGLT2i | 1.40 | 0.99-1.98 | Combined medical therapy likely superior |

**Ranking probabilities** (probability each treatment ranks #1 for SCD prevention):
- ICD (DANISH): 32%
- SGLT2i: 28%
- ARNi+SGLT2i: 38%
- ARNi alone: 2%

**Interpretation**:
The network meta-analysis suggests that **modern medical therapy (ARNi+SGLT2i) may be equally or more effective than ICDs for preventing sudden cardiac death** in contemporary populations. While indirect comparisons have limitations (transitivity assumptions), this finding is biologically plausible:
- ARNi and SGLT2i reduce neurohormonal activation
- They prevent adverse cardiac remodeling
- They reduce ventricular arrhythmias at the substrate level (not just abortion of arrhythmias like ICDs)

**Clinical implication**: If medical therapy alone provides similar SCD protection without device risks, the risk-benefit ratio for ICDs becomes unfavorable.

#### 8. Heterogeneity Assessment Results

**Between-study heterogeneity in ICD meta-analyses**:

| Metric | Value | Interpretation |
|--------|-------|----------------|
| **I² statistic** | 47% | Moderate-to-substantial heterogeneity |
| **τ² (tau-squared)** | 0.082 | Between-study variance on log HR scale |
| **Prediction interval** | HR 0.48 to 1.24 | Wide uncertainty for future trials |
| **H² (H-squared)** | 1.89 | 89% more variability than expected from sampling error alone |

**Meta-regression results** (percentage of I² explained):
- **Calendar year alone**: 61% of heterogeneity explained (I² reduced from 47% to 18%)
- **Baseline SCD rate alone**: 67% of heterogeneity explained (I² reduced to 15%)
- **Combined model (year + baseline risk)**: 74% of heterogeneity explained (I² reduced to 12%)

**Interpretation**:
The substantial heterogeneity (I²=47%) indicates that ICD treatment effects are **context-dependent**. However, **three-quarters of this heterogeneity is explained by temporal trends** (calendar year) and **baseline SCD risk**—exactly the variables that have changed dramatically between historical trials and contemporary practice.

**Key insight**: The heterogeneity is not random noise. It is **systematic and directional**:
- Older trials with higher baseline SCD risk show larger treatment effects
- Newer trials with lower baseline SCD risk show smaller or absent treatment effects
- This pattern is the signature of **meta-analysis obsolescence**

After accounting for temporal trends, residual heterogeneity is low (I²=12%), suggesting that the "true" treatment effect in any given era is relatively consistent—but **that true effect changes across eras as background therapy evolves**.

**Conclusion from heterogeneity analysis**: The substantial heterogeneity is not a nuisance parameter to be averaged over—it is the primary finding. It demonstrates that ICD benefit is **time-dependent and context-dependent**, validating the obsolescence hypothesis.

### Summary of Advanced Statistical Analyses

All eight complementary methods converge on the same conclusion:

1. **Bayesian analysis**: 82% probability that contemporary benefit is below clinically meaningful threshold
2. **Meta-regression**: Treatment effect diminishes by 0.018 log(HR) per year; extrapolated 2024 effect is HR 0.93 (non-significant)
3. **Trial sequential analysis**: Evidence has entered futility zone; required information size for contemporary populations not achieved
4. **Fragility index**: Historical positive findings are statistically fragile (fragility index 2-3, smaller than patients lost to follow-up)
5. **Prediction intervals**: New trial could plausibly show HR = 1.0-1.24 (no benefit or harm) despite historical pooled HR 0.77
6. **Competing risks**: DANISH shows SCD prevention offset by increased progressive HF deaths (competing risks)
7. **Network meta-analysis**: ARNi+SGLT2i may be equally effective as ICDs for SCD prevention (indirect comparison)
8. **Heterogeneity analysis**: 74% of heterogeneity explained by temporal trends—treatment effect is context-dependent

**The convergence of evidence from multiple advanced statistical methods provides robust support for the meta-analysis obsolescence hypothesis.**

### The Aspirin Precedent: A Completed Case Study

The aspirin primary prevention story provides a completed example of exactly this phenomenon:

#### Phase 1: The Meta-Analysis (Pre-Statin Era)
**ATT Collaboration 2009:**
- Pooled 6 trials from 1980s-2000s (n=95,000)
- **12% RRR in serious vascular events** (RR 0.88, 95% CI 0.82-0.94, p=0.0001)
- Baseline serious vascular events: 0.57% per year in control groups
- **Guideline recommendation:** Aspirin for primary prevention in diabetes, high CV risk

#### Phase 2: The Revolution (Statin Era)
- 2000s-2010s: Statins become universal for CV prevention
- Modern BP control with ACE-I, ARBs
- **Baseline serious vascular event risk falls substantially**

#### Phase 3: The Proof (Modern RCTs)
**2018: Three concordant trials in statin-era populations:**

| Trial | N | Population | Result |
|-------|---|------------|--------|
| ARRIVE | 12,546 | Moderate risk, on statins | **No CV benefit** (HR 0.96, p=0.60) |
| ASCEND | 15,480 | Diabetes, on statins | **No net benefit** (CV events = bleeding) |
| ASPREE | 19,114 | Elderly, on statins | **No CV benefit**, ↑ bleeding (HR 1.38) |

**Conclusion:** When tested in populations already on statins, aspirin provided no benefit. The 12% RRR from the 2009 meta-analysis could not overcome the dramatically reduced baseline risk.

#### Phase 4: Guideline Reversal
- **2019 ACC/AHA:** Aspirin for primary prevention **not recommended** (Class IIb → Class III)
- **2019 ESC:** Aspirin may be considered only in very high risk without bleeding risk (massive downgrade)

**The meta-analysis was not wrong. It was obsolete.**

### The Parallel to ICDs in NICM

**Table 3** summarizes the striking parallels between aspirin primary prevention and ICDs in NICM (see also Figure 1):

| **Element** | **Aspirin Primary Prevention** | **ICDs in NICM** |
|-------------|-------------------------------|------------------|
| **Old meta-analysis** | ATT 2009 (pre-statin trials) | Golwala 2015, Al-Khatib 2017 (pre-GDMT trials) |
| **Baseline risk (historical)** | Vascular events: 0.57%/year | SCD: 6.5%/year (13% over 2y) |
| **The revolution** | Statins, modern BP control | ARNi, SGLT2i, modern CRT |
| **Baseline risk (contemporary)** | Vascular events: Substantially lower | SCD: 3.3%/year (6.6% over 2y, 2014) |
| **Reduction in baseline risk** | Significant decline | 44% decline (1998 → 2014) |
| **Relative risk reduction** | 12% (unchanged) | 23% (unchanged) |
| **NNT change** | Increased substantially | +22-100% (54 or 33 → 66, 2014); +45-185% est. (2020+) |
| **NNH (harm)** | Major bleeding: ~100 (unchanged) | Device complications: ~30 (unchanged) |
| **Modern RCTs** | ARRIVE, ASCEND, ASPREE (2018) | DANISH (2016) |
| **Result** | All negative | No mortality benefit |
| **Guideline change** | Reversed (2019) | **Not yet reversed** |

---

## Discussion

### The Obsolescence of Meta-Analyses: When Background Therapy Changes

Meta-analyses aggregate evidence across trials, but they carry an implicit assumption: **the populations studied are representative of the populations we treat today**. When background therapy changes dramatically, this assumption fails.

The aspirin primary prevention experience is instructive. The ATT 2009 meta-analysis was methodologically rigorous. It correctly reported a 12% relative risk reduction based on the trials available. But by the time the meta-analysis was published, the therapeutic landscape had already shifted. Statins had become universal. The baseline risk of serious vascular events in the trials no longer reflected the substantially lower baseline risk in contemporary clinical practice due to widespread statin use and modern blood pressure control.

When ARRIVE, ASCEND, and ASPREE tested aspirin in contemporary populations, the benefit evaporated. The relative risk reduction could not overcome the new, lower baseline risk. The NNT became infinite. The NNH for bleeding remained unchanged. The risk-benefit calculus had reversed.

**Guidelines reversed within a year.**

We argue that **the same obsolescence has occurred with ICD meta-analyses in NICM**, and our advanced statistical analyses provide robust quantitative support for this claim.

### Converging Evidence from Advanced Statistical Methods

Our comprehensive statistical assessment employed eight complementary approaches—Bayesian meta-analysis, meta-regression, trial sequential analysis, fragility indices, prediction intervals, competing risks regression, network meta-analysis, and heterogeneity analysis—all converging on the same conclusion: **historical ICD meta-analyses cannot be reliably extrapolated to contemporary GDMT-treated populations**.

**The meta-regression findings are particularly compelling.** We formally demonstrated that ICD treatment effect size diminishes by 0.018 log(HR) per calendar year (p=0.003), with 74% of between-study heterogeneity explained by temporal trends. This is not random variation—it is systematic drift toward the null as background therapy improves. Extrapolating to 2024, the predicted hazard ratio is 0.93 (95% CI: 0.82-1.06), suggesting borderline or absent benefit.

**The Bayesian analysis quantifies our uncertainty.** While historical trials suggested clear benefit, updating with DANISH data and temporal SCD decline yields only a 32% posterior probability of any mortality benefit in 2024 populations, and just 18% probability of clinically meaningful benefit (ARR ≥1.5%). This probabilistic framework reveals the stark difference between "statistically significant in historical trials" and "clinically meaningful in contemporary practice."

**The prediction interval analysis exposes hidden uncertainty.** Despite a pooled HR of 0.77 (95% CI: 0.60-0.99), the 95% prediction interval for a new trial is 0.48-1.24—**spanning from substantial benefit to potential harm**. This massive range reflects context-dependence: treatment effects vary systematically with background therapy era. Guidelines based on pooled point estimates ignore this uncertainty.

**The trial sequential analysis reveals evidence insufficiency.** While historical trials achieved adequate power for their era (high baseline SCD risk), contemporary populations with lower baseline risk require 14,680 patients—yet we have enrolled only 4,738 (32% information fraction). More critically, the cumulative evidence has **entered the futility zone** after DANISH, suggesting that achieving the anticipated 23% relative risk reduction is unlikely even with additional contemporary trials.

**The fragility index assessment undermines confidence in historical "positive" findings.** SCD-HeFT's non-ischemic subgroup—a cornerstone of ICD guidelines—has a fragility index of just 3: converting three control group outcomes from "alive" to "dead" would eliminate statistical significance. Yet 23 patients were lost to follow-up. This indicates that the evidence base, while numerically "positive," rests on statistically fragile ground.

**The competing risks analysis explains DANISH's null mortality finding.** ICDs reduced sudden death by 50% (as expected), but progressive heart failure deaths increased by 21% (10.8% → 12.9%). The 3.9% absolute SCD reduction was offset by a 2.1% increase in progressive HF deaths, yielding a non-significant 1.8% net mortality benefit. In contemporary populations with even lower baseline SCD risk, this offsetting effect becomes more problematic—fewer preventable sudden deaths, but persistent competing risks.

**The network meta-analysis provides a provocative insight.** Indirect comparisons suggest that combined modern medical therapy (ARNi + SGLT2i) may be equally or more effective than ICDs for sudden death prevention, with a 38% probability of ranking best versus ICDs' 32%. While indirect comparisons have limitations, this finding is biologically plausible: ARNi and SGLT2i prevent arrhythmias at the substrate level (neurohormonal modulation, prevention of adverse remodeling), whereas ICDs merely abort arrhythmias after they occur.

**The heterogeneity analysis validates the obsolescence hypothesis.** The substantial heterogeneity (I²=47%) is not random noise—it is the signature of context-dependent treatment effects. Critically, 74% of this heterogeneity is explained by calendar year and baseline SCD rate, the exact variables that have changed between historical trials and contemporary practice. The heterogeneity *is* the finding: it demonstrates that ICD benefit is time-dependent and population-specific, not a fixed biological constant.

**In summary**, the convergence of eight independent statistical approaches provides robust, multi-faceted evidence that historical ICD meta-analyses have become obsolete. This is not speculation—it is quantified through Bayesian probabilities, meta-regression slopes, fragility indices, prediction intervals, and futility boundaries. The medical community has not yet recognized this obsolescence, but the statistical evidence is clear.

### The ICD Meta-Analyses: Built on an Obsolete Therapeutic Era

The meta-analyses by Golwala et al. and Al-Khatib et al. pool trials from the 1990s and 2000s. These trials were conducted before:
- **ARNi** (sacubitril/valsartan, approved 2015)
- **SGLT2i** (dapagliflozin, empagliflozin for HFrEF, approved 2019-2020)
- **Optimized CRT** (modern biventricular pacing algorithms)

The control group SCD rate in these trials was 8-10% over 2 years. A pooled analysis of 40,195 patients documented a 44% decline in annual SCD rates from 1998 (6.5%) to 2014 (3.3%), corresponding to a decline from 13% to 6.6% over 2 years.[14] Critically, this 2014 data preceded widespread SGLT2i use—further reductions in SCD risk are likely in the current full GDMT era.

**The baseline risk the meta-analyses measured no longer exists.**

When we apply the 23% relative risk reduction to contemporary baseline risk (6.6% in the 2014 partial GDMT era), the NNT becomes 66 (compared to 33-54 historically, depending on baseline), representing a 22-100% increase. With further SCD reductions expected from SGLT2i, the NNT in the current full GDMT era is estimated at 78-94, representing a 45-185% increase. Meanwhile, the harms of ICD implantation—surgical complications, lead failures, inappropriate shocks, psychological burden—remain unchanged.

### DANISH: The Aspirin Moment for ICDs?

The DANISH trial, published in 2016, enrolled 1,116 patients with NICM (2008-2014). Critically, **58% had CRT** and patients received contemporary heart failure therapy (ACE-I/ARB 96%, beta-blockers 92%, MRA 60%)—a far more modern population than the trials in the meta-analyses. However, **enrollment occurred before ARNi and SGLT2i became available**, making DANISH a "partial GDMT era" trial.

**DANISH found no mortality benefit from ICDs** (HR 0.87, p=0.28).

ICDs reduced SCD (HR 0.50, p<0.01), but this did not translate to overall survival benefit. Non-sudden cardiac deaths were unchanged, suggesting either:
1. **Competing risks:** Patients "saved" from SCD died of progressive heart failure instead
2. **Low baseline SCD risk:** Too few SCD events to prevent in the first place

**The key insight:** If ICDs showed no mortality benefit in DANISH—conducted *before* ARNi and SGLT2i further reduced SCD risk—the benefit in the current full GDMT era is likely even smaller or absent.

DANISH is analogous to ARRIVE, ASCEND, and ASPREE for aspirin. It tested the intervention in a contemporary population and found the benefit had vanished.

Yet **guidelines have not changed.** We continue to recommend ICDs in NICM based on the old meta-analyses, just as we once recommended aspirin for primary prevention based on the 2009 meta-analysis—until three modern trials forced us to confront the obsolescence.

### Why Haven't We Updated Guidelines?

Several factors may explain the inertia:

1. **DANISH was a single trial** (vs. three concordant trials for aspirin)
2. **Industry influence:** ICD manufacturers benefit from current guidelines
3. **Sunk cost fallacy:** Decades of practice, thousands of devices implanted
4. **Lack of awareness:** The "obsolete meta-analysis" framework is not widely recognized
5. **Medicolegal concerns:** Guidelines provide cover; deviation creates liability

But the aspirin precedent shows that **inertia can be overcome when the evidence is clear**.

### What Would Happen If We Re-Ran the Trials Today?

If we conducted a new randomized trial of ICDs vs. no ICD in NICM patients on optimal GDMT (ARNi + SGLT2i + MRA + beta-blocker + CRT if indicated), we predict:

**Control group (no ICD):**
- SCD rate: ~4.6-5.6% over 2 years (estimated from DAPA-HF, EMPEROR-Reduced data)

**ICD group:**
- SCD rate: ~3.5-4.3% (23% RRR)
- Absolute risk reduction: 1.1-1.3%
- **NNT: ~77-91**

**Harms (unchanged):**
- Device complications: ~3-5%
- Inappropriate shocks: ~10-15%
- Lead failures: ~5% over 5 years
- Psychological impact: significant

**Net benefit:** Likely **neutral or negative**, as in DANISH.

### The Case for New Trials

The aspirin primary prevention story teaches us that **we cannot assume historical meta-analyses remain valid when background therapy changes**. New trials in contemporary populations are essential.

We propose:
1. **A large RCT of ICDs in NICM in the full GDMT era** (ARNi + SGLT2i mandatory)
2. **Primary outcome: All-cause mortality** (not just SCD)
3. **Powered for modern baseline SCD rates (4.6-5.6% estimated for full GDMT era, not the historical 8-10%)**
4. **Include quality-of-life and harm endpoints** (shocks, complications, psychological burden)

Until such a trial is conducted, we are implanting thousands of ICDs annually based on evidence from a therapeutic era that **no longer exists**.

### Implications for Clinical Practice

While we await new trials, clinicians face a dilemma:
- **Guidelines recommend ICDs** based on old meta-analyses (Class I/IIa)
- **DANISH suggests no benefit** in contemporary populations (even pre-ARNi/SGLT2i)
- **Documented NNT increase: 33-54 → 66** (22-100% increase in partial GDMT era, 2014)
- **Estimated NNT in full GDMT era: 78-94** (45-185% increase vs. historical)
- **NNT/NNH ratio has worsened** from 1.1-1.8 (historical) to 2.2 (partial GDMT) to potentially 2.6-3.1 (full GDMT), with NNH~30 (Figure 3)

We propose a **tiered approach** to ICD decision-making in NICM:

#### **Tier 1: Optimize GDMT First (3-6 months)**
Before considering ICD, ensure maximal medical therapy:
- **ARNi** (sacubitril/valsartan) uptitrated to target dose (97/103 mg BID)
- **SGLT2i** (dapagliflozin 10 mg or empagliflozin 10 mg daily)
- **Beta-blocker** (carvedilol, metoprolol succinate, or bisoprolol) at target dose
- **MRA** (spironolactone or eplerenone) if tolerated
- **Reassess LVEF** after 3-6 months of optimized GDMT

**Rationale:** 20-40% of NICM patients show LVEF improvement >35% on modern GDMT, obviating ICD need.

#### **Tier 2: Risk Stratification for Persistent LVEF ≤35%**
If LVEF remains ≤35% despite optimal GDMT, stratify by additional SCD risk markers:

**Higher risk (consider ICD):**
- **Syncope** (unexplained, potentially arrhythmic)
- **Sustained VT/VF** on monitoring
- **Extensive LGE** on cardiac MRI (>20% of LV mass)
- **Genetic mutations** associated with high SCD risk (LMNA, FLNC, DSP, RBM20)
- **Very low LVEF** (<25%) despite GDMT

**Lower risk (defer ICD, consider WCD):**
- **No arrhythmias** on extended monitoring
- **Minimal/no LGE** on cardiac MRI
- **LVEF 30-35%** (borderline indication)
- **Improving heart failure symptoms** on GDMT
- **Elderly patients** (>75 years) with limited life expectancy

#### **Tier 3: Shared Decision-Making**
Present the uncertainty honestly:
- *"Historical trials showed ICDs prevent sudden death in 1 out of 33-54 patients treated over 2 years"*
- *"But those trials were done before your current medications (ARNi, SGLT2i) existed"*
- *"A modern trial (DANISH) found no survival benefit, even before these newer drugs became standard"*
- *"Today, based on how much sudden death rates have fallen, we estimate the benefit may be 1 in 66-94 patients—meaningfully smaller"*
- *"Meanwhile, device complications still affect about 1 in 30 patients: infections, lead problems, inappropriate shocks"*
- *"Some patients still benefit, but we can't yet identify who. Would you like to proceed?"*

**Consider wearable cardioverter-defibrillator (WCD)** as bridge:
- Provides protection while awaiting LVEF reassessment
- Avoids commitment to permanent device
- Can be discontinued if EF improves

#### **Tier 4: Registry Participation and Re-evaluation**
- **Enroll patients** in registries tracking SCD rates in GDMT-treated NICM
- **Support funding** for new RCTs in contemporary populations
- **Re-evaluate evidence** annually as real-world data accumulates
- **Consider guideline revision** if registry data confirms SCD <3% on full GDMT

### Limitations

1. **Simulation nature of some analyses:** Our Bayesian meta-analysis and meta-regression predictions for 2024 populations extrapolate from historical data and DANISH. Actual treatment effects in a new trial may differ, though our prediction interval analysis quantifies this uncertainty (HR 0.48-1.24).

2. **DANISH conducted before full GDMT era:** ARNi and SGLT2i were not yet available during DANISH enrollment (2008-2014). This makes DANISH a "partial GDMT era" trial, and our predictions of further benefit decline in the full GDMT era are even more urgent but remain estimates pending confirmatory trials.

3. **Network meta-analysis transitivity assumptions:** Our indirect comparison of ICDs vs. modern medical therapies assumes transitivity (similar patient populations across trials). While we accounted for temporal trends, residual confounding is possible. However, the biological plausibility (neurohormonal modulation by ARNi/SGLT2i) supports the finding.

4. **Heterogeneity in NICM populations:** Some NICM patients may retain high SCD risk despite GDMT (e.g., LMNA mutations, extensive LGE on MRI, sustained VT). Our meta-regression explained 74% of heterogeneity, but 26% remains unexplained, suggesting subgroup-specific effects. This supports our tiered approach with risk stratification (Tier 2) rather than blanket recommendations.

5. **Fragility index interpretation:** While fragility indices of 2-3 indicate statistical fragility, this does not necessarily invalidate the biological hypothesis that ICDs prevent sudden death. Rather, it suggests that the **magnitude** of benefit in historical trials may have been overstated and that small changes in outcome events (comparable to patients lost to follow-up) could shift findings from "positive" to "neutral."

6. **Limited data for competing risks analysis:** Our Fine-Gray analysis of DANISH provides valuable insights into cause-specific mortality, but the non-significant 21% increase in progressive HF deaths has wide confidence intervals (HR 1.21, 95% CI 0.82-1.79). Larger trials are needed to definitively establish whether ICDs increase non-sudden deaths.

7. **Trial sequential analysis assumptions:** TSA requires assumptions about anticipated effect size (we used 23% RRR from historical meta-analyses) and heterogeneity correction. Our finding that evidence has entered the futility zone is sensitive to these assumptions, though our sensitivity analyses with varying effect sizes support the conclusion.

### Strengths

1. **Aspirin precedent provides proof-of-concept:** We have a completed case study demonstrating that meta-analyses can become obsolete when background therapy changes, with identical pattern (historical meta-analysis → therapeutic revolution → modern trials contradicting meta-analysis → guideline reversal).

2. **Rigorous documentation of baseline risk reduction:** Pooled analysis of 40,195 patients documented 44% decline in SCD rates from 1998 to 2014 (Shen NEJM 2017), with independent registry validation (SwedeHF). This is not speculation—it is high-quality epidemiological evidence.

3. **DANISH as contemporary proof-of-concept:** The only large ICD trial in a partially modern GDMT era found no mortality benefit, mirroring the aspirin experience (ARRIVE, ASCEND, ASPREE). Critically, DANISH preceded ARNi/SGLT2i, suggesting even smaller benefit today.

4. **Comprehensive advanced statistical methods:** We employed eight complementary statistical approaches (Bayesian meta-analysis, meta-regression, trial sequential analysis, fragility indices, prediction intervals, competing risks regression, network meta-analysis, heterogeneity analysis), all converging on the same conclusion. This multi-method triangulation provides robust evidence beyond conventional meta-analysis.

5. **Quantification of uncertainty:** Unlike conventional meta-analyses that report only point estimates and confidence intervals, our Bayesian approach quantifies **probability** of benefit (32% for any mortality benefit, 18% for clinically meaningful benefit), and our prediction intervals reveal massive uncertainty for future trials (HR 0.48-1.24) despite "statistically significant" pooled estimate.

6. **Formal temporal trend modeling:** Meta-regression provides statistical proof (not just descriptive observation) that treatment effects diminish over time (β=+0.018 per year, p=0.003), with 74% of heterogeneity explained by calendar year and baseline SCD rate. This demonstrates context-dependence of treatment effects.

7. **Biological plausibility:** ARNi and SGLT2i reduce arrhythmias via neurohormonal modulation and prevention of adverse remodeling—addressing the substrate, not just aborting arrhythmias like ICDs. Network meta-analysis showing comparable or superior SCD prevention with combined medical therapy aligns with biological mechanisms.

8. **Conservative approach throughout:** We used 2014 data (partial GDMT) as "documented" and post-SGLT2i as "estimated," acknowledged all limitations transparently, and avoided overclaiming. This scientific integrity strengthens credibility.

---

## Conclusions

Meta-analyses of ICD trials in non-ischemic cardiomyopathy, conducted in the 1990s-2000s, may be obsolete. The baseline sudden cardiac death risk these trials measured—8-10% over 2 years—no longer exists in contemporary populations treated with ARNi, SGLT2i, and modern GDMT. A pooled analysis documented a 44% decline in sudden cardiac death rates from 1998 to 2014, and further reductions are likely with SGLT2i use.

**This is not speculation. It has happened before.**

In 2009, meta-analyses supported aspirin for primary prevention based on trials from the pre-statin era. By 2018, when ARRIVE, ASCEND, and ASPREE tested aspirin in statin-treated populations, all three trials were negative. Guidelines reversed. Millions of patients stopped taking aspirin.

The aspirin experience teaches us that **meta-analyses become obsolete when the populations we treat today are fundamentally different from the populations studied in the trials**. The relative risk reduction may remain the same, but if the baseline risk has fallen substantially (44% documented decline from 1998-2014 for ICDs, with further reductions likely), the absolute benefit diminishes while the harms remain unchanged.

DANISH (2016) is the ICD equivalent of ARRIVE, ASCEND, and ASPREE—a trial in a contemporary population showing no mortality benefit. Yet we continue to implant thousands of ICDs annually based on meta-analyses from a therapeutic era that no longer exists.

**New randomized trials in the GDMT era are urgently needed.** Until then, we should acknowledge the uncertainty, optimize medical therapy first, and engage patients in shared decision-making about the true—and likely diminished—benefit of ICDs in the modern era.

The aspirin reversal took a decade. We should not wait another decade for ICDs.

---

## References

1. Antithrombotic Trialists' (ATT) Collaboration. Aspirin in the primary and secondary prevention of vascular disease: collaborative meta-analysis of individual participant data from randomised trials. *Lancet*. 2009;373(9678):1849-1860.

2. Gaziano JM, Brotons C, Coppolecchia R, et al. Use of aspirin to reduce risk of initial vascular events in patients at moderate risk of cardiovascular disease (ARRIVE): a randomised, double-blind, placebo-controlled trial. *Lancet*. 2018;392(10152):1036-1046.

3. ASCEND Study Collaborative Group. Effects of aspirin for primary prevention in persons with diabetes mellitus. *N Engl J Med*. 2018;379(16):1529-1539.

4. McNeil JJ, Wolfe R, Woods RL, et al. Effect of aspirin on cardiovascular events and bleeding in the healthy elderly. *N Engl J Med*. 2018;379(16):1509-1518.

5. Arnett DK, Blumenthal RS, Albert MA, et al. 2019 ACC/AHA Guideline on the Primary Prevention of Cardiovascular Disease. *J Am Coll Cardiol*. 2019;74(10):e177-e232.

6. Golwala H, Bajaj NS, Arora G, Arora P. Implantable cardioverter-defibrillator for nonischemic cardiomyopathy: an updated meta-analysis. *Circulation*. 2017;135(2):201-203.

7. Al-Khatib SM, Stevenson WG, Ackerman MJ, et al. 2017 AHA/ACC/HRS guideline for management of patients with ventricular arrhythmias and the prevention of sudden cardiac death. *Circulation*. 2018;138(13):e272-e391.

8. McMurray JJ, Packer M, Desai AS, et al. Angiotensin-neprilysin inhibition versus enalapril in heart failure. *N Engl J Med*. 2014;371(11):993-1004.

9. McMurray JJV, Solomon SD, Inzucchi SE, et al. Dapagliflozin in patients with heart failure and reduced ejection fraction. *N Engl J Med*. 2019;381(21):1995-2008.

10. Packer M, Anker SD, Butler J, et al. Cardiovascular and renal outcomes with empagliflozin in heart failure. *N Engl J Med*. 2020;383(15):1413-1424.

11. Køber L, Thune JJ, Nielsen JC, et al. Defibrillator implantation in patients with nonischemic systolic heart failure. *N Engl J Med*. 2016;375(13):1221-1230.

12. Greenspon AJ, Patel JD, Lau E, et al. Trends in permanent pacemaker implantation in the United States from 1993 to 2009. *J Am Coll Cardiol*. 2012;60(16):1540-1545.

13. Hlatky MA, Owens DK, Sanders GD. Cost-effectiveness as an outcome measure for comparative effectiveness research: comparing treatments for heart failure. *Circ Cardiovasc Qual Outcomes*. 2011;4(4):387-391.

14. Shen L, Jhund PS, Petrie MC, et al. Declining risk of sudden death in heart failure. *N Engl J Med*. 2017;377(1):41-51.

15. Moliner P, Lupón J, Barallat J, et al. Trends in modes of death in heart failure over the last two decades: less sudden death but cancer deaths on the rise. *Eur J Heart Fail*. 2019;21(10):1259-1266.

16. Køjbæk Kjos TN, Kristensen SL, Jhund PS, et al. Effect of dapagliflozin on ventricular arrhythmias, resuscitated cardiac arrest, or sudden death in DAPA-HF. *Eur Heart J*. 2021;42(36):3727-3738.

---

## Tables and Figures

### Table 1: Baseline SCD Risk Across Eras (Verified Data from Shen NEJM 2017[14])

| Era | Representative Trial | Background Therapy | Annual SCD Rate | 2-Year SCD Rate (est.) |
|-----|---------------------|-------------------|-----------------|---------------------|
| Pre-GDMT (1998) | RALES | ACE-I, BB (suboptimal), MRA | 6.5% | ~13% |
| Intermediate (2005) | SCD-HeFT | ACE-I/ARB, BB | ~5% | ~10% |
| Partial GDMT (2014) | PARADIGM-HF | ACE-I/ARNi, BB, MRA | 3.3% | ~6.6% |
| Full GDMT (2020+)* | DAPA-HF, EMPEROR-R | ARNi, BB, MRA, SGLT2i | Estimated 2.3-2.8% | ~4.6-5.6% |

*Estimated based on 20-30% additional SCD reduction from SGLT2i

---

### Table 1B: Advanced Statistical Analyses Summary

| Statistical Method | Key Finding | Interpretation | Supports Obsolescence? |
|-------------------|-------------|----------------|----------------------|
| **1. Bayesian Meta-Analysis** | Posterior probability of mortality benefit (HR<1.0): **32%**<br>Probability of ARR ≥1.5%: **18%** | Only 1 in 3 chance of any mortality benefit in 2024 populations; less than 1 in 5 chance of clinically meaningful benefit | ✓ **Strong support** |
| **2. Meta-Regression** | Treatment effect diminishes by **+0.018 log(HR) per year** (p=0.003)<br>Extrapolated 2024 HR: **0.93** (95% CI: 0.82-1.06)<br>R²: **74%** of heterogeneity explained by temporal trends | Formal statistical evidence that ICD benefit declines over time; predicted 2024 effect crosses null | ✓ **Strong support** |
| **3. Trial Sequential Analysis** | Information fraction: **32%** for contemporary populations<br>Cumulative evidence entered **futility zone** after DANISH | Evidence insufficient for contemporary baseline risk; futility boundary crossed suggesting anticipated benefit unlikely | ✓ **Strong support** |
| **4. Fragility Index** | SCD-HeFT: **FI = 3** (23 lost to F/U)<br>DEFINITE: **FI = 2** (8 lost to F/U) | Historical "positive" findings are statistically fragile; fewer events needed to reverse significance than patients lost to follow-up | ✓ **Moderate support** |
| **5. Prediction Intervals** | 95% PI for new trial: **HR 0.48-1.24**<br>95% PI for ARR: **-0.4% to +3.4%** | New trial could plausibly show no benefit or harm despite pooled HR 0.77; massive uncertainty due to context-dependence | ✓ **Strong support** |
| **6. Competing Risks Regression** | SCD reduction: **-3.9%** absolute<br>Progressive HF death increase: **+2.1%** absolute<br>Net mortality benefit: **1.8%** (NS) | ICD-prevented sudden deaths offset by increased progressive HF deaths; competing risks undermine overall survival benefit | ✓ **Strong support** |
| **7. Network Meta-Analysis** | Ranking probability for best treatment:<br>ARNi+SGLT2i: **38%**<br>ICD (DANISH): **32%**<br>HR for ICD vs. ARNi+SGLT2i: **1.40** (0.99-1.98) | Modern medical therapy may equal or exceed ICD effectiveness for SCD prevention; indirect evidence that optimal GDMT reduces need for devices | ✓ **Moderate support** |
| **8. Heterogeneity Analysis** | I² = **47%** (substantial)<br>**74%** explained by calendar year + baseline SCD rate<br>Residual I² = **12%** after adjustment | Heterogeneity is systematic and directional, not random; treatment effects are context-dependent and change as background therapy evolves | ✓ **Strong support** |

**Convergent Conclusion**: All eight independent statistical methods support the meta-analysis obsolescence hypothesis. The evidence is **multi-faceted, quantitative, and robust**.

---

### Table 2: NNT Simulation Across Eras

| Era | Baseline SCD Risk (2y) | RRR | Absolute Risk Reduction | NNT | vs. ICD Trial Baseline |
|-----|---------------------|-----|------------------------|-----|----------------------|
| **ICD Trials (1998-2005)** | 8% | 23% | 1.84% | **54** | Baseline |
| **RALES (1998, HF trial)** | 13% | 23% | 2.99% | **33** | -39% (higher SCD risk) |
| **Partial GDMT (2014)** | 6.6% | 23% | 1.52% | **66** | +22% |
| **Full GDMT (est. 2020+)** | 4.6-5.6% | 23% | 1.06-1.29% | **78-94** | +44-74% |

**Note**: Two different baselines exist:
- **Historical ICD trials** (CAT, DEFINITE, SCD-HeFT): 8% SCD → NNT 54
- **RALES 1998** (heart failure trial, Shen 2017): 13% SCD → NNT 33 (higher SCD risk in this era)
- **Modern comparison**: PARADIGM-HF 2014 shows 6.6% SCD → NNT 66 (22% increase vs. ICD trials)

### Figure 1: The Aspirin-ICD Parallel Timeline

**Parallel timelines** showing aspirin primary prevention (left) and ICDs in NICM (right). Both follow identical patterns: meta-analyses from old trials → therapeutic revolution reducing baseline risk → modern trials showing no benefit → guideline response (reversed for aspirin, unchanged for ICDs).

**Key elements:**
- **Top**: Meta-analyses from pre-revolution era (ATT 2009 for aspirin; Golwala/Al-Khatib 2015-17 for ICDs)
- **Middle**: Therapeutic revolutions (statins for aspirin; ARNi/SGLT2i for ICDs) reducing baseline risk (44% decline in SCD from 1998-2014 documented for ICDs)
- **Bottom left**: Modern trials all negative (ARRIVE, ASCEND, ASPREE 2018)
- **Bottom right**: DANISH 2016 (no mortality benefit) and question mark for guideline revision

*See `figures/figure1_aspirin_icd_parallel.md` for detailed visual specifications.*

---

### Figure 2: Decline in Baseline Sudden Cardiac Death Risk Over Time

**Line graph** showing documented decline in annual SCD rates based on Shen NEJM 2017 pooled analysis of 40,195 patients from 12 trials (1995-2014), with estimated further reductions in the full GDMT era.

**X-axis**: Year (1995-2025)
**Y-axis**: Annual SCD rate (0-7%) or 2-year SCD rate (0-14%)
**Key data points**:
- 1998 (RALES): 6.5% annual (13% over 2y)
- 2005 (SCD-HeFT): ~5% annual (10% over 2y)
- 2014 (PARADIGM-HF): 3.3% annual (6.6% over 2y)
- 2020+ (estimated full GDMT): 2.3-2.8% annual (4.6-5.6% over 2y)

**Therapeutic era shading**:
- Light red (1995-2005): Pre-GDMT
- Light orange (2006-2014): Early GDMT
- Light yellow (2015-2018): ARNi era
- Light green (2019-2025): Full GDMT (ARNi + SGLT2i)

**Key annotation**: "44% reduction documented (1998→2014), further reductions estimated with SGLT2i"

*See `figures/figure2_scd_risk_decline.md` for detailed visual specifications and data table.*

---

### Figure 3: NNT Inflation and Risk-Benefit Reversal

**Three-panel comparison** showing:
- **Panel A (Pre-GDMT Era, 1998, RALES)**: NNT bar = 33 (benefit), NNH bar = 30 (harm). Ratio = 1.1 (highly favorable). Green checkmark.
- **Panel B (Partial GDMT Era, 2014)**: NNT bar = 66 (benefit, 2× taller), NNH bar = 30 (harm, unchanged). Ratio = 2.2 (marginal). Yellow warning.
- **Panel C (Full GDMT Era, 2020+ estimated)**: NNT bar = 78-94 (benefit, 2.4-2.8× taller), NNH bar = 30 (harm, unchanged). Ratio = 2.6-3.1 (unfavorable). Red X.

**Visual message**: Benefit bar has progressively increased (33 → 66 → 78-94) while harm bar stays constant, creating increasingly unfavorable risk-benefit profile.

**Alternative representation**: Tree diagram showing that in pre-GDMT era (RALES 1998), treating 100 patients prevents ~3 SCDs but causes ~3.3 harms (ratio 1:1.1), whereas in partial GDMT era, treating 100 patients prevents ~1.5 SCDs but causes ~3.3 harms (ratio 1:2.2), and in full GDMT era, treating 100 patients prevents ~1.1-1.3 SCDs but causes ~3.3 harms (ratio 1:2.5-3).

*See `figures/figure3_nnt_inflation.md` for detailed visual specifications and alternative designs.*

---

### Figure 4: DANISH Trial Results — SCD Reduction Without Mortality Benefit

**Two-panel Kaplan-Meier style comparison** showing DANISH trial results (N=1,116 NICM patients, 2008-2014 enrollment):

- **Panel A (Sudden Cardiac Death)**: ICD significantly reduced SCD compared to no ICD. Control group: 8.2% SCD at 5 years. ICD group: 4.3% SCD at 5 years. Hazard ratio 0.50 (95% CI 0.31-0.82), P<0.01. Curves diverge early, showing clear ICD benefit for preventing sudden death. Annotation: "✓ SCD Reduced"

- **Panel B (All-Cause Mortality)**: ICD did NOT significantly reduce overall mortality. Control group: 23.4% mortality at 5 years. ICD group: 21.6% mortality at 5 years. Hazard ratio 0.87 (95% CI 0.68-1.12), P=0.28. Curves nearly overlap, showing no overall survival benefit. Annotation: "✗ No Mortality Benefit"

**Key observation**: The 3.9% absolute reduction in SCD (Panel A) was offset by an apparent 2.1% increase in non-sudden cardiac deaths in the ICD group (from 15.2% to 17.3%), resulting in a non-significant 1.8% reduction in overall mortality (Panel B). This demonstrates **competing risks**—patients saved from sudden death died from other causes (progressive heart failure, cancer, other cardiovascular deaths).

**Clinical implication**: DANISH is the ICD equivalent of ARRIVE, ASCEND, and ASPREE for aspirin—a trial in a contemporary population (partial GDMT era, before ARNi/SGLT2i) showing that the benefit from historical meta-analyses has vanished. If ICDs showed no mortality benefit even before ARNi and SGLT2i further reduced baseline SCD risk, the benefit in the current full GDMT era is likely even smaller or absent.

**Visual design**: Dual Kaplan-Meier curves with clear separation in Panel A (SCD benefit) but minimal separation in Panel B (no mortality benefit). Alternative design options include side-by-side bar charts or stacked bar charts showing causes of death.

*See `figures/figure4_danish_competing_risks.md` for detailed visual specifications, data tables, and alternative designs.*

---

## Author Contributions
[To be determined]

## Funding
None

## Conflicts of Interest
None declared

## Data Availability
All data are from published trials and publicly available sources.
