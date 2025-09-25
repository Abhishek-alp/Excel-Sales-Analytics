## Sales Analytics and Reporting 📈 :

* **Project objective:**
  **1.** Build a robust **sales data model** using Power Query and Power Pivot in Excel.
  **2.** Define **custom DAX measures** to answer business-specific questions.
  **3.** Generate pivot reports to compare 2020 vs 2021 performance, identify top-performing products, analyze sales by division, and track new products introduced in 2021.

* **Purpose of analysis:** Provide a comprehensive sales performance overview that supports strategic planning in sales and marketing.

* **Importance of analyzing sales data:**

  * Understand which products drive **growth** year-over-year.
  * Benchmark top and bottom performers for targeted strategies.
  * Evaluate the **impact of new product launches**.
  * Gain geographic insights by tracking top-performing countries.

* **Role of reports:**

  * Deliver actionable insights into **growth trends** and **market performance**.
  * Highlight opportunities for **resource allocation and investment**.
  * Provide clarity for international **sales expansion strategies**.

---

## Stakeholder Questions Answered:

**Q1. What is the percentage increase in net sales from 2020 to 2021?**
✔ **Answer:** Calculated using DAX with `DIVIDE()` + `CALCULATE()` to compare yearly sales.
➡ **Insight:** Showed which products and markets contributed most to sales growth.
📎 [Attach Report Link Here]

**Q2. Which products are top and bottom performers in terms of sales and growth?**
✔ **Answer:** Identified using ranking logic with DAX measures.
➡ **Insight:** Enabled targeted strategies for promotions (top performers) and re-evaluation (underperformers).
📎 [Attach Report Link Here]

**Q3. Which products were newly introduced in 2021?**
✔ **Answer:** Detected by filtering products with 0% growth in 2020 vs sales in 2021.
➡ **Insight:** Provided visibility into new launches and their market impact.
📎 [Attach Report Link Here]

**Q4. What are the top 5 countries by net sales?**
✔ **Answer:** Extracted via Pivot Table filtering and DAX aggregation.
➡ **Insight:** Informed international sales strategies and priority market focus.
📎 [Attach Report Link Here]

**Q5. Generate a "Division" report to present the net sales data for 2020 and 2021, along with the growth percentage.**
✔ **Answer:** Built using DAX measures and Pivot Tables to compare net sales by division across years.
➡ **Insight:** Helped stakeholders see which divisions were growing faster and where corrective actions were needed.
📎 [Attach Report Link Here]

---

## Technical Skills:

* [x] Proficiency in **Power Query** for ETL (importing, cleaning, preparing sales data).
* [x] Building a relational **Power Pivot Data Model** with multiple tables.
* [x] Creating dynamic **Pivot Tables** for analysis and reporting.
* [x] Writing **DAX measures**:

  * `SUM()` → Total sales & quantity sold.
  * `DIVIDE()` + `CALCULATE()` → YoY growth % (2021 vs 2020).
  * Ranking logic → Top 10 products by growth, top/bottom 5 by quantity.
* [x] Applying filters to isolate **new products** and market insights.

---

## Soft Skills:

* [x] Problem-solving: Translating business questions into DAX and Power Pivot solutions.
* [x] Business acumen: Converting results into insights like “growth leaders,” “new product success,” and “priority markets.”
* [x] Attention to detail: Ensuring DAX logic and report filters are accurate to maintain data reliability.
* [x] Communication: Presenting findings in clear, stakeholder-friendly reports.
