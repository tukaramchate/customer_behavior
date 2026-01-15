# 👨🏻‍💻 Customer Shopping Behavior Analysis - Complete Data Analytics Portfolio

A comprehensive end-to-end data analytics project demonstrating professional analysis of customer shopping patterns using Python, SQL, and Power BI. This project showcases the complete workflow from business problem identification to stakeholder presentation.

## 🎯 Who Is This For?

- 📊 **Data Analyst Aspirants** - Build a strong portfolio project for interviews and LinkedIn
- 📚 **Students & Learners** - Practice Python, SQL, and Power BI in a real-world context
- 💼 **Career Switchers** - Demonstrate data analytics skills for Data Analytics, Data Science, or Product Analytics roles
- 🔍 **Business Professionals** - Understand how data drives customer behavior insights

---

## 📌 Project Overview

This project simulates a corporate-grade data analytics workflow, translating raw customer data into actionable business intelligence through seven key stages:

### **01** | Business Problem Statement
Define analytical objectives and key business questions around customer shopping behavior, revenue drivers, and loyalty patterns.

### **02** | Data Modeling & EDA in Python
- Import and explore customer shopping dataset
- Clean data and handle missing values with intelligent imputation
- Feature engineering (age groups, purchase frequency metrics)
- Statistical analysis and data profiling

### **03** | Data Analysis in SQL
- Load cleaned data into SQL database (MySQL/PostgreSQL/MS SQL Server)
- Execute 10+ complex analytical queries
- Extract insights on customer segments, loyalty, and purchase drivers
- Analyze revenue patterns and subscription behavior

### **04** | Interactive Dashboard using Power BI
- Connect SQL database to Power BI
- Build interactive visualizations highlighting key patterns and trends
- Enable stakeholders to explore data through dynamic filters
- Present insights through professional dashboard design

### **05** | Project Report
- Summarize key findings and data-driven insights
- Document methodology and analytical approach
- Present business recommendations based on analysis

### **06** | Presentation using Gamma AI
- Create professional presentation deck
- Visually communicate insights to stakeholders
- Prepare for business presentation scenarios

### **07** | GitHub Repository
- Upload complete project files with documentation
- Showcase work in professional portfolio
- Enable reproducibility and collaboration

