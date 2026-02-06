# Chapter 5: Complete Clinical Data Analysis

---

> **Chapter Summary**: In-depth analysis of LT3001-202 Phase 2 data, understanding why the surface numbers (mRS 0-2 Δ = +7.5%) are masked by structural factors, and the true efficacy signal revealed by subgroup analysis.

---

## 1. Phase 2 Trial Overview

### 1.1 LT3001-202 Trial Design

| Item | Details |
|------|---------|
| Trial phase | Phase 2 (dose exploration + efficacy signal) |
| Region | China |
| Total enrollment | 301 (297 evaluable) |
| Enrollment criteria | NIHSS 4-25, onset 4.5-24 hours |
| Control group | Placebo |
| Primary endpoint | mRS 0-1 @ 90 days |
| Secondary endpoints | mRS 0-2 @ 90 days, safety |

### 1.2 Dose Groups

| Group | Dose | N |
|-------|------|---|
| Placebo | — | 51 |
| Low dose | 0.025 mg/kg | 49 |
| **High dose** | **0.05 mg/kg** | **99** |
| Highest dose | 0.1 mg/kg | 98 |

**Result**: High dose group (0.05 mg/kg) showed best efficacy, selected for Phase 3.

---

## 2. Surface Numbers: Why They Look "Unimpressive"

### 2.1 Primary Efficacy Results

| Endpoint | LT3001 High Dose | Placebo | Δ |
|----------|------------------|---------|---|
| mRS 0-1 | 67.7% | 66.7% | **+1.0%** |
| mRS 0-2 | 85.9% | 78.4% | **+7.5%** |

Looking only at these numbers, it's easy to conclude "efficacy not significant."

Especially the mRS 0-1 improvement of only 1.0%—appearing virtually indistinguishable from placebo.

**But this conclusion is wrong.**

---

## 3. First Masking Factor: Mild Patient Dilution Effect

### 3.1 Issue: Enrollment Criteria Included Mild Cases

LT3001-202's enrollment criteria was NIHSS 4-25.

This means NIHSS 4-6 "mild" patients were also included.

**Reality**: Approximately **25%** of patients were mild cases (NIHSS 4-6).

### 3.2 Characteristics of Mild Patients

| Characteristic | Description |
|---------------|-------------|
| Minimal neurological deficit | May only have mild limb weakness or sensory abnormality |
| High proportion of lacunar strokes | Small vessel disease, not clot occlusion |
| **Extremely high natural recovery rate** | 80-90% achieve mRS 0-2 regardless of treatment |

### 3.3 Why This Dilutes Efficacy

Lacunar stroke is caused by small vessel pathology, **not clots**.

If there's no clot, thrombolytic drugs have no target.

These patients have similar recovery rates whether receiving drug or placebo.

**Statistical Effect**:

```
Assume 100 patients:
├── 75 are moderate-severe (have clots), drug effective
│   ├── Drug group recovery rate: 80%
│   └── Placebo recovery rate: 60%
│   → Δ = 20%
│
└── 25 are mild (no clots), drug ineffective
    ├── Drug group recovery rate: 90%
    └── Placebo recovery rate: 90%
    → Δ = 0%

Combined calculation:
├── Drug group: 75×80% + 25×90% = 82.5%
├── Placebo: 75×60% + 25×90% = 67.5%
└── Δ = 15% (diluted)
```

**Mild patients act as "noise," simultaneously raising recovery rates in both groups and compressing the efficacy gap.**

---

## 4. Second Masking Factor: Ceiling Effect

### 4.1 Issue: Placebo Group Recovery Rate Too High

LT3001-202 placebo group's mRS 0-2 achievement rate was **78.4%**.

This means even without any treatment, nearly 80% of patients would naturally recover to functional independence.

### 4.2 Why Ceiling Effect Compresses Efficacy

This is like exam scores:

| Scenario | Starting Score | Improve to | Improvement | Difficulty |
|----------|---------------|------------|-------------|------------|
| **Low baseline** | 20 | 50 | +30 | Relatively easy |
| **High baseline** | 70 | 100 | +30 | Very difficult |

Going from 20 to 50 (+30 points) seems like a lot. But going from 70 to 100 (+30 points) is a completely different level of difficulty.

**The higher the baseline, the more limited the room for further improvement.**

