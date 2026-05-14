# Casestudydefects
This analysis explores how defect severity, defect type, and inspection method influence repair cost exposure. The findings suggest that financial impact does not always align cleanly with severity classification alone. 

# Manufacturing Defects Analysis | Power BI Case Study

## Problem

Manufacturing defects are rarely just a quality issue. They create operational delays, increase repair costs, reduce customer confidence, and often hide deeper process weaknesses beneath headline KPIs.

This case study explores how defect type, severity, location, and repair cost interact inside a manufacturing environment. The focus was not simply identifying the largest number of defects, but understanding where financial and operational exposure may quietly accumulate over time.

The dataset used in this project is synthetic and designed for portfolio and demonstration purposes, but the analytical approach mirrors the type of exploratory analysis often required in real operational environments.

---

## Approach

The analysis was built in Power BI using a structured workflow focused on operational clarity rather than dashboard complexity.

### Data Preparation

* Cleaned and structured manufacturing defect records
* Standardised defect categories and severity labels
* Validated repair cost and frequency fields
* Created calculated measures for:

  * Total repair cost
  * Defect frequency
  * Severity distribution
  * Location-based comparisons

### Analytical Focus

The project explored:

* Which defect categories generated the highest operational cost
* Whether “minor” defects were financially underestimated
* The relationship between defect location and severity
* Patterns hidden behind aggregate totals

### Visual Design

The dashboard and supporting visuals were designed around:

* Executive-level readability
* Clear operational storytelling
* Reduced visual noise
* Comparisons that support decision-making rather than decoration

Visuals included:

* Treemaps
* Comparative bar charts
* Severity distribution analysis
* Cost concentration views
* Operational summary insights

---

## Solution

The analysis highlighted several operational themes:

* Total defect volume alone did not fully explain financial exposure
* Structural defects classified as “minor” generated significant cumulative repair cost
* Critical defects remained operationally important, but lower-severity recurring defects may create longer-term commercial risk
* Defect location patterns suggested areas where process review or preventative maintenance could reduce future cost accumulation

The project demonstrates how operational reporting can move beyond static KPI tracking into practical decision support.

In short: the most expensive problem is not always the loudest one.

---

## Demo

A PDF walkthrough of the Power BI case study is included in this repository.

The PDF contains:

* Executive summary
* Key findings
* Dashboard screenshots
* Visual analysis
* Operational recommendations

---

## How to Run

### Requirements

* Power BI Desktop

### Steps

1. Download or clone this repository
2. Open the `.pbix` file in Power BI Desktop
3. Refresh the dataset if required
4. Explore the visuals and filters interactively

### Repository Contents

* `Manufacturing_Defects.pbix`
* `Manufacturing_Defects_Case_Study.pdf`
* `README.md`

---

## About StraightLine Data & Training

StraightLine Data & Training focuses on turning operational complexity into practical insight through:

* Data analysis
* Power BI reporting
* ERP/SAP reporting support
* Training and user enablement

Clarity. Insight. Confidence.

Good analysis does not simply describe what happened. It helps people decide what matters next.
