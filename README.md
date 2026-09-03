# D2C-Brand-Growth-and-Performance-Analysis

## About the Project

This project analyzes the factors that drive customer value and retention for a Direct-to-Consumer (D2C) fashion brand.

The main objective was to understand:

**Is the brand building genuine customer loyalty, or are discounts primarily driving repeat purchases?**

Using data from approximately **3,900 customers in the United States**, I used Python, MySQL, and Excel to clean and analyze customer data, develop customer-level metrics, segment customers, and identify patterns in spending, loyalty, promotions, product preferences, and geography.

The goal was to turn the analysis into practical recommendations for customer retention and acquisition.

---

## Business Questions

The analysis focused on questions such as:

* Which customers are genuinely loyal and likely to remain active?
* Are discounts driving long-term loyalty or short-term purchases?
* Which customer segments generate the most value?
* Which product categories attract higher-quality customers?
* Which markets have strong customer quality but low penetration?
* What does the brand's ideal customer look like?

---

## Tools Used

| Tool               | Purpose                                     |
| ------------------ | ------------------------------------------- |
| **Python**         | Data cleaning, feature engineering, and EDA |
| **Pandas & NumPy** | Data manipulation and analysis              |
| **MySQL**          | Customer segmentation and business analysis |
| **Excel**          | Category, seasonal, and geographic analysis |

---

# Project Workflow

## 1. Data Cleaning and Exploration

The raw customer dataset was prepared for analysis by:

* Handling missing values
* Standardizing categorical data
* Removing redundant information
* Checking distributions and outliers
* Exploring relationships between spending, purchase frequency, tenure, ratings, and subscriptions

Python was primarily used for this stage.

---

## 2. Customer Scoring

Two separate measures were created to evaluate customer quality:

### Loyalty Score

Measures customer engagement using factors such as:

* Purchase frequency
* Review ratings
* Subscription status

### Value Score

Measures the customer's historical contribution to the business based on spending and purchase behavior.

Keeping loyalty and value separate helped identify customers who were high spenders but not necessarily loyal, and loyal customers with potential to increase spending.

---

## 3. Customer Segmentation

The Loyalty and Value Scores were combined to create four customer segments:

| Segment                | Description                            |
| ---------------------- | -------------------------------------- |
| **Champion**           | High loyalty and high value            |
| **Loyal Low-Spend**    | Loyal customers with growth potential  |
| **High-Spend Drifter** | Valuable customers with weaker loyalty |
| **Low Priority**       | Low engagement and low value           |

MySQL was used to build the segmentation logic and answer the key business questions.

---

## 4. Business Analysis

The analysis also examined customer behavior across:

### Product Categories

* Popular categories among high-value customers
* Categories associated with stronger loyalty
* The relationship between sales volume and customer quality

### Geography

US states were evaluated based on customer quality and market penetration to identify potential acquisition opportunities.

### Promotions

Promotional behavior was compared across customer segments, categories, and seasons.

One key observation was that discounts appeared to be distributed broadly rather than being strongly targeted toward customers who actually needed an incentive.

---

# Key Insights

### 1. Discounts May Be Affecting Margins

Highly loyal and long-tenured customers were also receiving substantial discounts, suggesting that some incentives may be unnecessary.

### 2. Loyalty and Value Are Different

High spending does not always indicate loyalty, and highly loyal customers are not always the highest spenders.

### 3. A Small Customer Group Drives Significant Value

A relatively small group performed strongly across spending, tenure, ratings, subscriptions, and engagement.

### 4. High Sales Do Not Always Mean Better Customers

Some categories generated high sales volumes but were not strongly represented among the best customer segments.

### 5. Some Markets Are Underpenetrated

Several states showed strong customer quality but relatively low penetration, creating potential opportunities for customer acquisition.

### 6. Promotions Could Be More Targeted

Similar promotional rates across categories and seasons suggest an opportunity to move away from broad discounting toward a more targeted strategy.

---

# Retention Strategy

## Champions

**Objective:** Protect loyalty while reducing unnecessary discounts.

* Offer early access and exclusive benefits
* Introduce subscription-based perks
* Gradually reduce blanket discounts

## Loyal Low-Spend Customers

**Objective:** Increase customer value.

* Cross-sell relevant products
* Use personalized recommendations
* Encourage subscription adoption

## High-Spend Drifters

**Objective:** Improve long-term loyalty.

* Launch re-engagement campaigns
* Identify declining purchase behavior
* Use personalized offers

## Low-Priority Customers

**Objective:** Avoid excessive marketing spend.

* Use low-cost automated communication
* Avoid unnecessary discounts
* Focus resources on higher-potential customers

---

# Promotional Strategy

Instead of completely removing discounts, the recommendation is to gradually reduce discount dependency:

**Identify → Test → Reduce → Monitor → Adjust**

Performance can be monitored using:

* Repeat purchase rate
* Customer retention
* Average order value
* Revenue per customer
* Discount rate
* Gross margin
* Subscription conversion
* Customer churn

Results can be reviewed over **30, 60, and 90-day periods**.

---

# Project Deliverables

* Cleaned customer dataset
* Loyalty and Value Scores
* Python-based EDA and feature engineering
* MySQL customer segmentation
* SQL-based business analysis
* Excel analysis
* Ideal Customer Profile
* Segment-specific retention strategy
* Promotional strategy and executive summary

---

# What This Project Demonstrates

This project combines technical data analysis with business decision-making and demonstrates experience in:

* Data cleaning and EDA
* Feature engineering
* SQL analysis
* Customer segmentation
* Customer retention analysis
* Promotional strategy
* Geographic analysis
* Data-driven decision-making

---

# Project Context

Completed as part of the **Consulting & Analytics Club, IIT Guwahati – Summer Projects 2026**.

The project was designed to simulate a real-world analytics problem, moving from **raw customer data to actionable insights and a practical retention strategy**.

**Author:** Ankit Kumar
**Institute:** MNNIT Allahabad
**Program:** B.Tech
