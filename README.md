# 📱 Flipkart Mobile Data Analysis (Web Scraping + EDA)

## 📌 Project Overview

While learning Data Analytics, I wanted to go beyond clean, pre-structured datasets and work on a real-world business problem using live marketplace data.

With hundreds of smartphones listed on Flipkart, customers often struggle to decide:

- Bigger battery?
- Better processor?
- Higher price?
- Better ratings?

But the real question is:

> **Which phone actually offers the best value for money?**

This project analyzes real-world Flipkart mobile data to understand how price, brand, processor, battery, storage, and ratings influence purchasing decisions.

---

## 🎯 Business Problem

Mobile specifications are spread across product pages in mixed formats, making comparison difficult.

Customers often struggle to understand:

- Which brand dominates the marketplace?
- Does a higher price always mean better ratings?
- Which processor segment is most common?
- Do bigger batteries increase price?
- Which brand offers the best value in budget & mid-range?

---

## 🛠️ Tools & Technologies Used

- Python  
- Requests  
- BeautifulSoup  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🔍 My Approach

### 1️⃣ Data Collection (Web Scraping)

- Scraped live mobile listing data using Requests & BeautifulSoup
- Extracted 900+ mobile listings
- Collected:
  - Brand  
  - Price  
  - Original Price  
  - Ratings  
  - Battery (mAh)  
  - Storage (GB)  
  - Processor  
  - Warranty  

---

### 2️⃣ Data Cleaning & Preprocessing

Real-world data is messy. Cleaning was a major part of this project.

- Converted mixed text fields (₹ price, mAh battery, GB storage) into numeric format  
- Removed duplicate entries  
- Handled missing values  
- Treated price outliers using the IQR method  
- Standardized column names  
- Created derived columns for better insights  

---

### 3️⃣ Exploratory Data Analysis (EDA)

Performed:

- Univariate Analysis (Price distribution, brand frequency)  
- Bivariate Analysis (Battery vs Price, Price vs Ratings)  
- Multivariate Analysis  
- Correlation Heatmaps  
- Brand-level comparisons  
- Segment-based price categorization  

---

## 📊 Key Insights

- Budget & mid-range segment (₹5,000–₹30,000) dominates the market  
- Price distribution is positively skewed with few premium outliers above ₹60,000  
- 50MP cameras and 5000–6000mAh batteries are now standard in mid-range phones  
- Moderate correlation between price, storage, and ratings  
- Strong correlation (0.87) between price and original price  
- Realme & Samsung lead in total listings  
- Apple dominates the premium segment with highest average price  
- Higher price does NOT always guarantee better ratings  

---

## 🏢 Brand-Level Business Insights

### 🔹 Realme
- Aggressive positioning in budget & mid-range segment  
- High listing volume strategy  

### 🔹 Samsung
- Strong presence across all price segments  
- Balanced product portfolio  

### 🔹 Apple
- Premium pricing strategy  
- Limited discounting  
- Highest average price per unit  

### 🔹 Motorola
- Competitive pricing  
- Strong battery capacity  
- Good rating performance  

Clear segment-based positioning is visible across brands.

---

## 📈 Business Impact

This analysis helps:

- Customers choose better value-for-money smartphones  
- Brands understand competitor positioning  
- Identify pricing trends in the Indian smartphone market  
- Recognize specification standards across different price segments  

---

## 💡 Key Learnings

Working with real-world scraped data taught me:

- Data cleaning is as important as analysis  
- Raw web data requires structured preprocessing  
- Outlier treatment significantly impacts insights  
- Visualizations make insights more powerful  
- Storytelling is crucial in Data Analytics  

---

## 🚀 Skills Strengthened

- Python Programming  
- Web Scraping  
- Data Cleaning  
- Exploratory Data Analysis  
- Data Visualization  
- Business Insight Generation  
- Data Storytelling  

---

## 📂 Project Structure

```
Flipkart-Mobile-Analysis/
│
├── Cleaned_Mobile_Data.csv              # Cleaned dataset used for analysis
├── flipkart_mobiles_data.csv            # Raw scraped dataset
├── scrapped_flipkart_mobile_data.ipynb  # Web scraping notebook
├── eda_analysis_filpkart_mobiles.ipynb  # EDA notebook
├── Flipkart_mobiles_prjct.ipynb         # Final combined analysis
├── Filpkart_mobile_analysis.pptx        # Project presentation
├── flipkart-icon.webp                   # Project image/logo
└── README.md                            # Project documentation
```
## 👤 Author

**Akhil Golla**  
Aspiring Data Analyst | Python | EDA | Web Scraping  

<p>
  <a href="mailto:akhilyadav2502@gmail.com">
    <img src="https://img.shields.io/badge/Email-akhilyadav2502%40gmail.com-red?style=for-the-badge&logo=gmail">
  </a>
  <a href="https://www.linkedin.com/in/akhilyadav25/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Akhil%20Yadav-blue?style=for-the-badge&logo=linkedin">
  </a>
</p>

---
