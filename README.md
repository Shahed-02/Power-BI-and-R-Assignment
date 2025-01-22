# 🌐 Sales and Revenue Dashboard: Power BI, R, and Excel

## 🔍 Project Overview
This project analyses sales, revenue, and movie performance data to uncover business and entertainment trends. Using **Power BI** for advanced visualization, **R** for exploratory data analysis (EDA), I created interactive dashboards and clean datasets that provide actionable insights. 📊✨

The project highlights:
- **Overall sales performance** 🛍️ and revenue growth trends.
- **Genre analysis** 🎬 to identify top-performing movie categories.
- **Product-level revenue breakdowns** 🛒 for better inventory planning.
- **Movie profitability analysis** 🎥 using R and Excel for data cleaning and insights.

---

## 🛠️ Tools and Skills  

### 🟡 Power BI: Advanced Visualization and Reporting  
- **Data Cleaning** 🧹: Imported raw sales data and cleaned it to ensure consistency and accuracy.
- **Calculated Columns and Measures** ➗: Created custom measures to calculate genre-based revenue, profit margins, and trends.
- **Visualizations** 📊:
  - Bar charts 📊 for Rotten Tomatoes scores by genre.
  - Tree maps 🌳 for worldwide gross revenue by genre.
  - Donut charts 🍩 for the number of movies produced per year.
  - Horizontal bar charts 📈 for profitability by studio.
- **Interactive Features** 🎛️:
  - Slicers for filtering by genre, studio, and year.
  - Drill-through pages for detailed insights.

### 🟠 R: Exploratory Data Analysis and Cleaning  
- **Data Import and Exploration** 🛠️:
  - Loaded and inspected the dataset of Hollywood's most profitable stories.
  - Checked data types and identified missing values for preprocessing.
- **Data Cleaning** 🧹:
  - Removed missing values using `na.omit()` and `drop_na()` for clean analysis.
- **Exploratory Data Analysis** 📊:
  - Summary statistics generated using the `summary()` function.
  - Created scatterplots and bar charts with **ggplot2** to visualise key trends:
    - Scatterplot: Relationship between studios and Rotten Tomatoes scores.
    - Bar chart: Frequency of movies by genre.
- **Exporting Clean Data** 📤:
  - Exported the cleaned dataset as a `.csv` file for further use.

---

## 🌍 Key Dashboard Visuals

### 🟡 Power BI Visuals:
1. **Rotten Tomatoes Scores** 🎥: Bar charts showing the average Rotten Tomatoes scores for each genre.
2. **Audience Scores** 👥: A table displaying audience scores for individual films.
3. **Worldwide Gross Revenue** 🌍: Tree maps highlighting gross revenue by genre.
4. **Movies Produced Per Year** 📅: Donut charts displaying production frequency by year.
5. **Profitability by Studio** 🎞️: Horizontal bar charts ranking studios by profitability.


![Power BI main dashboard ](https://github.com/user-attachments/assets/a363fd71-a30f-4381-b7c5-b8ad029bb7e4)


### 🟠 R Visuals:
1. **Scatterplot and Bar Chart**:

   <img src="https://github.com/user-attachments/assets/6236b40a-3451-405f-aba8-faf3105ebb21" alt="R Scatter Plot Assignment" width="45%">  
   <img src="https://github.com/user-attachments/assets/8d982f35-b69b-430c-bbc0-9c505a809d2a" alt="R Bar Chart Assignment" width="45%">

---

## 📊 Key Findings

1. **Top Genres**: The **Comedy** genre generated the highest worldwide gross revenue, followed by **Romance** and **Drama**.  
2. **Audience Scores**: **Animation** and **Fantasy** genres had the highest average Rotten Tomatoes scores, with **Action** scoring the lowest.  
3. **Profitability Insights**: Independent studios outperformed major studios in terms of profitability, with notable contributions from **Disney** and **Warner Bros.**  
4. **Production Trends**: Movie production peaked in 2011, while 2007 saw the fewest releases in this dataset.

---

## 🚀 How to Explore

1. 🔗 **[Explore the Power BI Dashboard](https://app.powerbi.com/groups/me/reports/d050d496-8fe4-4ac4-9887-155ffd5b233f/996866041e821adc30b4?experience=power-bi)**.  
2. Use filters to:  
   - 🎛️ Drill down by genre, studio, and production year.  
   - 📊 Explore profitability and audience scores by genre.  
3. Analyse detailed insights with drill-through pages.  

---

## 😅 Reflections
This project helped me combine the strengths of **Power BI** and **R** to deliver comprehensive insights. The dashboards effectively visualised trends across genres and studios. One challenge was handling missing data, which persisted in the Excel files even after R cleaning. Using **Power Query** in Power BI resolved this issue, ensuring clean data for analysis. 🚀

---

## 📑 Repository Files
- **🟡 Power BI Dashboard Link**: Interactive Power BI dashboard.  
- **🟠 R Code**: Scripts for cleaning and exploring movie dataset.  
- **📋 Excel Files**:  
  - [Hollywood's Most Profitable Stories Dataset](./HollywoodsMostProfitableStories.csv)  
  - [Cleaned Dataset](./clean_df.csv)  

---

🌐 **Explore movie trends, audience scores, and profitability insights today! 🎉**
