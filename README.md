# IBM Data Analyst Capstone Project

## Overview
This capstone project is the final component of the **IBM Data Analyst Professional Certificate**. It involves a comprehensive, end-to-end analysis of the **Stack Overflow Developer Survey** dataset to uncover current technology usage trends, future technology preferences, and global developer demographics — visualised through interactive IBM Cognos Analytics dashboards.

---

## Dashboards

### 1. Current Technology Usage
![Current Technology Usage](dashboard_page1.png)

### 2. Future Technology Trend
![Future Technology Trend](dashboard_page2.png)

### 3. Demographics
![Demographics](dashboard_page3.png)

---

## Key Findings

### Current Technology Usage
- **HTML/CSS, JavaScript, and TypeScript** were the most widely used language combinations, with the top combination used by 291 respondents
- **PostgreSQL** dominated database usage with 994 respondents, followed by Microsoft SQL Server (689) and MySQL (395)
- **Amazon Web Services (AWS)** was the most used cloud platform, followed by Microsoft Azure and Google Cloud
- **Node.js and React** were the most popular web frameworks currently in use

### Future Technology Trends
- **PostgreSQL** remained the most desired database for the next year (1,265 respondents), showing strong continued adoption
- **C# and TypeScript** combinations were the most desired languages to learn next (230 respondents)
- **Python** featured strongly in future language preferences, reflecting its growing importance in data and AI fields
- **AWS and Microsoft Azure** continued to dominate future platform preferences
- **React** was the most desired web framework for the coming year

### Developer Demographics
- **41.3%** of respondents were aged **25–34**, making it the largest age group
- **27.3%** were aged **35–44**, showing a mature and experienced developer community
- **15.9%** were aged **18–24**, representing the emerging generation of developers
- **Bachelor's degree** was the most common education level (8,629 respondents), followed by Master's degree (5,000)
- Respondents spanned globally, with strong representation from the **USA, UK, Germany, Ireland, Brazil, and Switzerland**

---

## Tools & Technologies Used

| Category | Tools |
|---|---|
| Programming | Python |
| Data Wrangling | Pandas, NumPy |
| Visualisation | Matplotlib, Seaborn |
| BI & Dashboards | IBM Cognos Analytics |
| Notebook Environment | Jupyter Notebook |
| Data Format | CSV, JSON |

---

## Dashboard Highlights

| Dashboard | Charts Used |
|---|---|
| Current Technology Usage | Horizontal bar charts, bubble charts |
| Future Technology Trends | Bar charts, treemaps, bubble charts |
| Demographics | Pie chart, choropleth world map, line chart, stacked bar chart |

---

## Project Structure
```
ibm-data-analyst-capstone/
│
├── data/                        # Raw and cleaned datasets
├── notebooks/                   # Jupyter notebooks for each phase
│   ├── 01_data_collection.ipynb
│   ├── 02_data_wrangling.ipynb
│   ├── 03_exploratory_analysis.ipynb
│   └── 04_visualisation.ipynb
├── dashboard/                   # IBM Cognos Analytics dashboard screenshots
│   ├── dashboard_page1.png      # Current Technology Usage
│   ├── dashboard_page2.png      # Future Technology Trends
│   └── dashboard_page3.png      # Demographics
└── README.md
```

---

## How to Run
1. Clone this repository
   ```bash
   git clone https://github.com/your-username/ibm-data-analyst-capstone.git
   ```
2. Install required libraries
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Open Jupyter Notebook
   ```bash
   jupyter notebook
   ```
4. Run notebooks in order starting from `01_data_collection.ipynb`

---

## Certificate
Completed as part of the [IBM Data Analyst Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-analyst) on Coursera — an 11-course specialisation covering data analysis, Python, SQL, Excel, and IBM Cognos Analytics.

---

## Author
**Kshitiz Saxena**
- LinkedIn: [linkedin.com/in/kshitizsaxena08](https://linkedin.com/in/kshitizsaxena08)
- Email: ksaxena491@gmail.com
