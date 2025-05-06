# Hello, I'm Jacob 👋

I am a **Senior Computer Science** student and my main focus this year was a project leveraging machine learning to improve public transit systems (under NDA), so some details are kept high-level.

---

## Leveraging AI to Improve Public Transit

**Technologies:** PyTorch, GCP Vertex AI, Google BigQuery

**Overview:**
A scalable machine learning pipeline designed to optimize public transit routes and schedules by predicting demand patterns and identifying inefficiencies. We worked directly with the client’s ridership and maintenance datasets, enriching them with multiple external sources.

**Process & Methodology:**

1. **Data Acquisition & Preparation:**

   * Ingested and cleaned large-scale ridership and maintenance records using BigQuery and the Pandas Python library.
   * Integrated external data: weather, air quality index (AQI), consumer price index (CPI), and gas prices.
   * Engineered features capturing temporal and internal influences on transit usage.
2. **Exploratory Data Analysis (EDA):**

   * Identified anomalies and gaps in the client’s data collection pipeline.
   * Discovered previously untracked factors with strong correlation to ridership.
3. **Model Development:**

   * Developed a high-performance regression model in Vertex AI to predict daily ridership.
        * Achieved **R² = 0.967** and **MAPE = 5.25%**, demonstrating robust predictive accuracy.
   * Developed a PyTorch nerual network with comparable (slightly worse) performance.
        * Could be used as an alternative to avoid the high costs of GCP.

4. **Decision Support Findings:**

   * Highlighted shortcomings in the existing data pipeline and recommended improvements.
   * Quantified the impact of environmental and economic variables on ridership to guide resource allocation.

**Current Status:**

* Presenting our findings to the client’s board and stakeholders next week; awaiting feedback.

**General Results & Impact:**

* Enabled **data-driven decision-making** to reduce wait times and operational costs.
* Provided actionable recommendations for enhancing data collection and feature tracking.

> 📋 *Detailed performance metrics and proprietary findings are under NDA.*

---

## 🛠️ Technical Skills

* **Languages:** Python, SQL
* **Machine Learning & Data:** PyTorch, scikit‑learn, EDA, feature engineering
* **Cloud:** GCP (Vertex AI, BigQuery, Cloud Functions)
* **Tools:** Git, Tableau

---

## 📚 Education

**Bachelor of Science in Computer Science**

Oregon State Univeristy

*Expected Graduation:* December 2025


---

## 📫 Contact

Feel free to reach out for collaborations or questions:
✉️ [jacobnunez99@gmail.com](mailto:jacobnunez99@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/jacob-nunez-135377130/)
