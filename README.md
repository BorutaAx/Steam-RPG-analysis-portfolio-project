# The RPG Renaissance: A Data-Driven Journey through the Genre’s Evolution

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Tools](https://img.shields.io/badge/Tools-Python%20|%20Tableau-blue)

## Project Overview
Is the RPG genre truly in a "Modern Renaissance"? This project analyzes over 20 years of Steam data to investigate the resurgence of Role-Playing Games. By comparing the **Golden Age (pre-2010)**, the **Intermediate Period (2011-2019)**, and the **Modern Renaissance (2020-Present)**, I explore trends in release volume, game quality, and market positioning.

**[VIEW THE INTERACTIVE STORY ON TABLEAU PUBLIC](https://public.tableau.com/app/profile/marek.grobelny/viz/SteamRPGPortfolioProject/TheRPGRenaissanceAData-DrivenAnalysisoftheGenresEvolution)**

---

## Key Insights
* **Volume Explosion:** RPG releases have reached an all-time high since 2020, significantly outperforming the early 2000s in terms of quantity.
* **Quality Parity:** Despite the surge in new titles, the median user score has remained remarkably stable (80-85%). Modern developers are successfully maintaining the high standards set by "Golden Age" classics.
* **Market Diversity:** The "Price vs. Quality" analysis reveals a healthy ecosystem where $60+ AAA masterpieces (like *Baldur's Gate 3*) coexist with high-value indie gems.

---

## Tech Stack & Methodology
1.  **Data Cleaning (Python/Pandas):** * Filtered Steam datasets for RPG-specific titles.
    * Handled missing values and categorized games into three distinct historical eras.
    * Applied review count thresholds (>300 reviews) to ensure data reliability and filter out "noise."
2.  **Exploratory Data Analysis (EDA):**
    * Statistical analysis of user scores across different periods.
    * Pricing analysis to identify market trends.
3.  **Visualization (Tableau):**
    * Created an interactive **Tableau Story** to guide users through the narrative.
    * Utilized Box Plots for quality stability, Scatter Plots for price-value mapping, and Treemaps for market share.

---

## Data Limitations & Notes
* **Steam Release Dates:** It is important to note that for many classic titles (e.g., *Baldur's Gate II*), Steam lists the "Enhanced Edition" or digital re-release date (e.g., 2013) rather than the original launch year (2000). 
* **Analysis Scope:** For the purpose of this project, I used Steam's database as the primary source, acknowledging that "Golden Age" representation reflects their digital presence on the platform.

---

## Project Structure
* `rpg_analysis.ipynb`: The Jupyter Notebook containing all Python code for data processing and cleaning.
* `rpg_renaissance_clean.csv`: The final, cleaned dataset used for Tableau visualizations.

---

## Contact
**[Marek Grobelny]** [marek.grobelny92@gmail.com]