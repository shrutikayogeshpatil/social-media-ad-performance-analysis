

#  Social Media Advertisement Performance Analysis

##  Project Overview

This project analyzes **social media advertising campaign data** to identify which advertisements perform best in terms of **link clicks and lead generation**.

The analysis was developed using **Python and Google Colab**, with a focus on transforming raw advertising data into actionable insights that can support **digital marketing campaign optimization and decision-making**.

The project answers the key business question:

> **Which advertisement is performing best, and what can we learn from its performance?**

---

## Objectives

The main objectives of this analysis are to:

* Analyze advertisement-level performance
* Compare link clicks across different advertisements
* Compare Meta lead generation
* Calculate lead conversion rates where applicable
* Identify the strongest traffic-generating advertisement
* Identify the strongest lead-generating advertisement
* Visualize campaign performance
* Generate actionable digital marketing recommendations

---

## Technologies & Tools

| Tool             | Purpose                                   |
| ---------------- | ----------------------------------------- |
| **Python**       | Data analysis                             |
| **Pandas**       | Data manipulation and aggregation         |
| **NumPy**        | Numerical calculations                    |
| **Matplotlib**   | Data visualization                        |
| **Google Colab** | Development environment                   |
| **GitHub**       | Project documentation and version control |

---

## Dataset

The dataset contains advertisement-level campaign data including:

* Advertisement name
* Link clicks
* Meta leads
* Results
* Impressions
* Reach
* Amount spent

### Advertisements Analyzed

The dataset contains four advertisements:

1. `FC_CAP_YMK`
2. `STATIC_1`
3. `Student_Reel_1_Admissions_Open`
4. `YMKCOE_STATIC_2`

---

## Analysis Workflow

The project follows the following analytical workflow:

```text
Raw Advertising Data
        ↓
Data Loading
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Advertisement-wise Aggregation
        ↓
KPI Analysis
        ↓
Performance Comparison
        ↓
Data Visualization
        ↓
Business Insights
        ↓
Marketing Recommendations
```

---

##  Key Performance Indicators

The analysis primarily focuses on the following measurable KPIs:

###  Link Clicks

Measures the number of users who clicked the advertisement link.

###  Meta Leads

Measures the number of leads generated through the advertisements.

###  Lead Conversion Rate

Calculated as:

```text
Lead Conversion Rate =
(Meta Leads / Link Clicks) × 100
```

This provides an indication of how effectively clicks are converted into leads.

---

##  Performance Summary

Based on the analyzed campaign data:

| Advertisement                  | Link Clicks | Meta Leads |
| ------------------------------ | ----------: | ---------: |
| FC_CAP_YMK                     |          60 |          9 |
| STATIC_1                       |           3 |          1 |
| Student_Reel_1_Admissions_Open |          28 |          9 |
| YMKCOE_STATIC_2                |          46 |         10 |

###  Traffic Leader

**FC_CAP_YMK**

Generated the highest number of link clicks, making it the strongest advertisement for driving traffic.

###  Lead Generation Leader

**YMKCOE_STATIC_2**

Generated the highest number of Meta leads, making it the strongest advertisement for lead generation by volume.

###  Conversion Efficiency

The conversion-rate analysis provides an additional perspective by comparing leads relative to link clicks.

However, conversion rate should be interpreted alongside **sample size**, since an advertisement with very few clicks can produce an artificially high conversion rate.

---

##  Visualizations

The project includes several visualizations designed to communicate campaign performance clearly.

###  Advertisement Performance Leaderboard

Compares advertisements based on their lead-generation performance.

###  Clicks vs Leads Analysis

Shows the relationship between link clicks and generated leads for each advertisement.

###  Campaign Performance Matrix

Positions advertisements according to their ability to generate:

* Traffic
* Leads

This helps distinguish between advertisements that primarily attract attention and those that generate stronger business outcomes.

###  Advertisement Scorecards

Provides an individual performance view of each advertisement, making comparison easier for marketing teams.

---

##  Business Insights

The analysis provides several practical insights for digital marketing decision-making:

### 1. Traffic and lead generation are different objectives

The advertisement generating the most clicks is not necessarily the advertisement generating the most leads.

Therefore, campaigns should be evaluated using **multiple KPIs rather than clicks alone**.

### 2. Strong creatives can drive traffic

`FC_CAP_YMK` generated the highest number of link clicks, indicating strong ability to attract users and drive traffic.

### 3. Lead generation should be prioritized for conversion-focused campaigns

`YMKCOE_STATIC_2` generated the highest number of Meta leads and therefore represents the strongest performer when the primary objective is lead generation.

### 4. Conversion rate needs context

Conversion rate is useful for evaluating efficiency, but it should always be considered alongside the number of clicks and leads.

---

##  Marketing Recommendations

Based on the analysis, the following actions are recommended:

###  Scale Strong Lead Generators

Consider increasing the focus on advertisements that consistently generate higher numbers of leads.

###  Study High-Traffic Creatives

Analyze the creative elements of high-click advertisements, including:

* Visual design
* Headline
* CTA
* Copy
* Audience targeting

These elements can potentially be incorporated into future campaigns.

###  Optimize the Conversion Journey

If an advertisement receives many clicks but comparatively fewer leads, investigate:

* Landing-page experience
* CTA clarity
* Form length
* Page loading speed
* Message consistency between advertisement and landing page

###  Continue A/B Testing

Future campaigns should test variations of:

* Static creatives
* Reels/videos
* Headlines
* CTAs
* Ad copy
* Audience segments

This can help identify which creative and targeting combinations consistently produce better results.

---

##  Data Limitations

The dataset contains fields for **Impressions, Reach, and Amount Spent**, but these values are not available as usable numerical data in the analyzed records.

Therefore, the following metrics were **not calculated**:

* CTR
* CPC
* CPM
* CPA
* ROAS

The analysis instead focuses on the available measurable outcomes:

**Link Clicks + Meta Leads + Lead Conversion Rate**

This ensures that the conclusions remain based on the available campaign data rather than estimated values.

---

##  Project Structure

```text
social-media-ad-performance-analysis/
│
├── README.md
│
├── Social_Media_Ad_Analysis.ipynb
│
├── visuals/
│   ├── ad_leaderboard.png
│   ├── clicks_vs_leads.png
│   └── performance_matrix.png
│
└── data/
    └── sample_advertising_data.xlsx
```

> **Note:** If the original dataset contains confidential company/client information, it should not be uploaded to a public GitHub repository. Use an anonymized or sample dataset instead.

---

##  How to Run the Project

### Option 1 — Google Colab

Open the `.ipynb` notebook in Google Colab and run the cells sequentially.

### Option 2 — Local Environment

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib openpyxl
```

Then open the notebook using Jupyter Notebook or JupyterLab.

---

##  Future Improvements

The project can be extended by incorporating:

* Campaign spend analysis
* CTR and CPC analysis
* CPA analysis
* ROAS calculation
* Audience demographic analysis
* Placement-level analysis
* Campaign date/time analysis
* A/B testing analysis
* Landing-page performance
* Power BI marketing dashboard
* Automated campaign performance reporting

---

##  Author

**Shrutika Patil**

AI & Data Science Engineering Student
Digital Marketing & Data Analytics

### Skills Demonstrated

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Data Analysis` · `Data Visualization` · `Digital Marketing Analytics` · `Performance Marketing`

---

##  Project Takeaway

> **The best-performing advertisement depends on the campaign objective.**

An advertisement that generates the most traffic may not generate the most leads. Therefore, effective digital marketing analysis should combine **performance metrics, conversion efficiency, creative analysis, and business objectives** to make data-driven campaign decisions.
