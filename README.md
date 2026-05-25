# 🌾 Agriculture Data Analysis Dashboard

## 🔗 Live Dashboard Link :  (https://app.powerbi.com/groups/me/reports/ebc47073-39bd-4dde-9b21-d7dfe128b79f/e1d6e3de03ca15344b42?experience=power-bi)

---

# 📌 Project Overview

The Agriculture Data Analysis project focuses on analyzing agricultural production data to uncover valuable insights related to crop production, environmental conditions, irrigation methods, rainfall patterns, soil conditions, yield performance, and seasonal agricultural trends.

This project was developed using a modern cloud-based data analytics pipeline integrating **AWS S3**, **Snowflake**, **SQL**, and **Power BI** to create an interactive business intelligence dashboard for agricultural data reporting and decision-making.

---

# 📌 Project Objective

The main objective of this project is to:

* Analyze Rainfall Analysis By Year / Season / Crops / Location 
* Analyze Temperature Analysis By Year / Season / Crops / Location 
* Analyze Humidity Analysis By Year / Season / Crops / Location 
* Analyze Average Rainfall Analysis By Year / Season / Crops / Location 
* Build an interactive Power BI dashboard
* Generate actionable agricultural insights
* Demonstrate cloud-based analytics workflow using AWS S3 and Snowflake
* Improve reporting efficiency using SQL-based transformation processes

---

# 🛠 Tools & Technologies

* ☁️ **AWS S3** – Used for storing raw agricultural datasets.
* ❄️ **Snowflake** – Used as the cloud data warehouse for storing and managing transformed data.
* 🗄 **SQL** – Used in Snowflake for data cleaning, transformation, and querying.
* 📊 **Power BI Desktop** – Main data visualization platform used for dashboard development.

---

# 📂 Dataset Information

## 📌 Dataset Source

* Raw Data Stored in AWS S3
* Data Processed and Transformed in Snowflake
* Final Reporting Performed in Power BI

## 📌 Dataset Overview

The dataset contains agricultural production and environmental information including:

1. Crop Details
2. Climate Information
3. Soil & Irrigation Data
4. Seasonal Agricultural Data
5. Yield & Production Information
6. Location-wise Farming Data

## 📌 Dataset Columns

The dataset includes the following fields:

* Year
* Location
* Area
* Rainfall
* Temperature
* Soil Type
* Irrigation
* Yields
* Humidity
* Crops
* Price
* Season
* YEAR_Group 
* Rainfall_Groups

---

# 📈 Dashboard Highlights

## 1️⃣ Data Collection

* Stored raw agricultural data in AWS S3
* Loaded data into Snowflake Cloud Data Warehouse
* Connected Snowflake with Power BI
* Verified dataset structure and data consistency

## 2️⃣ Data Cleaning & Transformation

Performed data cleaning and transformation using SQL in Snowflake:

* Cleaned null and inconsistent values
* Standardized crop and seasonal categories
* Optimized dataset for reporting
* Transformed environmental and agricultural fields
* Performed aggregation and preprocessing using SQL

## 3️⃣ KPI Development

Developed dynamic KPIs including:

* Analyze Rainfall Analysis By Year / Season / Crops / Location 
* Analyze Temperature Analysis By Year / Season / Crops / Location 
* Analyze Humidity Analysis By Year / Season / Crops / Location 
* Analyze Average Rainfall Analysis By Year / Season / Crops / Location 

---

# 📊 Dashboard Preview

## 🔹 AWS S3 & Snowflake Data Pipeline

![Image1](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Loading%20Data%20From%20Amazon%20S3%20TO%20Snowflake.png)

![Image2](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Creating%20IAM%20Roles%20In%20AMAZON%20.png)

![Image3](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Creating%20Integration%20Object%20In%20Snwoflake%20.png)

## 🔹 Data Cleaning & Transformation Using SQL

![Image1](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Creating%20Table%20and%20Schema%20Inside%20Snowflake%20.png)
![Image2](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Data%20Cleaning%20and%20Tranformation%20In%20Snowflake%202.png%20.png)
![Image3](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Data%20Cleaning%20and%20Tranformation%20In%20Snowflake%201.png)

## 🔹 Dashboard Overview

![Image1](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Agriculture%20Rainfall%20Analysis%20.png)
![Image2](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Agriculture%20Temperature%20%20Analysis%20.png%20.png)
![Image3](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Agriculture%20Humidity%20Analysis%20.png)
![Image4](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Agriculture%20Yield%20Analysis%20.png)

## 🔹 Power BI Service Published Report

