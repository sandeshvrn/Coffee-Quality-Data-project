# Coffee-Quality-Data-project

# ☕ Coffee Quality Analysis with Power BI

## 📌 Project Overview

This capstone Power BI project analyzes a real-world coffee quality dataset to uncover insights into the key factors influencing overall cup quality. The goal is to support coffee producers, quality inspectors, and industry stakeholders in making data-driven decisions based on sensory and processing variables.

---

## 🎯 Project Objectives

- Identify **key determinants** of coffee quality based on sensory attributes like aroma, flavor, acidity, etc.
- Analyze the **relationship between processing methods**, origin regions, and total cup points.
- Explore the **impact of defects** on coffee quality scores.
- Perform **correlation analysis** to determine how individual variables contribute to final cup scores.
- Use **What-If analysis**, **DAX measures**, and **interactive visuals** to derive deep insights.

---

## 🧩 Dataset Information

- **Source**: inspired by Coffee Quality Institute data
- **Data Size**: ~200 coffee samples
- **Key Fields**:
  - `Country of Origin`
  - `Variety`
  - `Processing Method`
  - `Aroma`, `Flavor`, `Acidity`, `Body`, `Balance`, `Clean Cup`, `Sweetness`, etc.
  - `Total Cup Points`
  - `Defects` and `Moisture Content`

---

## 🧠 Key Features & Techniques

| Feature                         | Implementation                                                                 |
|--------------------------------|---------------------------------------------------------------------------------|
| **Data Cleaning**              | Handled nulls, unknowns, outliers, and inconsistent labels                      |
| **Calculated Columns/Measures**| Created custom DAX for KPIs, segmenting, and correlation scores                |
| **Advanced DAX**               | Used `SWITCH`, `CALCULATE`, `RANKX`, `ISINSCOPE`, `SELECTEDVALUE`              |
| **Drillthrough & Tooltip Pages**| Enabled for detailed exploration of origin and processing metrics              |
| **What-If Parameters**         | Simulate changes in sensory scores to observe effects on Total Cup Points       |
| **Highlighting Outliers**      | Subtle conditional formatting to flag nulls or extreme values (`#FFECB3` yellow)|

---

## 📊 Report Pages

1. **Overview Dashboard**  
   Summary KPIs, global distribution, and cup score comparison by region & method

<img width="1353" height="791" alt="image" src="https://github.com/user-attachments/assets/28c9ac0f-d322-4a07-ae6b-5fcdad5b6cdf" />


2. **Sensory Analysis**  
   Decomposition tree and scatter plot showing how individual attributes affect quality

<img width="1352" height="792" alt="image" src="https://github.com/user-attachments/assets/a1320dac-cc88-4385-a074-4c61a3f19bf8" />


3. **Defects & Quality**  
   Matrix visuals and trend lines on how defects influence final cup scores

<img width="1327" height="802" alt="image" src="https://github.com/user-attachments/assets/25674cc9-77f3-48ef-8b7e-91a7b856bdc5" />


4. **What-If Simulator**  
   Users can adjust sensory attribute sliders to observe predicted total cup score

<img width="1333" height="796" alt="image" src="https://github.com/user-attachments/assets/262f4956-eacd-4a98-acb4-efe3ee665d60" />


5. **Region Drillthrough**  
   Detailed view of coffee quality patterns by country, variety, and processing method

<img width="1343" height="807" alt="image" src="https://github.com/user-attachments/assets/cf46d54e-2940-43ef-a728-6dc5fbb7af36" />


---

## 💡 Key Insights

- **Overall, Flavor, and Aftertaste** show the highest positive correlation with `Total Cup Points`.
- **Washed Coffees** tend to score better on average compared to natural or semi-washed methods.
- Coffees with **primary defects > 1** almost always score below the 80-point specialty threshold.
- **Ethiopian, Tanzania and Taiwan** coffees are the top three rank higher across most sensory attributes.

---

## 🛠 Tools Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Excel (for pre-cleaning and metadata mapping)
- GitHub (for version control and portfolio hosting)

---


## 📌 Target Audience

- Data Enthusiasts & Analysts
- Coffee Producers & Distributors
- Quality Control Teams
- Recruiters seeking strong data storytelling and dashboarding skills

---

## 🔗 Live Demo / Preview

➡️ [**Power BI Report PDF Preview**](./Coffee_Quality_Summary.pdf)  
➡️ Attached PBIX file

---

## 📬 Contact

For collaboration, suggestions, or portfolio reviews:

**Sandesh Varun**  
📧 sandeshvrn@gmail.com
🌐 [LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)

---



