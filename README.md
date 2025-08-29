# ⚡🚗 Electric Vehicle Capstone Project – US EV Registrations & Renewable Energy  

_Analyzing the relationship between electric vehicle (EV) adoption and renewable energy production across the United States (1990–2019) using Python, statistical analysis, and geospatial visualization._  

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project explores how the growth of **electric vehicle (EV) registrations** is influenced by **renewable energy production** across U.S. states.  
It leverages state-level data (1990–2019) to uncover patterns, correlations, and disparities using:  
- **Time Series Analysis**  
- **Geospatial Visualization**  
- **Correlation & Relationship Analysis**  

The insights aim to inform **policy decisions**, **infrastructure investments**, and the U.S. transition to a **low-carbon economy**.  

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

With rising concerns about climate change, air pollution, and fossil fuel dependency, EV adoption and renewable energy development are critical. This project addresses:  
- Which states lead or lag in EV adoption and renewable energy production?  
- Is there a correlation between renewable energy availability and EV adoption?  
- How have EV registrations and renewable energy trends evolved (1990–2019)?  
- What policy or infrastructure factors influence disparities?  
- How can states align clean energy and transportation electrification goals?  

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

Datasets used in this project:  
- **States_Electric_Vehicle_Registrations_2018.xlsx** → EV registrations by state  
- **States_All_Vehicle_Registrations_2018.xlsx** → Total vehicle registrations  
- **States_Annual_Energy_Generation_Sources_1990_2019.xlsx** → Annual energy production by source (Solar, Wind, Hydro, Coal, etc.)  
- **state_codes.xlsx** → U.S. state codes mapping  

📥 Dataset Source: [Google Drive Link](https://drive.google.com/drive/folders/1Fu_2MhZ80v2nPq2OLFDWfBQQVseWR_BV?usp=drive_link)

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- **Python (Jupyter Notebook)**  
  - Pandas, NumPy → Data processing  
  - Matplotlib, Seaborn → Visualizations  
  - Plotly Express → Interactive charts & maps  
- **Geospatial Analysis** (Choropleth maps)  
- **GitHub** for version control  

---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>


---

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Removed unnecessary rows/columns  
- Handled missing values & standardized formats  
- Converted energy values to integer formats (MWh/GWh)  
- Created pivot tables for state-level and yearly summaries  
- Merged datasets using state codes  

---

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Visualizations Performed:**  
- Top 10 EV adopting states (bar chart)  
- Producer-wise energy generation (bar chart)  
- Top 4 energy sources by share (pie chart)  
- Correlation heatmap (EV vs energy sources)  
- Time series plots of energy generation (1990–2019)  
- Choropleth maps for EV adoption across U.S. states  
- Bubble plots (EV adoption vs energy generation)  

---

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **Which energy sources dominate?** → Natural Gas, Nuclear, and Hydro.  
2. **Are renewables linked with EV adoption?** → Moderate positive correlation (Wind & Solar).  
3. **Do coal-heavy states adopt EVs?** → Lower adoption in fossil-fuel-dependent states.  
4. **Which regions lead?** → Coastal, Western, and Northeastern states.  
5. **Where is EV adoption lagging?** → Central & rural states.  

---

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:
```bash
git clone https://github.com/Neelam-pal/electric-vehicle-capstone.git
cd electric-vehicle-capstone
```
2. Open the Notebook:
```bash
jupyter notebook notebooks/ElectricVehicle.ipynb
```
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>
<ul>
  <li>Promote EV adoption in coal-heavy & rural states via incentives.</li>
  <li>Expand renewable energy projects (Solar &amp; Wind) in EV-leading states.</li>
  <li>Align transportation electrification with clean energy goals.</li>
  <li>Educate consumers in low-adoption states through awareness campaigns.</li>
  <li>Urban centers should lead EV-grid integration (V2G) for sustainability.</li>
</ul>

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Neelam Pal**  
Data Analyst  
📧 Email: np782906@gmail.com  
🔗 [LinkedIn](www.linkedin.com/in/neelam-pal-30b4a12b8)  
