# 📺 Viewership Analysis Project

## 📌 Summary of the Case Study
This case study analyzes **video viewership data** stored in an Excel file. The project focused on importing data into Python, cleaning and exploring the dataset, and preparing it for further analysis. The goal was to transform raw viewership logs into **actionable insights** about customer behavior, platform usage, and video consumption trends.

---

## 🔍 How the Case Study Was Done
1. **Environment Setup**
   - Installed required dependencies (`openpyxl`) to ensure Excel file compatibility.
   - Restarted the Python kernel after installation to apply updates.

2. **Library Imports**
   - Imported essential Python libraries:
     - `pandas` → For data manipulation and analysis.
     - `numpy` → For numerical operations.
     - `openpyxl` → For reading `.xlsx` files.

3. **Data Loading**
   - Defined the file path:  
     `/Workspace/Users/khozabonginkosi6@gmail.com/Viewership Analysis .xlsx`
   - Loaded the dataset into a Pandas DataFrame using `pd.read_excel()`.
   - Displayed the dataset for initial exploration.

4. **Dataset Exploration**
   - Columns included:  
     - `DateID` → Date of the event (YYYYMMDD format).  
     - `CustomerID` → Unique identifier for the customer.  
     - `TotalTimeWatched` → Total viewing time in seconds.  
     - `Platform` → Platform used (e.g., Leanback, Mobile).  
     - `PlayEventType` → Type of event (e.g., LiveTV, Other).  
     - `VideoTitle` → Title of the video watched.  
   - Sample records were reviewed to understand structure and data quality.

---

## 📊 Insights Found
- **Viewing time distribution** showed differences across customers and platforms.  
- **Platform usage trends** revealed Leanback as a dominant platform in the sample data.  
- **Event type analysis** highlighted LiveTV as a major driver of engagement.  
- **Video title exploration** provided insights into popular content (e.g., sports, movies, documentaries).  

---

## 🎯 Summary of Findings
By loading and exploring the dataset, the project uncovered:  
- How customers interact with different platforms.  
- Which event types drive the most engagement.  
- Early indicators of **content popularity** and **viewership behavior**.  

This demonstrates how Python and Pandas can be used to transform raw Excel logs into **business intelligence** that supports **content strategy, platform optimization, and customer engagement analysis**.

---

## 🛠️ Tools Used
- **Python** → Programming environment.  
- **pandas** → Data manipulation and analysis.  
- **numpy** → Numerical operations.  
- **openpyxl** → Excel file support for `.xlsx` format.  
- **Excel** → Original data source. 
