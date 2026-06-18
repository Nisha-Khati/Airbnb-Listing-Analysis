# 🏠 Airbnb Data Analysis & Price Prediction

## 📌 Project Overview

The Airbnb marketplace generates massive amounts of data related to listings, pricing, availability, hosts, and customer reviews. This project leverages data analytics and machine learning techniques to uncover meaningful insights from Airbnb data and answer key business questions that directly impact revenue, occupancy, and customer satisfaction.

Using Airbnb Listings, Reviews, and Calendar datasets, this project explores market demand, pricing behavior, occupancy trends, host performance, and customer preferences. The analysis provides actionable recommendations that can help hosts, property managers, and travel businesses make data-driven decisions and optimize their performance in a highly competitive marketplace.



## 🎯 Business Problem

In the short-term rental industry, understanding what drives bookings and pricing is critical for maximizing revenue and maintaining high occupancy rates.

This project aims to answer questions such as:

- Which neighborhoods experience the highest demand?
- How does pricing vary by location, property type, and season?
- Are professional hosts dominating the marketplace?
- What factors contribute to higher occupancy?
- Do higher-priced properties receive better customer ratings?
- Can machine learning accurately predict listing prices and occupancy levels?

---

## 📂 Dataset Information

The project utilizes three interconnected Airbnb datasets:

### 🏡 Listings
Contains detailed information about properties, including:
- Property type
- Room type
- Location
- Host information
- Pricing
- Review scores

### 📅 Calendar
Contains:
- Daily availability
- Daily pricing
- Occupancy-related information

### ⭐ Reviews
Contains:
- Customer feedback
- Review dates
- Historical guest activity

Together, these datasets provide a comprehensive view of Airbnb marketplace dynamics.



## 🔍 Exploratory Data Analysis

The analysis focuses on uncovering hidden patterns and trends through data exploration and visualization.

### 📍 Demand Analysis
Identified neighborhoods with the strongest booking demand by analyzing:
- Review frequency
- Availability trends
- Occupancy patterns

### 💰 Pricing Analysis
Examined how pricing changes across:
- Property types
- Room types
- Neighborhoods
- Seasonal periods

### 🏢 Host Performance Analysis
Evaluated:
- Host portfolio sizes
- Market concentration
- Professional vs Individual hosts

### 📈 Occupancy Analysis
Investigated:
- Availability rates
- Fully booked listings
- Occupancy trends by property type and location

### ⭐ Customer Satisfaction Analysis
Studied relationships between:
- Price and overall ratings
- Price and value ratings
- Affordability and guest satisfaction



## 📊 Key Findings

### High-Demand Areas
- Broadway emerged as the most in-demand neighborhood.
- Belltown and First Hill showed the lowest availability, indicating higher occupancy.
- High review counts combined with low availability strongly indicate strong booking demand.

### Pricing Trends
- Entire homes/apartments are significantly more expensive than private rooms.
- Boats represent the highest-priced property category.
- Peak pricing occurs during the summer months (June–August).
- January offers the lowest average prices, making it ideal for budget-conscious travelers.

### Host Market Concentration
- Approximately 83% of hosts own only one listing.
- A very small percentage of professional hosts control a significant share of the market.
- Some hosts operate dozens of listings, functioning as property management businesses rather than individual hosts.

### Occupancy Insights
- Several listings remain fully booked throughout the year.
- South Lake Union recorded the highest average occupancy.
- Entire homes outperform shared accommodations in booking rates.

### Customer Satisfaction
- Listing price has almost no relationship with overall ratings.
- Affordable listings often provide better perceived value.
- Guests prioritize experience and value over premium pricing.



## 🤖 Machine Learning Models

### 1️⃣ Price Prediction Model

**Objective:** Predict the nightly price of an Airbnb listing.

#### Approach
- Data preprocessing
- Feature engineering
- Regression modeling
- Model evaluation

#### Results
- Achieved an R² score of approximately **0.56**
- Successfully captured major pricing patterns across listings
- Performed best for low-to-mid range properties



### 2️⃣ Occupancy Classification Model

**Objective:** Predict whether a listing will experience high or low occupancy.

#### Approach
- Occupancy segmentation
- Classification modeling
- Performance evaluation

#### Results
- Strong performance in identifying low-occupancy listings
- Revealed challenges in predicting highly occupied properties due to class imbalance and market complexity



## 🛠️ Technologies Used

### Programming & Analytics
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn
- Power BI

### Machine Learning
- Scikit-learn

### Data Management
- SQL

### Development Environment
- Jupyter Notebook



## 📈 Business Impact

This analysis demonstrates how data-driven decision-making can improve performance in the hospitality and travel industry.

The insights generated can help:

✅ Hosts optimize pricing strategies

✅ Improve occupancy rates

✅ Identify profitable neighborhoods

✅ Understand customer preferences

✅ Maximize revenue opportunities

✅ Support strategic investment decisions


## 🚀 Future Enhancements

- Advanced demand forecasting
- Dynamic pricing recommendation system
- Sentiment analysis on customer reviews
- Interactive Power BI dashboard deployment
- Recommendation engine for travelers
- Deep learning models for improved price prediction



## 👩‍💻 Author

**Nisha Khati A**

📊 Data Analyst  
🚀 AI Enthusiast  

"Transforming data into insights and insights into impact."


