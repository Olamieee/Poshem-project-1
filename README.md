# POSHEM BUSINESS SCHOOL SALES ANALYSIS PROJECT

## 📊 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of Poshem Business School's sales dataset, conducted as part of the **Poshem Technologies Institute Python Data Challenge**. The analysis examines 4 years of sales data (2015-2018) to derive actionable business insights.

<!-- **Submitted By**: Alonge Olamide 
**Date**: February 2026  
**Course**: Poshem Technologies Institute -  Data Science Challenge  
**Project Supervisor**: Simon E. Akhamie, CEO -->

---

## 📁 Project Structure

```
Poshem_Sales_Project/
├── poshem_business_school_sales.ipynb    # Main analysis notebook
├── poshem_business_school_sales.csv      # Dataset
├── Poshem_Sales_Analysis_Report.pdf      # Complete analysis report
├── README.md                              # README
└── charts/                           # Visualization charts
    ├── Averagen order value.png
    ├── customer_segmentation_distribution.png
    ├── region_distributon.png
    ├── shipping_mode_patterns_by_region.png
    ├── top_cities.png
    ├── top_products.png
```

---

## 🎯 Project Objectives

1. Conduct comprehensive EDA on sales data
2. Identify patterns and trends in customer behavior
3. Analyze geographical distribution and market penetration
4. Evaluate product category performance
5. Assess shipping operations efficiency
6. Provide data-driven recommendations for strategic decisions

---

## 📊 Dataset Information

**Source**: Poshem Business School Sales Records  
**Period**: January 2015 - December 2018  
**Records**: 9,800 transactions  
**Columns**: 18 data fields  

### Data Fields:
- **Order Information**: Order ID, Order Date, Ship Date, Ship Mode
- **Customer Data**: Customer ID, Customer Name, Segment
- **Geographic**: Country, City, State, Postal Code, Region
- **Product Details**: Product ID, Category, Sub-Category, Product Name
- **Financial**: Sales

---

## 🔍 Key Findings

### Market Performance
- **Total Revenue**: $2.3 million over 4 years
- **Customer Base**: 793 unique customers
- **Order Volume**: 5,009 unique orders
- **Average Order Value**: $230.77

### Geographic Insights
- **Top Regions**: West (32%) and East (28.5%) dominate
- **Growth Opportunity**: South region only 16.2% of orders
- **Urban Concentration**: Top 5 cities drive disproportionate volume

### Customer Segmentation
- **Consumer Segment**: 52% of orders (volume leader)
- **Corporate Segment**: Highest average order value ($234)
- **Home Office**: 18% of business (growth opportunity)

### Product Performance
- **Technology**: $836K revenue (36.4%)
- **Furniture**: $742K revenue (32.3%)
- **Office Supplies**: $719K revenue (31.3%)

### Data Quality Issues Identified & Resolved
- Fixed 11 missing postal codes (Burlington, Vermont = 05401)
- Zero duplicate records
- **Profit data unavailable** (limitation for profitability analysis)

---

## 🛠️ Technologies Used

### Programming Language
- **Python 3.10+**

### Core Libraries
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computations
- `matplotlib` - Data visualization
- `seaborn` - Statistical graphics

### Development Environment
- **Jupyter Notebook** - Interactive analysis and documentation

---

## 🚀 How to Run This Project

### Prerequisites

1. **Python Installation** (3.8 or higher)
   ```bash
   python --version
   ```

2. **Required Libraries**
   ```bash
   pip install pandas numpy matplotlib seaborn scipy jupyter
   ```

### Step-by-Step Instructions

1. **Clone/Download Project**
   - Download the project folder
   - Ensure all files are in the same directory

2. **Launch Jupyter Notebook**
   ```bash
   cd path/to/project
   jupyter notebook
   ```

3. **Open the Notebook**
   - In Jupyter interface, click `poshem_business_school_sales.ipynb`

4. **Run the Analysis**
   - Option A: Run all cells at once
     - Menu: `Cell` → `Run All`
   - Option B: Run cells individually
     - Click each cell and press `Shift + Enter`

5. **View Results**
   - All visualizations will display inline
   - Statistical outputs appear below code cells

### Troubleshooting

**Issue**: "File not found" error  
**Solution**: Ensure `poshem_business_school_sales.csv` is in the same directory as the notebook

**Issue**: Import errors  
**Solution**: Install missing libraries using `pip install [library-name]`

**Issue**: Plots not displaying  
**Solution**: Add `%matplotlib inline` at the top of notebook

---

## 📈 Analysis Sections

The notebook is organized into the following sections:

### 1. Overview
- Dataset timeframe
- Data structure (rows/columns)
- Missing values identification and correction
- Data types validation
- Duplicate detection
- Statistical summary

