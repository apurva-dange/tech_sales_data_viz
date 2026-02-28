# Mobile and Laptop Sales Data Analysis & Dashboard (Tech-Product-Sales-Analysis)
**Course:** IFT 533: Data Visualization and Reporting for IT  

## 📌 Project Overview
This project focuses on the analysis and visualization of a simulated dataset containing **50,000 sales records** for mobile phones and laptops. The goal was to create an interactive dashboard that aids stakeholders such as Sales Managers, Marketing Teams, and Inventory Specialists in making data-driven decisions regarding revenue, stock movement, and customer preferences.

## 👥 Team Members
* **Apurva Dange**
* **Nidhi Thribhuvan Devadas**
* **Trinadh Chowdary Rayapudi**

---

## 🎨 Design Process (Mural Board)

The project planning and design workflow was visualized across three distinct stages on our Mural board.

### **Stage 1: Dataset Selection & Schema Definition**
We evaluated multiple datasets (including Global Superstore and Suicide Rates) before selecting the **"Mobiles & Laptop Sales Data"** for its relevance to business intelligence and forecasting. We created a comprehensive data dictionary to define key attributes like `Brand`, `Price`, `RAM`, and `SSD`.

<p align="center">
  <img 
    src="https://github.com/AppyDange/data_visualization/blob/main/page1.png?raw=true" 
    alt="Dataset Selection and Schema" 
    width="70%"
  />
</p>

### **Stage 2: User Analysis & Preprocessing**
This phase connected raw data to business needs. We identified key **Target Users** (e.g., Sales Managers, Marketing Teams) and mapped them to specific use cases. We also defined the **Core Questions** the dashboard needed to answer (e.g., "Which product type sells the most in each region?") and outlined necessary **Preprocessing** steps, such as standardizing brand names.

<p align="center">
  <img 
    src="https://github.com/AppyDange/data_visualization/blob/main/page2.png?raw=true" 
    alt="User Analysis and Questions" 
    width="70%"
  />
</p>

### **Stage 3: Dashboard Architecture & Design**
The final planning stage focused on technical specifications. We created a mapping matrix linking business questions to:
* **Chart Types:** Vertical Bars, Sunburst Charts, Treemaps.
* **Pre-attentive Attributes:** Using color intensity for revenue and size for quantity.
* **Interactivity:** Defining filters for Year, Region, and Product Category.

<p align="center">
  <img 
    src="https://github.com/AppyDange/data_visualization/blob/main/page3.png?raw=true" 
    alt="Dashboard Components and Architecture" 
    width="70%"
  />
</p>

---

## 📊 Final Dashboard Features

The final Tableau dashboard provides a comprehensive view of sales performance. Key visualizations include:

1.  **Year-Wise Sales (Donut Chart):** Visualizes the proportion of sales contributed by each quarter and year.
2.  **Brand Revenue (Treemap & Bar Chart):** Ranks brands by total revenue and quantity sold, highlighting top performers like Google and Apple.
3.  **Regionwise Delivery Time:** Compares logistics efficiency across brands and regions.
4.  **Product Specs Analysis:**
    * **SSD Sales:** Breakdown of sales by storage capacity (2TB, 512GB).
    * **RAM/ROM Combo:** A dot plot identifying the most popular memory configurations.
    * **Price Range:** A box plot analysis of pricing distributions and outliers.

## Data Dashboard Snapshot

<p align="center">
  <img src="https://github.com/apurva-dange/tech_sales_data_viz/blob/main/dataviz.gif" 
       alt="Interactive Demo GIF" width="80%" />
</p>

## 🛠️ Tools Used
* **Tableau:** For final dashboard creation and visualization.
* **Python (Pandas):** For data cleaning and preprocessing (dropping irrelevant columns like text-based specifications).
* **Mural:** For project planning, brainstorming, and wireframing.

## 🧠 Key Skills & Competencies

### 📈 Analytical Skills
- Exploratory Data Analysis (EDA)
- KPI tracking & performance monitoring
- Sales trend analysis & year-over-year comparisons
- Outlier detection & statistical summarization
- Data cleaning & transformation (ETL)
- Cohort analysis & customer segmentation

### 📊 Business Intelligence
- Interactive dashboard design & layout
- Stakeholder reporting & data storytelling
- Cross-functional data communication (Sales, Marketing, Inventory)
- Translating business questions into visual insights
- Requirement gathering & user-centered design

### 🛠️ Technical
- Python (Pandas, NumPy) - data wrangling, null handling, feature engineering
- Tableau - calculated fields, dynamic filters, parameters, LOD expressions, Tableau Public publishing
- Data aggregation & pipeline preprocessing
- Chart selection & pre-attentive attribute design (color, size, position)
- Large-scale dataset handling (50,000+ records)

## 🔗 Links
* **Tableau Dashboard:** [View on Tableau Public](https://public.tableau.com/views/Mobile_phone_new/Final_Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
* **Dataset:** [Kaggle - Mobile and Laptop Sales Data](https://www.kaggle.com/datasets/vinothkannaece/mobiles-and-laptop-sales-data/data)
* **Mural Board:** [View Board](https://app.mural.co/t/5334959/m/5334959/1744919538305/b953c3acfa8f3e0b392319e85916feb16946f1a6?sender=u2af3f1a1d51ba46c04ad1251)
