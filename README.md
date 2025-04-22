## 🧠 Project: Analyzing Excess Mortality During COVID-19

This project explores how different COVID-19 response strategies — including **vaccination rates**, **public health stringency measures**, and **healthcare capacity** — affected excess mortality across countries categorized as Developed, Developing, and Underdeveloped.

### 🔍 Key Highlights:
- Developed a clean, structured dataset using **Our World in Data** and the **World Mortality Dataset** with 26,520 records across 111 countries
- Preprocessed 400K+ raw rows down to weekly summaries, removing missing values and categorizing nations by GDP-based development status
- Applied **ANOVA** and **Tukey HSD** to evaluate statistical differences in mortality across regions
- Built a **Ridge Regression model** (R² = 0.72) with interaction terms to identify which interventions worked best for each development group

### 📈 Key Findings:
- 💉 **Vaccinations** were most effective in Developed countries with robust healthcare and distribution systems
- 🏥 **Healthcare capacity** (hospital beds, ICUs) had the strongest impact in Underdeveloped nations, reducing mortality significantly
- 📏 **Public health interventions** (lockdowns, testing) consistently reduced mortality across all regions, especially where healthcare systems were weaker

### ⚙️ Tools & Techniques:
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Statistical Modeling**: ANOVA, Tukey HSD, Ridge Regression
- **Feature Engineering**: Composite metrics for healthcare capacity and policy measures, interaction terms by region
- **Data Visualization**: Time-series trends, scatter plots, correlation matrices

> 📌 **Conclusion**: This study highlights the importance of integrated and context-sensitive strategies in pandemic response. A one-size-fits-all approach doesn't work — policy and healthcare interventions must align with a country's development level for optimal impact.