This is why there's a business classic called *"Good to Great"*—progressing from "excellent" to "outstanding" is far more difficult than from "mediocre" to "excellent."

LT3001-202 faced exactly this situation:

| Scenario | Placebo | Drug Group | Δ (Absolute) |
|----------|---------|------------|--------------|
| Typical trial | 40% | 60% | **+20%** |
| **LT3001-202** | **78%** | **86%** | **+8%** |

With placebo already at 78% recovery, even if the drug is highly effective, the absolute gap that can be opened is compressed.

### 4.3 Looking at Relative Risk

If we use Relative Risk Reduction (RRR):

```
Proportion not achieving mRS 0-2:
- Placebo: 100% - 78.4% = 21.6%
- LT3001: 100% - 85.9% = 14.1%

Relative Risk Reduction = (21.6% - 14.1%) / 21.6% = 34.7%
```

**The drug reduced the risk of "not recovering" by approximately 35%.**

**What does this 35% mean?**

Imagine a frequently accident-prone intersection.

The traffic bureau made just some "minor adjustments"—adjusting traffic light timing, repainting road markings—and traffic accidents at that intersection decreased by **35%**.

That would be considered a major breakthrough.

What LT3001 does is essentially similar: not inventing new thrombolytic enzymes, just "redistributing" elements the body already has, reducing the risk of "not recovering" by 35%.

**This number is quite impressive for a neurological drug.**

### 4.4 The Forgotten "Untreatable" Population

There's an even deeper issue to understand: **The patients enrolled in LT3001-202 are inherently the "most difficult to treat" group.**

Why? Because of medical ethics.

In stroke treatment, if a patient meets the eligibility criteria for tPA or mechanical thrombectomy (EVT), physicians must prioritize these proven effective treatments. Only in the following situations would patients enter LT3001-202:

| Enrollment Criterion | Patient Type | Actual Situation |
|---------------------|--------------|------------------|
| Beyond tPA window | Onset 4.5-24 hours | Missed golden treatment period |
| Not suitable for EVT | No large vessel occlusion or other limitations | Cannot undergo surgery |
| Very mild | Low NIHSS | Doesn't need aggressive treatment |

**In other words, these patients are either "untreatable" or "don't need treatment."**

This is a population "abandoned" by the current treatment system—missed the tPA window and don't qualify for thrombectomy. Before LT3001, they could only receive supportive care, waiting for natural recovery or deterioration.

**Demonstrating 35% relative risk reduction and +13% to +21% absolute improvement in subgroups among this "most difficult to show effect" patient population—that's what's truly impressive.**

---

## 5. Subgroup Analysis: Revealing True Efficacy

When we correct for the above dilution factors and focus on patients who "truly need thrombolytic treatment," the efficacy signal becomes clear.

### 5.1 Stratification by Severity

| Population | mRS 0-2 Δ | Notes |
|------------|-----------|-------|
| Overall | +7.5% | Includes 25% mild cases, diluted |
| **Moderate-Severe (NIHSS 7-10)** | **+9.3%** | Gap widens after excluding mild cases |

### 5.2 Stratification by Functional Deficit Type

| Population | mRS 0-2 Δ | Notes |
|------------|-----------|-------|
| **Disabling (Motor Deficit)** | **+13% to +21%** | Clear motor function impairment |
| Aphasia patients | +15% | Language function impaired |
| Non-disabling | Lower | Mild symptoms, high natural recovery |

### 5.3 Stratification by Stroke Etiology

| Population | mRS 0-2 Δ | Notes |
|------------|-----------|-------|
| **Large Artery Atherosclerosis (LAA)** | **+10.4%** | Clear clot to dissolve |
| Lacunar | Lower | Non-thrombotic pathology |

### 5.4 Key Finding

> **In patient populations with definite clots and definite functional deficits, LT3001 demonstrates +10% to +21% efficacy improvement.**

This effect size is sufficient to support a well-designed Phase 3 trial.

---

## 6. Safety Data: Independent Value

### 6.1 Symptomatic Intracranial Hemorrhage (sICH)

| Metric | LT3001 (N=297) | tPA (Historical Control) |
|--------|----------------|-------------------------|
| sICH rate | **0% (0/297)** | 2-6% |

**Approximately 300 patients, with zero symptomatic intracranial hemorrhage.**

This is extremely rare data in the thrombolytic drug field.