![Project Workflow](https://github.com/user-attachments/assets/8bbd5dc9-eb6c-40c1-8f19-c08b4107f654)

## 🛠️ Technologies & Tools

- **Python 3.x** - Data manipulation and analysis
  - pandas - Data cleaning and transformation
  - NumPy - Numerical computing
- **SQL** - Advanced querying (PostgreSQL/MySQL/MS SQL Server)
- **Power BI** - Interactive dashboard and visualization
- **Jupyter Notebook** - Interactive development environment
- **Gamma AI** - Presentation creation
- **Git/GitHub** - Version control and portfolio hosting

---

## 📁 Project Structure

```
Customer-Behavior/
│
├── customer_shopping_behavior.csv              # Raw dataset
├── Customer_Shopping_Behavior_Analysis.ipynb   # Python analysis notebook
├── customer_behavior_sql_queries.sql           # SQL business queries
├── README.md                                   # Project documentation
└── LICENSE.txt                                 # MIT License
```

---

## 🚀 How to Use This Project

### Step 1️⃣: Clone the Repository
```bash
[git clone <repository-url>](https://github.com/tukaramchate/customer_behavior)
cd Customer-Behavior
```

### Step 2️⃣: Python Analysis - Data Modeling & EDA

**Prerequisites:**
```bash
pip install pandas numpy jupyter
```

**Run the Analysis:**
1. Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook
2. Execute cells sequentially to:
   - Import customer shopping data from CSV
   - Explore dataset structure and statistics
   - Clean data (handle missing values with category-based median imputation)
   - Rename columns for consistency (snake_case)
   - Engineer new features:
     - `age_group`: Segment customers into Young Adult, Adult, Middle-aged, Senior
     - `purchase_frequency_days`: Calculate purchase patterns
   - Prepare data for SQL export

### Step 3️⃣: SQL Analysis - Business Insights

1. **Set up SQL Database:**
   - Create a new database in MySQL/PostgreSQL/MS SQL Server
   - Load cleaned data from Python notebook into SQL database

2. **Execute Business Queries:**
   - Open `customer_behavior_sql_queries.sql`
   - Run 10 analytical queries to answer:
     - ✅ Total revenue by gender
     - ✅ Smart shoppers (discount users with high spending)
     - ✅ Top 5 products by review rating
     - ✅ Shipping type impact on purchase amount
     - ✅ Subscriber vs non-subscriber spending patterns
     - ✅ Products with highest discount rates
     - ✅ Customer segmentation (New/Returning/Loyal)
     - ✅ Top 3 products per category
     - ✅ Repeat buyer subscription likelihood
     - ✅ Revenue by age group

### Step 4️⃣: Power BI Dashboard (Optional)

1. Connect SQL database to Power BI Desktop
2. Import customer behavior tables
3. Create interactive visualizations:
   - Revenue trends and comparisons
   - Customer segmentation charts
   - Product performance metrics
   - Demographic analysis
4. Design dashboard for stakeholder presentation

### Step 5️⃣: Document Findings

- Create project report summarizing key insights
- Develop presentation using Gamma AI or PowerPoint
- Prepare to present data-driven recommendations

### Step 6️⃣: Publish to GitHub

- Upload all project files
- Update README with your analysis insights
- Add to your portfolio and LinkedIn

---

## 📊 Key Business Questions Answered

This project answers 10 critical business questions:

1. **Revenue Analysis** - What is the total revenue generated by male vs. female customers?
2. **Smart Shoppers** - Which customers used discounts but still spent above average?
3. **Product Excellence** - Which are the top 5 products with highest review ratings?
4. **Shipping Impact** - How do Standard vs. Express shipping affect purchase amounts?
5. **Subscription Value** - Do subscribed customers spend more?
6. **Discount Strategy** - Which products have the highest discount application rates?
7. **Customer Loyalty** - How are customers distributed across New/Returning/Loyal segments?
8. **Category Leaders** - What are the top 3 most purchased products per category?
9. **Loyalty Drivers** - Are repeat buyers more likely to subscribe?
10. **Demographic Trends** - What is the revenue contribution of each age group?

---

## 🎓 Skills Demonstrated

### Technical Skills
- ✅ Data cleaning and preprocessing
- ✅ Feature engineering
- ✅ Statistical analysis
- ✅ SQL querying (aggregations, window functions, CTEs)
- ✅ Python programming (pandas, data manipulation)
- ✅ Data visualization (Power BI)
- ✅ Database management

### Business Skills
- ✅ Problem formulation and requirements gathering
- ✅ Customer segmentation strategies
- ✅ Revenue and profitability analysis
- ✅ KPI identification and tracking
- ✅ Data storytelling and presentation
- ✅ Stakeholder communication

### Professional Competencies
- ✅ End-to-end project execution
- ✅ Documentation and reproducibility
- ✅ Portfolio development
- ✅ Version control (Git/GitHub)

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Fork this repository
- Enhance analysis with additional insights
- Improve visualizations
- Add new business questions
- Submit pull requests

---


## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE.txt](LICENSE.txt) file for complete details.

**You are free to:**
- ✅ Use this project for learning and portfolio purposes
- ✅ Modify and adapt the code for your needs
- ✅ Share and distribute with attribution
- ✅ Use in commercial or non-commercial projects

---

## 💡 Show Your Support

If you found this project helpful:
- ⭐ **Star this repository** on GitHub
- 🔀 **Fork it** to create your own version
- 📤 **Share it** with others learning data analytics
- 💬 **Contribute** improvements or additional analyses

---

## 📧 Contact & Feedback

For questions, suggestions, or collaboration:
- Open an issue in this repository
- Connect on LinkedIn (add your profile)
- Share your portfolio projects!

---

**Happy Analyzing! 📊✨**

*Project Last Updated: January 2026*
