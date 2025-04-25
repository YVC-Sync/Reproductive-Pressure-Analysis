# 🧠 How Clustering Helped Me Spot Policy Gaps in Fertility Support

When I was working on the Reproductive Pressure project, I kept seeing countries that spent a lot on family benefits… but still had some of the lowest fertility rates in the world.
That disconnect stuck with me. So I decided to go deeper not just by looking at **how much** countries spend, but **how that support is structured**. That’s where clustering came in.

---

## 🔍 What I Wanted to Understand

I wanted to answer one core question:  
**Are countries that offer more types of support actually seeing better fertility outcomes?**

But instead of just comparing countries one by one, I used clustering to group them based on the **traits of their support systems** not just the total investment.

---

## 🧩 What Variables I Used

For each country, I included:

- **Cash benefits (% of GDP)**  
- **Childcare support (0–2 years)**  
- **Education and family services**  
- **Tax relief and leave policies**

All values were scaled using StandardScaler so clustering wasn’t biased by any one variable.

---

## 🧪 The Clustering Process

I used KMeans to test groupings from 2 to 8 clusters, then applied the **elbow method** to find the ideal number. Three clusters made the most sense each one represented a **different type of support system**.

---

## 📊 What I Found

- **Cluster 1** had the highest spending across the board but still low fertility (think Japan and Korea).  
- **Cluster 2** included countries with **moderate support and stronger outcomes** (like Mexico and New Zealand).  
- **Cluster 3** had patchy support, especially in early childcare and education.

The most interesting part?  
**Cluster 1 spent the most but didn’t deliver better results.** That shifted my focus from investment size to investment structure.

---

## 🧠 Why It Mattered

Clustering helped me **cut through averages** and find patterns that wouldn’t show up in standard comparison charts.

This method helped explain:

- Why **high spending alone doesn’t solve fertility decline**  
- How **policy structure** (not just totals) creates long-term outcomes  
- Which countries might be **overlooked** when judged on spending totals alone

---

## 🔗 Want to see the full analysis?

Check out the notebook here: [6.5_Clustering_Motherhood_Policy_Analysis.ipynb](../notebooks/6.5_Clustering_Motherhood_Policy_Analysis.ipynb)

Or explore the full project:
- [GitHub Repository](https://github.com/YVC-Sync/Reproductive-Pressure-Analysis)
- [Tableau Storyboard](https://public.tableau.com/app/profile/yarisel.velacanto/viz/ReproductivePressureTheHiddenCostsofGlobalFertilityDecline)

