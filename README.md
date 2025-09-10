 # Reproductive Pressure: A Data-Driven Analysis  
**The Hidden Costs of Fertility Decline: What Governments Ask of Women and What They Refuse to Give**

<img src="reproductive_pressure_logo.png" alt="Reproductive Pressure Logo" width="150">

This project digs into the global fertility crisis what’s driving it, who’s paying the price, and whether all the government “support” actually helps. I brought together datasets from the World Bank, OECD, and OWID to trace how financial incentives, care policies, and demographic pressure collide. Then I broke that down into a story about women, equity, and the future of population policy. Everything’s visualized in Tableau & Python, with a mix of time series, regression, and clustering to uncover the patterns most people miss.

---

## 🚀 Fast Facts for Busy Reviewers

- **Tool Stack:** Python (Pandas, Seaborn, Statsmodels), Jupyter, Tableau  
- **Data Sources:** World Bank, OECD, Our World in Data  
- **Key Wins:**
  - Pulled together 15+ messy global datasets into a clean, analysis-ready frame  
  - Modeled long-term fertility shifts in Japan, Korea, and the U.S.  
  - Used clustering to go beyond “total spending” and actually break down support structures  
  - Built a clean, interactive Tableau storyboard with six connected story points  

---

## 🎯 The Challenge

Fertility rates are dropping everywhere even in countries pushing aggressive pro-natalist policies. That raises some big questions:

- Why aren’t financial incentives working?  
- What types of support *actually* help people start families?  
- Who’s being expected to carry the weight of population growth?

To explore that, I looked at:
1. Trends over time in fertility vs. social spending  
2. Support structure types across 40+ countries  
3. Where Japan, Korea, and the U.S. are headed long-term

---

## 🧹 Data Cleaning Highlights

Getting everything into one clean dataset took some doing:

- Combined OECD + World Bank public spending data (with lots of reshaping)  
- Filled missing values for South Korea using OWID fertility sources  
- Aligned country names, time spans, and support definitions  
- Created a final cleaned dataset for Tableau: `final_merged_data.csv`

All cleaned and final data files are in the `data/` folder.

---

## 📊 Key Visuals & What They Show

- **Fertility Divergence Bar Chart** - Which countries are furthest from replacement  
- **Support vs. Fertility Scatterplots** - Comparing spending to outcomes  
- **Cluster Profiles** - What kind of support structure each country offers  
- **Fertility Time Series (Japan, Korea, U.S.)** - Where we’ve been, and where we’re going

👉 [View the final Tableau storyboard here](https://public.tableau.com/app/profile/yarisel.velacanto/viz/ReproductivePressureTheHiddenCostsofGlobalFertilityDecline/ReproductivePressureTheHiddenCostsofGlobalFertilityDecline)

---

## 🧠 Main Insights (Recap)

- **Throwing money at the problem doesn’t work**  
  Countries with high spending still had some of the lowest birth rates.

- **South Korea is a cautionary tale**  
  Tons of investment, but little real infrastructure or gender equity.

- **It’s not just about support it’s about *how* it’s structured**  
  Clusters showed that leave policies and childcare access mattered more than cash.

- **The burden keeps falling on women**  
  Most of these policies still assume moms will be the default caregivers.

---

## 💼 From Data to Decisions

Here’s what this work says to policymakers and organizations:

1. **Rethink what “family-friendly” really means** more childcare, less token cash  
2. **Focus on structure, not just spending totals**  
3. **Don’t ignore the gender gap** baked into how support is delivered  
4. **Start forecasting now** some of these demographic shifts are already baked in

---

## 🛠️ Tools Used

- **Python** for data wrangling, clustering, regression, and time series  
- **Jupyter** for organized, documented notebooks  
- **Tableau** to build a story that’s easy to follow and backed by data  

---

## 📝 Additional Insights

- [How Clustering Helped Me Spot Policy Gaps in Fertility Support](blog/clustering-policy-gap.md)

---

## 📁 Repository Structure

```bash
Reproductive-Pressure-Analysis/
│
├── data/
│   ├── original/    # Raw downloads from World Bank, OECD, OWID
│   ├── cleaned/     # Cleaned and renamed versions with aligned formatting
│   └── prepared/    # Final datasets used in modeling or Tableau
│
├── notebooks/       # All project notebooks for EDA, time series, clustering, and regression analysis
│
├── tableau/
│   ├── Tableau_Link.txt         # Link to Tableau Public Story
│   └── images/                  # Dashboard screenshots
│
├── case-study/
│   ├── Reproductive_Pressure_Case_Study.pdf        # Final case study for CareerFoundry
│   └── Bonus_Task_UX_UI_Feedback.pdf               # UX/UI design feedback document
│
├── reproductive_pressure_logo.png   # Header image for GitHub visual polish
└── README.md                        # Project overview, insights, and repo guide
```
### 🔗 View the Full Case Study  
[📂 www.yariselvelacanto.com/analyst](http://www.yariselvelacanto.com/analyst)
