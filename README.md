1. 🦠 COVID-19 Analytics Dashboard  

An interactive Power BI dashboard designed to analyze the global and state-level impact of the COVID-19 pandemic. It tracks confirmed cases, recoveries, deaths, and vaccination progress over time, providing actionable insights into pandemic trends and vaccine adoption.  

---

2. 📌 Short Description / Purpose  

The COVID-19 Analytics Dashboard helps users explore the spread and recovery trends of the COVID-19 pandemic worldwide and within India. It provides a detailed breakdown of confirmed cases, deceased counts, recoveries, and vaccination coverage, offering valuable insights for researchers, policymakers, and healthcare analysts.  

---

3. 🛠 Tech Stack  

📊 Power BI Desktop -- Core visualization platform.  
📂 Power Query -- Data transformation and cleaning.  
🧠 DAX (Data Analysis Expressions) -- For calculated KPIs (active cases, vaccination %).  
📝 Data Modeling -- Establishes relationships between case counts, vaccines, and geography.  
📁 File Format -- .pbix for dashboard, .pdf / .png for exports.  

---

4. 📁 Data Sources  

The dashboard is powered by both global and India-specific datasets:  

**Global Sources:**  
• World Health Organization (WHO): Global confirmed, recovered, and deceased case counts  
• Our World in Data (OWID): Vaccination progress and vaccine adoption  
• Johns Hopkins University CSSE: Worldwide time-series case and death counts  

**India-specific CSV Files:**  
• case_time_series.csv – Daily India-level COVID-19 case progression (confirmed, recovered, deceased)  
• raw_data_Indian_states.csv – State-level COVID-19 data (confirmed, recovered, deceased, vaccination coverage)  
• vaccination-data.csv – India’s vaccination dataset (total doses, partial & full vaccination, vaccine manufacturer distribution)  

**Scope:** Covers both global and India (national & state-level) datasets  
**Attributes Include:** Confirmed, Recovered, Deceased cases, Vaccinations (partial & fully vaccinated), Vaccine Types (AstraZeneca, Pfizer, Janssen, etc.), Country, State, and WHO Region breakdowns  

**Timeline:** Jan 2020 – Oct 2021  

---

5. 🌟 Features / Highlights  

**Business Problem**  
COVID-19 data is complex and constantly evolving. Understanding how the virus spread, recovery trends, and vaccination rates can be challenging without clear visualization.  

**Goal of the Dashboard**  
To deliver a tool that:  
- Tracks the global confirmed, deceased, and recovered cases  
- Monitors vaccination progress by country, state, and vaccine type  
- Analyzes pandemic evolution by year, quarter, and month  
- Provides state-level insights (e.g., Assam case and recovery trends)  

**Walkthrough of Key Visuals**  
- **Key KPIs**:  
  Confirmed: 8,189M  
  Recovered: 7,721M  
  Deceased: 110M  
  Vaccinations: 8,159M  
  Fully Vaccinated: 7,728.79M  

- **Confirmed & Recovered by State**: Maharashtra, Kerala, and Karnataka showing the highest confirmed and recovered counts.  
- **Most Used Vaccines**: Distribution of vaccine adoption – AstraZeneca (58.3%), Beijing CNBG, Janssen, Pfizer, etc.  
- **Cases by Year, Quarter, Month**: Time-series tracking of confirmed, recovered, and deceased.  
- **Vaccination Progress**: Percentage of fully vaccinated population vs total.  
- **Deceased & Recovered by State**: State-level breakdowns (e.g., Assam's confirmed, recovered, and deceased trends).  

**Business Impact & Insights**  
- Policy Support: Helps governments plan healthcare responses  
- Vaccine Monitoring: Tracks adoption and coverage rates globally  
- Trend Analysis: Identifies waves of infection and recovery patterns  
- Public Health Planning: Aids in allocating resources to high-burden states/countries  

---

6. 🔗 Dashboard Preview

https://github.com/sahith-patnala/COVID-19/blob/main/COVID19.pdf
