# 📦 Amazon Sales & Review Analytics Project

An **end-to-end Data Analytics & Visualization case study** focused on real-world Amazon e-commerce data — from **Python preprocessing** to a fully interactive **Power BI dashboard** with dual perspectives: *Customer Review Behavior* and *Product Sales Performance*.

---

## 📌 Problem Statement

A product insights team wants to analyze:

- **Product popularity** and **customer feedback patterns**  
- What influences *positive sentiment* and *review engagement*?  
- How do **discount strategies**, **ratings**, and **pricing** impact performance?
- Provide *stakeholders* with an interactive dashboard for better decision-making.

---

## 🎯 Objectives

- Extract insights from **review titles & content** using **sentiment analysis**  
- Track **discount trends**, **review patterns**, and **top performing products**  
- Profile **highly engaged users** and **popular products** across categories  
- Build **two interactive Power BI dashboards** with filters, KPIs, and story-driven visuals

---

## 🛠️ Tools & Skills Used

- **Python (Pandas, NumPy, TextBlob)** – For data cleaning, feature engineering, review length, and sentiment scoring
- **Power BI** – For dashboard creation, DAX-based KPIs, visuals, slicers, and formatting
- **Power Query** – Data model adjustments and data loading
- **DAX** – To calculate metrics like % Positive Sentiment, Avg Review Length, etc.
- **Data Storytelling** – Structured dashboards for both Sales and Review perspectives

---

## 🧠 Key Metrics & KPIs

#### Dashboard 1: *Customer Sentiment & Review Engagement*
- **Total Reviews**
- **% Positive Sentiment (from review titles)**
- **Avg Review Length**
- **Highly Engaged Users** (review_length > 100 words)
- **Sentiment Distribution (Positive, Neutral, Negative)**

#### Dashboard 2: *Product Sales & Performance*
- **Total Revenue**
- **Avg Discount %**
- **Avg Rating**
- **% Highly Rated Products** (rating > 4.5)
- **Total Products**

---

## 🧹 Data Preprocessing (Python)

### 🧪 Steps:
- Cleaned and standardized data using **Pandas**
- Calculated **review length** from review titles and content
- Used **TextBlob** for basic sentiment scoring
- Generated new features: `popularity_score`, `price_bucket`, etc.
- Exported clean `.csv` to be used in Power BI

---

## 📊 Dashboarding (Power BI)

### Dashboard 1: *Customer Behavior & Sentiment*
| Visual Type | Use Case |
|-------------|----------|
| Bar Chart | Top 10 Products by Avg Review Length |
| Histogram | Distribution of Review Lengths |
| Donut Chart | Sentiment Distribution |
| Matrix | Sentiment by Category |
| Scatter Chart | Popularity vs Rating (Quadrant Analysis) |
| KPIs | Engagement metrics & review insights |

### Dashboard 2: *Sales & Product Performance*
| Visual Type | Use Case |
|-------------|----------|
| Bar Chart | Top 10 Products by Popularity Score |
| Bar Chart | Discounted vs Actual Price per Category |
| Line Chart | Avg Rating by Price Bucket |
| Donut Chart | Product Category Distribution |
| Treemap | Sub-categories by Total Reviews |
| KPI Cards | Sales & discount metrics |

---

## 📁 Folder Structure

Amazon-Sales-Analytics-Project/  
├── Python_Analysis/  
│   ├── review_analysis.ipynb  
│   ├── sentiment_cleaning.ipynb  
├── PowerBI_Dashboard/  
│   ├── dashboard1_reviews.pbix  
│   ├── dashboard2_sales.pbix  
├── Data/  
│   ├── amazon_sails_clean_data.csv  
├── Assets/  
│   ├── screenshots/  
└── README.md

---

## 📸 Screenshots

> Add dashboard screenshots here inside `/Assets/screenshots/`

---

## 💡 Bonus Insights

- Review Sentiment is **81% Positive**, with very few negative cases
- **Highly Engaged Users** = 1.1K+ users with long reviews
- Quadrant Chart reveals **low-rated but popular products** — potential quality issues
- **Average Discount Amount** is ₹2.3K+ — might be worth re-strategizing

---

## 📬 Contact

📧 anuragmishrably800@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/anurag-mishra-b17051288/)

---

## ⭐ Feedback & Suggestions

Have feedback? Want to collaborate? Feel free to open an issue or connect! Your support helps improve my data journey 🚀

