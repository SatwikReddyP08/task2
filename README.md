# HR Data Visualization and Storytelling (Task 2)

## Objective
The goal of this project was to create clear, insightful visualizations from HR data to support effective storytelling using **Power BI**.

---

## Dataset Used
A simple HR dataset containing 183 entries with the following columns:
- Name
- Gender
- Age
- Rating
- Date Joined
- Department
- Salary
- Country

---

## Tools Used
- **Power BI Desktop** for data cleaning, transformation, and visualization
- **Python (Pandas)** for preprocessing and formatting before importing

---

## Visualizations Created

1. **Department-wise Headcount**  
   - *Type:* Stacked Column Chart  
   - *Insight:* Shows how many employees work in each department.

2. **Gender Distribution by Department**  
   - *Type:* Clustered Column + 100% Stacked Column (side-by-side)  
   - *Insight:* Compares male vs. female distribution within each department.

3. **Age Spread of Staff**  
   - *Type:* Age Binning with Stacked Columns  
   - *Insight:* Shows both exact age distribution and grouped age bins, with highlights for largest groups.

4. **Salary Stats by Department**  
   - *Type:* Table with Country Slicer  
   - *Insight:* Displays min, max, and average salary per department, filterable by country.

5. **Top Earners by Country**  
   - *Type:* Tables for each country  
   - *Insight:* Identifies top-paid employees from each country.

6. **Company Growth Trend**  
   - *Type:* Line Chart  
   - *Insight:* Visualizes hiring trends over time using 'Date Joined'.

---

## File Structure
- `cleaned_hr_dataset.csv` – Cleaned dataset used for Power BI import
- `hr_visualizations.pbix` – Power BI project file with all charts
- `README.md` – This file
- *(Optional)* `/screenshots/` – Folder containing screenshots of key charts for preview

---

## Suggestions for Usage
- You can **open the `.pbix` file** in Power BI Desktop to explore the interactive dashboards.
- Screenshots are optional, but they’re helpful for **previewing visuals directly on GitHub**, especially for reviewers who don’t open `.pbix` files.
- Add a short **caption under each screenshot** if you include them.

---

## How to Run
1. Clone this repository.
2. Open `hr_visualizations.pbix` using Power BI Desktop.
3. Explore or modify the visuals using Power BI’s interactive features.

---

## Author
Satwik Reddy Pathapati
