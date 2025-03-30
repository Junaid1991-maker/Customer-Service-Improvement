# Customer Service Improvement Project  
**Analyzing support interactions to boost CSAT, reduce delays, and optimize team performance.**  

---

## 📌 **Project Overview**  
- **Goal**: Identify pain points in customer service operations (returns, delays, agent performance) and recommend data-driven solutions.  
- **Data Source**: `Customer_support_data.csv` (500 interactions, July-August 2023).  
- **Tools Used**: MySQL (data processing), Jupyter Notebook (analysis + visualization).  
- **Key Metrics**: CSAT scores, response times, issue categories, agent tenure.  

---

## 📂 **Files & Structure**  
project_folder/
├── data/
│ └── Customer_support_data.csv # Raw dataset
├── scripts/
│ ├── data_cleaning.sql # MySQL queries for preprocessing
│ └── analysis.ipynb # Jupyter Notebook for analysis
├── outputs/
│ ├── heatmap.png # Key visualization
│ └── agent_performance_report.pdf # Detailed findings
└── README.md # This file


---

## 🔍 **Key Findings**  
1. **Returns Process Issues**  
   - 40% of complaints were return-related, with delays up to **23 days**.  
   - *Recommendation*: Automate approvals for returns under ₹5,000.  

2. **Team Size Matters**  
   - Small teams (<20 agents) achieved **CSAT 4.6** vs. 3.6 for large teams (>30 agents).  
   - *Recommendation*: Cap teams at 20 agents/supervisor.  

3. **Agent Performance**  
   - Top agents (>90-day tenure) resolved cases **2x faster** with higher CSAT.  
   - *Recommendation*: Pair new hires with mentors.  

---

## 🛠 **How to Reproduce**  
1. **Preprocess Data**: Run `data_cleaning.sql` in MySQL.  
2. **Analyze**: Open `analysis.ipynb` in Jupyter and execute cells.  
3. **Visualize**: Export charts to `outputs/`.  

---

## 📈 **Recommendations Implemented**  
| Action                          | Outcome (Target)                  |  
|---------------------------------|-----------------------------------|  
| Auto-approve low-value returns  | Reduce return delays by 50%       |  
| Redesign teams (20 agents max)  | Boost CSAT from 3.6 → 4.0+       |  
| Agent mentorship program        | Improve new hire resolution speed |  

---

## 📧 **Contact**  
For questions, email: [junaid19tex@gmail.com]  