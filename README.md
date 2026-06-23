# Job-Market-Analysis
# 📊 Job Market Analysis Dashboard

A comprehensive Power BI dashboard project that analyzes job market trends, company hiring patterns, salary distributions, and location insights using LinkedIn job postings data.

---

## 📁 Project Structure

```
Job-Market-Analysis-Dashboard/
│
├── Job_Market_Analysis_Dashboard.pbix   # Main Power BI report file
├── postings.csv                         # Raw job postings dataset
│
├── screenshots/
│   ├── Company_Analysis_Dashboard.png
│   ├── Executive_Analysis_Dashboard.png
│   ├── Job_Market_Insights_Dashboard.png
│   ├── Location_Analysis_Dashboard.png
│   └── Salary_Analysis_Dashboard.png
│
└── README.md
```

---

## 🖼️ Dashboard Screenshots

### Executive Analysis Dashboard
![Executive Analysis Dashboard](screenshots/Executive_Analysis_Dashboard.png)

### Company Analysis Dashboard
![Company Analysis Dashboard](screenshots/Company_Analysis_Dashboard.png)

### Job Market Insights Dashboard
![Job Market Insights Dashboard](screenshots/Job_Market_Insights_Dashboard.png)

### Location Analysis Dashboard
![Location Analysis Dashboard](screenshots/Location_Analysis_Dashboard.png)

### Salary Analysis Dashboard
![Salary Analysis Dashboard](screenshots/Salary_Analysis_Dashboard.png)

---

## 🗂️ Dashboard Pages

### 1. 🏢 Executive Analysis Dashboard
High-level overview for executives and decision-makers.

- **94K** Total Jobs
- **15K** Total Companies
- **217.84K** Currency (Average Salary)
- **177K** Total Applications
- **1M** Total Views
- **10K** Remote Jobs
- Top Hiring Companies, Experience Level distribution, Work Type breakdown, Salary Chart by Pay Period, and Location map

### 2. 🏣 Company Analysis Dashboard
Detailed breakdown of company-level hiring activity.

- Top 10 Hiring Companies
- Top 10 Most Applied Companies
- Top 10 Most Viewed Companies
- Average Salary by Company
- Filters: Company Name, Experience Level, Work Type

### 3. 💼 Job Market Insights Dashboard
Insights into job titles, roles, and market dynamics.

- Top 10 Job Titles by count
- Top 10 Most Applied Job Titles
- Top 10 Most Viewed Job Titles
- Work Type Distribution (Full-time, Contract, Part-time, etc.)
- Experience Level Distribution
- Filters: Company, Experience, Work Type, Location

### 4. 📍 Location Analysis Dashboard
Geographic analysis of job availability and salaries.

- **10K** Remote Jobs | **84K** Onsite Jobs
- Interactive location map
- Top 10 Hiring Locations
- Top 10 Most Viewed Locations
- Remote vs Onsite Jobs breakdown
- Top 10 Highest Paying Locations

### 5. 💰 Salary Analysis Dashboard
In-depth salary analysis across dimensions.

- **Average Salary:** 217.84K
- **Maximum Salary:** 1.22M
- **Minimum Salary:** 1.00
- **Median Salary:** 110.06M
- Salary by Experience Level
- Salary by Work Type
- Salary by Pay Period (Biweekly, Hourly, Yearly, Weekly, Monthly)
- Top 10 Highest Paying Locations

---

## 📊 Key Metrics Summary

| Metric | Value |
|---|---|
| Total Jobs | 94K |
| Total Companies | 15K |
| Total Applications | 177K |
| Total Views | 1M |
| Remote Jobs | 10K |
| Onsite Jobs | 84K |
| Average Salary | $217.84K |
| Maximum Salary | $1.22M |

---

## 🔍 Key Insights

- **Mid-Senior level** roles dominate the market with 41K postings, followed by **Entry level** at 37K
- **Full-time** is the most common work type (80.37%), followed by **Contract** (8.9%)
- **Data Analyst** is the most applied and most viewed job title
- **Sales Manager** is the most listed job title with 640 postings
- **United States** leads in hiring locations with 5.3K postings; **New York, NY** follows with 2.1K
- **Westwood, CA** is the highest paying location with an average salary of $0.26B
- **Biweekly** is the most common pay period
- Top hiring companies include **J. Galt (604)**, **Ingersoll (513)**, and **TEKsystems (510)**

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard creation and data visualization
- **Power Query** — Data transformation and cleaning
- **DAX** — Calculated measures and KPIs
- **CSV (postings.csv)** — Source data

---

## 📥 Download Dataset & Report

The `.pbix` and `.csv` files are too large for direct GitHub upload. Download them via Google Drive:

| File | Link |
|---|---|
| `postings.csv` + `Job_Market_Analysis_Dashboard.pbix` | [📂 Download from Google Drive](https://drive.google.com/file/d/1wc1b_ZE5GIB7PQio9yUXxZHUfslGG9S2/view?usp=drive_link) |

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Job_Market_Analysis_Dashboard.pbix` in **Power BI Desktop**
3. If prompted, re-link the data source to `postings.csv` via **Transform Data > Data Source Settings**
4. Explore each dashboard tab using the interactive slicers and filters

> **Note:** Power BI Desktop is required to open the `.pbix` file. Download it free from [Microsoft](https://powerbi.microsoft.com/desktop/).

---

## ⚠️ Uploading to GitHub

GitHub has a **file size limit of 25MB** for regular uploads via the web interface, and **100MB** via Git (with files over 50MB requiring Git LFS).

### If your `.pbix` or `.csv` files are large, follow these steps:

**Option 1: Use Git LFS (Large File Storage)**
```bash
# Install Git LFS
git lfs install

# Track large file types
git lfs track "*.pbix"
git lfs track "*.csv"

# Add .gitattributes and commit
git add .gitattributes
git add .
git commit -m "Add dashboard files with LFS"
git push origin main
```

**Option 2: Use GitHub Desktop**
Download [GitHub Desktop](https://desktop.github.com/), add the repository, and push — it handles large files more gracefully than the web uploader.

**Option 3: Share via Google Drive / OneDrive**
Upload the `.pbix` and `.csv` to cloud storage and add the shareable link in this README under a **Download** section.

**Option 4: Compress the files**
```bash
zip dashboard_files.zip Job_Market_Analysis_Dashboard.pbix postings.csv
```
Then upload the `.zip` if it falls within the size limit.

---

## 👤 Author

**Thippavathi Hemanth Kumar**

🔗 GitHub: [https://github.com/hemanthmikkie/Mikkie](https://github.com/hemanthmikkie/Mikkie)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