### 2. Order Statistics
- Unique orders count
- Order status distribution (Note: column not available in dataset)
- Customer count and retention metrics

### 3. Geographical Insights
- Country analysis
- Regional distribution
- Top 5 cities by order volume

### 4. Product Analysis
- Product categories overview
- Sales by category
- Top 5 selling products

### 5. Customer Segmentation
- Segment distribution
- Average order value by segment
- Customer behavior patterns

### 6. Shipping Operations
- Shipping modes analysis
- Delivery time analysis
- Regional shipping patterns

### 7. Sales Distribution
- Overall sales distribution
- Outlier detection (IQR method)
- Sales distribution by category

### 8. Profit Analysis
- **Note**: Profit data not available in dataset
- Alternative sales-based analysis provided
- Recommendations for future data collection

---

## 📊 Visualizations Created

The analysis includes 10+ professional visualizations:

1. **Regional Distribution** - Bar chart showing order volume by region
2. **Top Cities** - Horizontal bar chart of top 5 cities
3. **Product Categories** - Bar chart of sales by category
4. **Top Products** - Top 5 products by revenue
5. **Customer Segmentation** - Pie chart of segment distribution
6. **Average Order Value** - Bar chart by customer segment
7. **Shipping Modes** - Distribution of shipping options
8. **Shipping Time** - Box plot of delivery times
9. **Regional Shipping** - Grouped bar chart of shipping patterns
10. **Sales Distribution** - Violin plot by product category

All charts use professional color schemes and follow data visualization best practices.

---

## 💡 Key Recommendations

Based on the analysis, the following strategic recommendations are proposed:

### Priority 1: Regional Expansion
- Focus marketing on underperforming Central and South regions
- Establish distribution partnerships in low-penetration areas
- Target 15-20% growth in underserved regions

### Priority 2: Customer Segment Strategies
- **Corporate**: Dedicated account management program
- **Consumer**: Implement loyalty/rewards program
- **Home Office**: Specialized marketing and product curation

### Priority 3: Operational Efficiency
- Reduce Standard Class shipping from 5 days to 3.5 days
- Promote premium shipping options
- Establish regional distribution centers

### Priority 4: Data Infrastructure
- **Critical**: Implement profit/cost tracking
- Add order status field
- Automate data validation

### Priority 5: Revenue Growth
- Reactivate dormant customers
- Cross-selling initiatives
- Geographic expansion programs

---

## 📝 Report Deliverables

### Included in Submission:

1. ✅ **Jupyter Notebook** - Complete analysis with code and visualizations
2. ✅ **PDF Report** - Professional 30-page analysis report including:
   - Executive summary
   - Detailed findings
   - Data quality assessment (missing values challenge)
   - 10+ charts and visualizations
   - Strategic recommendations
3. ✅ **Dataset** - Original CSV file
4. ✅ **Charts** - High-resolution charts (8 PNG files)
5. ✅ **README** - This comprehensive documentation

---

## 🎓 Learning Outcomes

Through this project, I demonstrated proficiency in:

### Technical Skills
- ✅ Data cleaning and preprocessing
- ✅ Exploratory data analysis techniques
- ✅ Statistical analysis and interpretation
- ✅ Data visualization (Matplotlib, Seaborn)
- ✅ Python programming for data science
- ✅ Jupyter Notebook documentation

### Business Skills
- ✅ Translating data insights into business recommendations
- ✅ Identifying market opportunities and challenges
- ✅ Strategic thinking and problem-solving
- ✅ Professional report writing
- ✅ Stakeholder communication

### Tools Mastered
- Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook
- Data visualization best practices
- Statistical analysis methods

---

## 🔄 Future Enhancements

Potential extensions to this analysis:

1. **Time Series Analysis** - Identify seasonal trends and patterns
2. **Predictive Modeling** - Forecast future sales
3. **Customer Lifetime Value** - Calculate CLV by segment
4. **Market Basket Analysis** - Identify product associations
5. **Geospatial Visualization** - Interactive maps of sales distribution

---

## 📞 Contact Information

**Email**: alongeola16@gmail.com
**LinkedIn**: https://linkedin.com/in/alonge-olamide/49323742
**GitHub**: https://github.com/Olamieee

**Institution**: Poshem Technologies Institute  
**Course**: Python Data Challenge  
**Project Supervisor**: Simon E. Akhamie, CEO
---

## 📄 License

This project was completed as part of the Poshem Technologies Institute curriculum.  
Dataset provided by Poshem Business School.  

---

## 🏆 Acknowledgments

- **Poshem Technologies Institute** for providing this learning opportunity
- **Poshem Business School** for providing the dataset

---

*For questions or feedback about this analysis, please contact via the information provided above.*
