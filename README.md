# 🎥 Netflix Data Visualization Project

Welcome to the **Netflix Data Visualization Project**, where we explore Netflix's global impact, content growth, and subscriber trends using data analytics and interactive dashboards. This project leverages datasets from Kaggle and tools like Python and Tableau to reveal insights into Netflix's strategy and evolution.

---

## 📖 Overview

Netflix has transformed the entertainment industry with its vast library of movies and TV shows. This project aims to answer three key questions:

1. **Geographic Impact**: Which countries offer the most Netflix content, and how does subscription pricing vary globally?
2. **Content Growth Timeline**: How has Netflix’s content library grown over the years?
3. **Popularity Metrics**: How many subscribers does Netflix have, and how are they distributed across regions?

Through data cleaning, analysis, and visualization, this project uncovers insights into Netflix's global strategy.

---

## 🛠️ Technologies Used

- **Python**: Data cleaning, preprocessing, and analysis
- **Pandas & NumPy**: Data manipulation and numerical computations
- **Jupyter Notebooks**: Exploratory data analysis and workflow documentation
- **Tableau**: Creating interactive dashboards and visualizations
- **Git**: Version control and collaboration
---

## 📂 Repository Structure

```bash
├── data/                           # Raw and cleaned datasets
│   ├── raw/                        # Original datasets from Kaggle
│   ├── processed/                  # Processed datasets for visualization
├── notebooks/                      # Jupyter Notebooks for analysis
│   ├── data_cleaning.ipynb         # Data cleaning and preprocessing
│   └── analysis.ipynb              # Exploratory data analysis
├── visualizations/                 # Tableau dashboards and static images
│   ├── Geographical.jpeg           # Geographical impact dashboard image
│   ├── Timeline.jpeg               # Content growth timeline dashboard image
│   └── Popularity.jpeg             # Subscriber metrics dashboard image
├── README.md                       # Project documentation
└── LICENSE                         # License for the repository
```
---

## 📊 Datasets

The following datasets were used in this project:

1. [Netflix Subscription Prices in Different Countries](https://www.kaggle.com/datasets/prasertk/netflix-subscription-price-in-different-countries)
2. [Netflix Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
3. [Netflix Subscribers (2020)](https://www.kaggle.com/datasets/pariaagharabi/netflix2020?select=DataNetflixSubscriber2020_V2.csv)

---

## 🔑 Key Insights

### 1. Geographic Impact - **[CLICK HERE TO INTERACT WITH DASHBOARD](https://public.tableau.com/app/profile/srinivas.barla/viz/Netflix_17352977889580/Geographical2)**  
- The **United States** offers the largest content library, with over 3,211 titles.
- **India** ranks second, showcasing Netflix's focus on South Asia.
- Switzerland has the highest subscription fees, with premium plans costing $26.96/month.
  
![Geographic Impact](Geographical.png "Geographical Summary")

### 2. Content Growth Timeline - **[CLICK HERE TO INTERACT WITH DASHBOARD](https://public.tableau.com/app/profile/srinivas.barla/viz/Netflix_17352977889580/Timeline2)**  
- Netflix’s content library has grown exponentially since 2015, driven by heavy investments in Originals.
- By 2021, Netflix had spent over **$17 billion** on content creation.

![Content Growth Timeline](Timeline.png "Timeline Summary")

### 3. Popularity Metrics - **[CLICK HERE TO INTERACT WITH DASHBOARD](https://public.tableau.com/app/profile/srinivas.barla/viz/Netflix_17352977889580/Popularity2)**  
- Netflix had **370 million subscribers worldwide** by Q2 2022.
- Subscriber growth in regions like **Asia-Pacific** and **Latin America** highlights the platform’s global expansion strategy.

![Popularity Metrics](Popularity.png "Popularity Summary")

---

## 🔄 Data Pipeline

### 1. Data Acquisition

- Downloaded datasets from Kaggle
- Stored raw data in the `data/raw/` directory

### 2. Data Cleaning and Preprocessing

- Utilized Jupyter Notebook (`notebooks/01_data_cleaning.ipynb`) for data cleaning
- Performed the following tasks:
  - Handled missing values
  - Removed duplicates
  - Standardized data formats (e.g., date formats, currency conversions)
  - Merged relevant datasets
- Saved cleaned datasets in the `data/processed/` directory

### 3. Exploratory Data Analysis (EDA)

- Conducted EDA using Jupyter Notebook (`notebooks/02_exploratory_analysis.ipynb`)
- Explored key variables and relationships
- Generated initial insights and hypotheses

### 4. Data Visualization

- Imported cleaned data into Tableau
- Created three main dashboards:
  1. Geographic Impact
  2. Content Growth Timeline
  3. Popularity Metrics
- Designed interactive elements for user exploration

### 5. Insight Generation

- Analyzed visualizations to extract key findings
- Summarized insights for each dashboard (see Key Insights section)

### 6. Deployment and Sharing

- Published Tableau dashboards to Tableau Public
- Created a Medium blog post to share findings
- Updated GitHub repository with all project files and documentation

---

## 📜 Blog Post & Dashoard

Read the detailed project write-up on Medium:  
[**Netflix Data Visualization: Exploring the Global Streaming Leader**](https://medium.com/@srinivasbarla2000/netflix-data-visualization-exploring-the-global-streaming-leader-4c3cd8e5577f)

Explore the interactive dashboards created in Tableau:                                                 **[NETFLIX - ANALYSIS - DASHBOARD](https://public.tableau.com/app/profile/srinivas.barla/viz/Netflix_17352977889580/Geographical2)**  