![Image1](https://github.com/ROHIT19K/Agriculture-Analysis-Using-AWS-SNOWFLAKE-POWER-BI-/blob/main/Agriculture%20Power%20BI%20Servie%20Publisehd.png)


---

# 🔍 Key Insights

📌 Rainfall Insights

* Bangalore recorded the highest average rainfall at approximately 3.8K mm, indicating strong rainfall concentration in the region.
* Raichur, Kasaragodu, and Mangalore also showed consistently high rainfall levels above 3.1K mm.
* Rabi season experienced the highest average rainfall (~3105 mm), followed closely by Kharif and Zaid seasons.
* Paddy crops received the highest average rainfall (~3.5K mm), making them highly rainfall-dependent.
* Rainfall trends remained relatively stable across years, fluctuating between 2.7K mm and 3.2K mm.
* Regions with higher rainfall showed improved agricultural productivity for water-intensive crops.

🌡️ Temperature Insights

* Bangalore recorded the highest average temperature level (~186), significantly higher than other regions.
* Davangere and Raichur also experienced comparatively high temperature conditions.
* Kharif and Zaid seasons showed the highest average temperatures (~72), indicating warmer cultivation periods.
* Ginger crops had the highest average temperature exposure (~79), followed by Tea and Cashew crops.
* Temperature trends varied across years, with certain years showing noticeable spikes that could impact crop productivity.
* Moderate temperature regions demonstrated better consistency in crop performance and environmental balance.

.
💧 Humidity Insights
* Average humidity remained highly stable across all years, maintaining values around 55–56%.
* Rabi, Zaid, and Kharif seasons displayed nearly identical humidity levels, indicating balanced atmospheric moisture conditions.
* Crops such as Cotton, Pepper, Coffee, and Blackgram showed the highest humidity compatibility.
* Most locations maintained consistent humidity values, supporting stable agricultural environments.
* Stable humidity conditions indicate lower environmental volatility and better crop sustainability across seasons.

🌾 Yield Insights

* Cotton recorded the highest average yield (~51K), making it the top-performing crop in the dataset.
* Coconut and Ginger also demonstrated strong agricultural productivity with yields above 25K.
* Rabi season generated the highest average yield (~24.9K), outperforming Zaid and Kharif seasons.
* Kodagu achieved the highest regional yield (~28.7K), followed closely by Mysuru and Madikeri.
* Yield trends showed gradual improvement across several years, indicating agricultural growth and productivity optimization.
* Crops with balanced rainfall and moderate temperature conditions generally achieved higher yield performance
---

# ☁️ Cloud Data Architecture

## ✅ AWS S3

Used AWS S3 for:

* Raw data storage
* Scalable cloud-based data management
* Centralized dataset storage

## ✅ Snowflake

Used Snowflake for:

* Cloud data warehousing
* SQL-based data transformation
* Data cleaning and preprocessing
* Query optimization and reporting support

## ✅ Power BI Integration

Connected Snowflake with Power BI for:

* Interactive dashboard creation
* Real-time analytical reporting
* Data visualization and business insights

---

# 🚀 Future Enhancements

* Add real-time weather API integration
* Implement predictive crop yield forecasting using Machine Learning
* Integrate IoT-based agricultural sensor data
* Create farmer-level performance analysis
* Add satellite and GIS-based agricultural mapping
* Implement automated ETL pipelines
* Build mobile-optimized dashboard version
* Deploy enterprise-level cloud reporting architecture

---

# ▶️ How to Run the Project

## Step 1: Download Project Files

* Download the `.pbix` Power BI dashboard file
* Download dataset files if required

## Step 2: Configure Snowflake Connection

* Connect Power BI with Snowflake
* Update credentials and connection settings if required
* Refresh dataset connections

## Step 3: Open Power BI Dashboard

* Open the `.pbix` file using Power BI Desktop
* Explore dashboard visuals

---

# 📊 Project Workflow

1. Raw Data Storage in AWS S3
2. Data Loading into Snowflake
3. SQL-Based Data Cleaning & Transformation
4. Data Modeling
5. KPI Development
6. Dashboard Design in Power BI
7. Interactive Reporting
8. Business Insights Generation
9. Cloud-Based Analytics Reporting

---

# ✅ Results & Outcomes

* Successfully built an interactive Agriculture Analysis Dashboard.
* Implemented cloud-based analytics workflow using AWS S3 and Snowflake.
* Improved visibility into crop production and climate trends.
* Enabled detailed agricultural performance analysis.
* Created dynamic KPI monitoring system.
* Delivered actionable agricultural insights for decision-making.
* Demonstrated expertise in cloud data engineering and Power BI reporting.

---

# 📬 Contact

## 👤 Author

**Your Name**

* LinkedIn: [https://linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
* GitHub: [https://github.com/yourusername](https://github.com/yourusername)
* Email: [yourmail@gmail.com](mailto:yourmail@gmail.com)



