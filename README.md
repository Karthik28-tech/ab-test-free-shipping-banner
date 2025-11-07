🛒 A/B Test: Free Shipping Banner at Checkout

Goal: Measure whether showing a "Free Shipping" banner at the checkout page increases the purchase conversion rate for an e-commerce platform.

This project simulates a real-world product experiment where users reaching the checkout page are randomly split into Control (no banner) and Variant (banner shown) groups. The analysis validates whether the UI change meaningfully impacts conversions and revenue.

🔍 Key Objectives

✅ Run an A/B experiment on checkout step UX

✅ Compare conversion rates using a two-proportion z-test

✅ Quantify uplift and statistical significance

✅ Estimate real business impact (₹ revenue & profit)

✅ Explore user segments (e.g., mobile vs desktop)

✅ Provide SQL queries for funnel tracking & retention insight

📊 Headline Result (Synthetic Sample)
Metric	Control	Variant
Conversion Rate (CVR)	3.4%	4.2%
Uplift	—	+23.5%
p-value	—	< 0.01 (Significant)
Monthly Revenue Impact	—	+₹18.4L projected

(Values auto-generated if no Kaggle dataset is used — notebook updates dynamically if real data is supplied.)

🛠 Tech Stack
Area	Tools
Data & Analysis	Python (Pandas, NumPy)
Statistical Testing	z-test for proportions (manual + Statsmodels option)
Visualization	Matplotlib
SQL Analytics	CTEs, Window Functions
Dataset Source	Kaggle E-Commerce Event Logs

📁 Repository Contents

├── ab_test_analysis.ipynb       # Full Python notebook (A/B test)
├── funnel_analysis.sql          # SQL query for user funnel stages
├── cohort_retention.sql         # SQL for cohort & repeat behavior
├── synthetic_checkout_sessions.csv   # Sample dataset (auto fallback)
├── images/                      # Exported charts (uplift, CVR)
├── README.md                    # Documentation
└── data_source.txt              # Kaggle dataset reference

📈 Business Insights Example

Free shipping messaging reduces price-friction at final stage, especially for cart values ₹700–₹1500

Mobile users respond more positively vs desktop (higher uplift %)

If validated with full traffic, the feature can be rolled out at 100% with margin monitoring

Follow-up experiments: banner styling, copy variants, cart value threshold logic

🚀 How to Run
git clone https://github.com/Karthik28-tech/ab-test-free-shipping-banner.git
cd ab-test-free-shipping-banner
open ab_test_analysis.ipynb

🏷 Suggested GitHub Topics
ab-testing
data-analysis
product-analytics
python
ecommerce
sql
statistics
business-intelligence
experimentation

📌 Author

Raparthi Karthik
LinkedIn: linkedin.com/in/raparthi-karthik
