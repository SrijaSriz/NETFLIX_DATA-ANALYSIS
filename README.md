# Netflix Content Trends Dashboard

An **interactive Tableau dashboard** that visualizes Netflix's content library trends.  
Data was cleaned and preprocessed using Python before being imported into Tableau for analysis and visualization.

---

## 📊 View the Dashboard
[**Click here to view on Tableau Public**](https://public.tableau.com/views/tableau_Netflix_17549048229050/DASHBOARD)

---

## 📂 Dataset
- **Source:** [Netflix Shows Dataset – Kaggle]
- **Size:** ~8,800 records
- **Fields used:**
  - `type` – Movie or TV Show
  - `rating` – TV-MA, PG, R, etc.
  - `date_added` – Date the title was added
  - `country` – Production country
  - `listed_in` – Genres
  - `director`, `cast`

---

## 🛠 Data Cleaning (Python)
1. Removed null values from critical columns (`type`, `rating`, `date_added`, `country`).
2. Standardized date formats.
3. Split multi-value fields:
   - `cast` → individual actor entries
   - `listed_in` → individual genres
4. Created calculated fields for:
   - Year of addition
   - Genre count
5. Filtered dataset for valid and non-empty records.

---

## 📈 Dashboard Insights
The Tableau dashboard includes:
1. **Top 10 Countries by Content Volume** – Bar chart  
2. **Country Distribution by Type** – Pie chart filterable by year and rating  
3. **Content Count by Rating** – Packed bubble chart  
4. **Yearly Trend of Content Added** – Line chart (2008–2021)  
5. **Show Count by Type** – Bar chart (Movies vs TV Shows)  
6. **Most Frequent Genres** – Horizontal bar chart  
7. **Director with Most Titles** – Horizontal bar chart  
8. **Interactive Filters** – Rating filter, year slider, and type toggle

---

## 🖼 Dashboard Preview
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/24b2de3e-63ea-4450-9258-33c88b0a8937" />


---

## 🚀 Tech Stack
- **Python (Pandas, NumPy)** – Data cleaning & preprocessing
- **Tableau Public** – Visualization & interactive dashboard
- **GitHub** – Portfolio & version control

---

## 📌 Key Features
- Fully interactive filters and tooltips
- Preprocessed dataset ensuring clean, accurate analysis
- Visual storytelling for trend exploration

---

## 📬 Contact
Created by **Srija Mandavilli**  
📧 [srijamandavilli@gmail.com]  
🔗 [http://www.linkedin.com/in/srijarajesh]

---