### 6.2 Why This Data Is Important

0% bleeding is not statistical fluctuation—it's mechanistic evidence.

As described in Chapter 4, LT3001's local action mechanism should theoretically result in lower bleeding risk.

**Clinical data is highly consistent with the mechanistic hypothesis, strengthening the drug's credibility.**

### 6.3 Other Safety Metrics

| Metric | LT3001 | Placebo |
|--------|--------|---------|
| Mortality rate | Comparable to placebo | — |
| Serious adverse events | Comparable to placebo | — |

Overall safety is favorable, with no safety signals identified.

---

## 7. What Does FDA's Response Indicate?

In November 2025, Lumosa received official feedback from the FDA Type C meeting.

### 7.1 FDA's Four Confirmations

| Confirmed Item | Content |
|----------------|---------|
| ✅**Data sufficient** | Phase 2 data supports Phase 3 development |
| ✅**Subgroup design** | Agree to focus on "moderate-severe + disabling patients" |
| ✅**Efficacy endpoint** | mRS 0-2 or mRS 0-1 both acceptable |
| ✅**U.S. patient proportion** | No specific requirement mandated (15% passed) |

### 7.2 Understanding FDA's Logic

FDA would not give such a positive response to a drug showing "no efficacy signal."

If FDA believed LT3001's Phase 2 data was insufficient for further development, typical responses would be:

- Require additional Phase 2 bridging trial
- Require larger dose exploration study
- Express major reservations about Phase 3 design

But in fact, FDA's response was **confirmatory**.

**This indicates FDA saw beyond the surface numbers—they conducted independent verification of subgroup analysis and saw the same efficacy signal we did.**

---

## 8. Why Is mRS 0-1 Improvement So Small?

Many will ask: Why did mRS 0-1 only improve by 1% (67.7% vs 66.7%)?

### 8.1 Reason One: Higher Ceiling for mRS 0-1

Placebo group's mRS 0-1 achievement rate was already 66.7%.

Opening a gap from this baseline is extremely difficult.

### 8.2 Reason Two: Difference Between mRS 0 vs mRS 1

| mRS | Meaning |
|-----|---------|
| 0 | **Completely asymptomatic**, returned to pre-stroke state |
| 1 | Minor symptoms but not affecting daily activities |

The threshold for mRS 0 is very high—must completely return to pre-stroke state.

Many patients, even with good recovery, may retain slight residual symptoms (like occasional finger numbness), categorizing them as mRS 1 rather than mRS 0.

**LT3001's primary effect may be moving patients who "would have been mRS 2-3" to "mRS 1," rather than moving "mRS 1" to "mRS 0."**

### 8.3 Expected Improvement in Phase 3

When Phase 3 excludes mild patients (NIHSS ≥7), placebo group's mRS 0-1 achievement rate will decrease.

Expected mRS 0-1 improvement in Phase 3 will be more obvious than in Phase 2.

---

## 9. How Does Phase 3 Design Address Phase 2 Issues?

Lumosa's Phase 3 trial design addresses the structural issues from Phase 2:

| Issue | Phase 2 Situation | Phase 3 Correction |
|-------|-------------------|-------------------|
| Mild case dilution | NIHSS ≥4, includes 25% mild cases | **NIHSS ≥7**, excludes mild cases |
| Ceiling effect | Placebo 78.4% achievement | Focus on disabling patients, expect lower placebo rate |
| Population heterogeneity | Broad enrollment criteria | Focus on Motor Deficit |
| Sample size | 297 (exploratory) | 600-1,200 (pivotal) |

**Phase 3 Design Logic**:

> Exclude patients who "won't respond," focus on patients who "should respond," allowing true efficacy to emerge.

FDA's approval of this design logic is itself an indirect endorsement of Phase 2 subgroup analysis results.

---

## 10. Expected Phase 3 Efficacy

Based on Phase 2 subgroup data, we can estimate expected Phase 3 efficacy:

### 10.1 Conservative Estimate

| Endpoint | Placebo (Est.) | LT3001 (Est.) | Δ |
|----------|---------------|---------------|---|
| mRS 0-1 | 50-55% | 58-63% | **+8-10%** |
| mRS 0-2 | 65-70% | 75-82% | **+10-12%** |

### 10.2 Optimistic Estimate

If the disabling patient subgroup effect is replicated in Phase 3:

