# 🛒 E-Commerce Cart Abandonment Dashboard & ML Analysis

This project presents an interactive dashboard and machine learning model to analyze and predict **cart abandonment behavior** in an e-commerce setting. It helps businesses understand **why users abandon carts**, identify key patterns, and take **proactive steps** like targeted offers to improve conversion rates.

---

## 📌 Project Objectives

- Analyze user session behavior and identify abandonment trends.
- Visualize key metrics such as cart value, demographics, and device preferences.
- Build a basic machine learning model to predict the likelihood of cart abandonment.
- Suggest data-driven strategies to reduce cart abandonment.

---

## 🧠 Key Insights

- **Accessories** have a high abandonment rate — potential opportunity for discount nudges.
- **Mobile users** tend to abandon carts more often, likely due to poor UX or payment issues.
- A large share of users are **female**, which can guide product-based campaigns.
- **Social media referrals** have lower purchase intent — consider targeted remarketing.
- **Virginia** sees the highest abandonment; **New York** the least — useful for regional targeting.
- **No Guest Checkout** is the top reason for abandonment — a clear UX fix opportunity.

---

## 🧮 Features & KPIs

| KPI | Description |
|-----|-------------|
| ✅ Total Users | All sessions analyzed |
| ❌ Abandoned Users | Users who abandoned cart |
| 📉 Abandonment Rate | % of users who did not complete checkout |
| 💰 Avg. Cart Value | Average value of carts |
| 🕒 Avg. Session Duration | How long users stayed in session |
| 📆 Filters | Device Type, Gender, Referral Medium, Week, Day |

---

## 📊 Visualizations

- Purchase Category by Cart Status
- Abandonment Reason (if available)
- Demographic breakdown (Gender, Location, Referral, Device)
- Weekly & Day-wise trends
- Cart Content distribution

---

## 🧠 Machine Learning (Prototype)

- **Goal:** Predict whether a user will abandon cart or not
- **Model Used:** Random Forest, GridSearchCV
- **Accuracy:** ~50% (due to limited data features)
- **Improvement:** Richer data like clickstream, page views, pricing sensitivity, promo codes, etc.

---

## 🧰 Tech Stack

- **Python**
- **Pandas, Plotly, Seaborn, Scikit-learn**
- **Streamlit** – for interactive dashboard

---

## 🚀 How to Run

```bash
# 1. Clone this repo
git clone https://github.com/yourusername/cart-abandonment-dashboard.git
cd cart-abandonment-dashboard

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run Streamlit App
streamlit run dashboard.py
