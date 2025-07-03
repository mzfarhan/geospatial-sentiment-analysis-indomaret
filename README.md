# 📊 Jakarta's Retail Landscape: A Geospatial and Sentiment Analysis of Indomaret

**Project Tagline:** *A deep-dive analysis into Indomaret's market position in Jakarta, translating location data and thousands of customer reviews into a precise, three-part strategic action plan.*

![Project Banner](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9d/Logo_Indomaret.png/1200px-Logo_Indomaret.png)

---

## 1. 📊 Executive Summary

This project presents a comprehensive analysis of Indomaret in Jakarta, merging **geospatial distribution** with **customer sentiment** to forge a data-driven strategy for market leadership.

While Indomaret enjoys dominant market penetration, the analysis reveals a critical disconnect between location strategy and on-the-ground customer experience. The findings culminate in a **three-part strategic action plan**, with each part designed to address a specific, data-verified weakness in current operations. This ensures that resources are allocated precisely to initiatives with the highest potential return on investment.

---

## 2. 🎯 The Business Problem

In Jakarta's saturated retail market, physical presence alone is not a defensible moat. Competitors are fierce, and customer loyalty is fragile. To maintain and grow its market share, Indomaret needs answers to critical business questions:
* Are our stores truly capturing their potential, or are we losing customers due to correctable issues?
* What are the specific, actionable drivers of customer satisfaction and dissatisfaction?
* How can we prioritize operational improvements and capital expenditures for the highest possible return?

This analysis directly tackles these questions to provide a clear path forward.

---
## 3. 🛠️ Analytical Framework & Technology

This analysis was executed using the following framework and technologies to move from raw data to strategic insight:

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-313131?style=for-the-badge&logo=matplotlib&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-31753C?style=for-the-badge&logo=leaflet&logoColor=white)

1.  **Data Sourcing:** Utilized the **Google Places API** to collect location data and thousands of customer reviews for Indomaret outlets across Jakarta.
2.  **Geospatial Analysis:** Mapped store locations with **Folium** to visualize market penetration and identify clusters of high density.
3.  **Sentiment Quantification:** Processed customer reviews to calculate sentiment polarity scores, revealing that nearly **70% of stores maintain a positive rating (>4.0)**.
4.  **Thematic Analysis:** Used **WordCloud** and keyword frequency analysis to identify the core topics driving positive and negative sentiment.

---

## 4. 💡 Key Insights Linked to Action

The analysis surfaced three distinct, actionable insights that directly map to the proposed strategic initiatives.

| Insight                                                        | Evidence from Data                                                              | Leads to...                                                                      |
| :------------------------------------------------------------- | :------------------------------------------------------------------------------ | :---------------------------------------------------------------------------------------- |
| **1. Service Quality is the #1 Driver of Complaints** | "Cashier" and "Service" are the most dominant keywords in negative reviews, pointing to direct, emotional service failures. | **Action 1: Focus on Staff Training** |
| **2. Facility Convenience is a Decisive Factor**| "Parking" is the most frequently mentioned *facility*, indicating it is a foundational part of the customer journey. | **Action 2: Prioritize Parking** |
| **3. Brand Risk is Highly Concentrated** | Negative sentiment is not evenly distributed; a small number of underperforming stores disproportionately impact the brand. | **Action 3: Investigate Outliers** |

---

## 5. 🚀 A Three-Part Strategic Action Plan

Based on the insights, a precise, three-part action plan is recommended:

### Action 1: Focus on Cashier Staff Training
* **Business Justification:** This action directly targets the most significant source of customer dissatisfaction. Improving service at this critical touchpoint offers the highest immediate return in terms of reducing negative sentiment and improving brand perception.
* **Proposed Initiatives:**
    1.  **Develop "Customer Service Excellence" Curriculum:** A mandatory training program focusing on speed, courtesy, and effective problem resolution.
    2.  **Re-engineer Queue Management SOPs:** Optimize checkout flows to minimize wait times during peak hours.
    3.  **Launch a Staff Recognition Program:** Introduce a rewards system for staff who consistently receive positive customer feedback.

### Action 2: Prioritize Parking Convenience
* **Business Justification:** While service failures *anger* customers, facility friction *deters* them. Winning on convenience is a powerful long-term strategy to increase store traffic and build loyalty. Addressing the most-mentioned facility is the logical first step.
* **Proposed Initiatives:**
    1.  **Conduct a System-Wide Parking Audit:** Assess the availability, security, and ease-of-access at all key outlets.
    2.  **Develop a "Standardized Parking Mandate":** Create clear, enforceable standards for all store locations.
    3.  **Form a Public-Private Task Force:** Proactively establish cooperation with local authorities to manage the surrounding areas and ensure a safe, orderly environment for customers.

### Action 3: Investigate Problematic Outlets
* **Business Justification:** This is a proactive "brand health" initiative. By surgically addressing the worst-performing stores, we can mitigate brand damage, prevent the spread of negative word-of-mouth, and turn liabilities into assets.
* **Proposed Initiatives:**
    1.  **Create a "Bottom 10" Watchlist:** Use sentiment scores to identify the 10 lowest-rated stores for immediate attention.
    2.  **Deploy a Mystery Shopper Program:** Conduct unannounced on-site visits to gather qualitative data on the root causes of poor performance.
    3.  **Implement Focused Turnaround Plans:** Develop and execute a specific, time-bound improvement plan for each store on the watchlist.

---

## 6. 📂 Project Structure & Usage

This repository contains the full analysis and presentation materials.

* `/Indomaret_Store_Location_Analysis_in_Jakarta.ipynb`: The main Jupyter Notebook containing all code.
* `/Analisis data lokasi indomaret di jakarta by Muhammad Zulfarhan.pdf`: The final presentation deck.
* `requirements.txt`: A list of all Python libraries required to run the notebook.

#### **Running the Analysis:**
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mzfarhan/geospatial-sentiment-analysis-indomaret.git](https://github.com/mzfarhan/geospatial-sentiment-analysis-indomaret.git)
    cd geospatial-sentiment-analysis-indomaret
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook Indomaret_Store_Location_Analysis_in_Jakarta.ipynb
    ```
---

## 7. 🔮 Future Opportunities

This analysis serves as a foundation for deeper investigations, including:
* **Competitive Benchmarking:** A direct geospatial and sentiment analysis against key competitors like Alfamart.
* **Predictive Modeling for Site Selection:** Using existing data to build a model that predicts the potential success of new store locations.
* **Advanced Topic Modeling:** Going beyond keywords to identify more nuanced complaint categories.

---

## 8. 👨‍💻 Contact

* **Muhammad Zulfarhan**
* **LinkedIn:** [https://www.linkedin.com/in/muhammad-zulfarhan-1b3921206/](https://www.linkedin.com/in/muhammad-zulfarhan-1b3921206/)