| Endpoint | Δ |
|----------|---|
| mRS 0-1 | **+12-15%** |
| mRS 0-2 | **+15-20%** |

### 10.3 Success Threshold

Generally, the "clinically meaningful threshold" for neurological drug Phase 3 trials is:

- mRS 0-1 or mRS 0-2: **Δ ≥ 7-10%**
- Statistical significance: **P < 0.05**

Based on Phase 2 subgroup data, LT3001 has a reasonable chance of meeting this threshold.

### 10.4 P-Value Prediction Matrix

For more precise evaluation of Phase 3 success probability, we can build a "P-value prediction matrix"—calculating corresponding statistical significance based on different combinations of placebo and LT3001 recovery rates.

**Model Assumptions**:

| Parameter | Setting |
|-----------|---------|
| Total trial enrollment | 800 |
| Treatment group proportion | 50.0% |
| Placebo group proportion | 50.0% |

**P-Value Matrix Table**:

![P-Value Prediction Matrix](image/-05_臨床數據完整解讀/p_value_matrix_800.png)

**Table Legend**:

- **X-axis**: LT3001 treatment group recovery rate (mRS 0-2), range 60%-80%
- **Y-axis**: Placebo group recovery rate (mRS 0-2), range 55%-69%
- **Cell values**: P-value for corresponding combination
- **Orange background**: P < 0.05 (statistically significant)
- **Blue background**: P < 0.01 (highly significant) => **Most likely Phase 3 result zone**

### 10.5 Most Likely Outcome Analysis

Estimating Phase 3 expected results based on Phase 2 data:

| Data Source | Placebo | LT3001 | Δ |
|-------------|---------|--------|---|
| Phase 2 overall (includes 25% mild) | 78.4% | 85.9% | +7.5% |
| Phase 2 moderate-severe | Lower | — | +9.3% |
| Phase 2 disabling type | Lower | — | +13%~+21% |

**Expected Changes After Phase 3 Excludes Mild Cases**:

1. **Placebo baseline decreases**: After excluding mild cases (high natural recovery rate), placebo recovery rate expected to drop to **61-65%**
2. **Δ widens**: Focusing on population with most obvious efficacy, Δ expected to widen to **+10%~+15%**

**Scenario Analysis**:

| Scenario | Placebo | LT3001 | Δ | P-value (approx) | Success? |
|----------|---------|--------|-----|------------------|----------|
| Conservative | 65% | 74% | +9% | 0.033 | ✅ |
| Base case | 63% | 74% | +11% | 0.007 | ✅✅ |
| Optimistic | 61% | 76% | +15% | <0.001 | ✅✅✅ |

**Most likely outcome zone**: Placebo **61-65%**, LT3001 **72-76%**

Within this zone, **the vast majority of combinations have P < 0.05**, many even **P < 0.01**.

**Key Conclusion**: As long as Phase 3 results fall within the "most likely zone" described above, probability of achieving statistical significance is quite high. The only concerning scenario is unexpectedly high placebo recovery (>67%) with compressed Δ (<8%), but based on Phase 3 enrollment design (excluding mild cases, focusing on disabling type), this scenario has lower probability.

---

## 11. Chapter Summary

| Key Point | Description |
|-----------|-------------|
| Surface numbers | mRS 0-2 Δ = +7.5%, mRS 0-1 Δ = +1.0% |
| Dilution factors | Mild patients (25%) + Ceiling effect (78.4%) |
| Subgroup efficacy | Moderate-severe +9.3%, Disabling +13-21%, LAA +10.4% |
| Safety | **0% symptomatic intracranial hemorrhage** (0/297) |
| FDA response | Positive response, agrees with Phase 3 design |
| Phase 3 expectation | mRS 0-2 Δ = +10-12% (conservative) |

**Core Conclusion**:

> LT3001's Phase 2 overall analysis result is a "diluted number" that does not represent the drug's true efficacy potential. Subgroup analysis shows clear efficacy signals in target patient populations, with excellent safety data. FDA's positive response confirms this assessment.

---

**[Previous Chapter: Chapter 4 — LT3001's Scientific Mechanism](-04_LT3001_Mechanism.md)** | **[Next Chapter: Chapter 6 — Competitor Analysis](-06_Competitor_Analysis.md)**

---

*This chapter is based on publicly available clinical data and regulatory documents.*
