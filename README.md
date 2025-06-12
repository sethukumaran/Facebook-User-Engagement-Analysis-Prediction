# Facebook-User-Engagement-Analysis-Prediction

## Overview

This data science project explores how **demographic attributes** (like age, gender, and tenure) affect **user engagement behaviors** on Facebook. In addition to detailed **descriptive analytics**, the project uses **predictive modeling** to forecast user interaction levels.

We analyze patterns and build machine learning models to answer:
- What factors influence how active users are?
- Can we predict a user's engagement based on their demographic profile?

---

## Objectives

- Perform **exploratory data analysis (EDA)** to understand user behavior.
- Segment users by **age group** and **tenure**.
- Analyze **likes, friendships, and activity** across gender and time-on-platform.
- Build predictive models to classify or predict **engagement intensity**.

---

## Dataset

The dataset includes anonymized Facebook user data with features like:
- `age`, `gender`, `tenure`
- `friend_count`, `friendships_initiated`
- `likes`, `likes_received`, `mobile_likes`, etc.

> Source: [FB Data.csv] – included in the notebook.

---

## Technologies Used

- **Python 3**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Visualization
- **Scikit-learn** – Predictive modeling (e.g., Random Forest)
- **Jupyter Notebook**

---

## Analysis Performed

- Cleaned and grouped data by **age group** and **tenure buckets**.
- Generated heatmaps and box plots to visualize:
  - Friendships initiated by age/gender
  - Likes received vs. platform usage (mobile/web)
  - Tenure impact on engagement levels
- Highlighted engagement trends by demographic segment

---

## Predictive Modeling

We used **machine learning** to predict **user engagement levels** based on:
- Demographics (age, gender, tenure)
- Interaction patterns (likes, friends, etc.)

**Steps involved:**
1. **Feature engineering**: Prepared input variables.
2. **Train-test split**: Partitioned dataset for model validation.
3. **Random Forest Classifier**: Trained to predict high vs. low engagement users.
4. **Model Evaluation**: Evaluated using accuracy and other metrics (expand if available).

---

## Key Insights

- Users aged **20–29** and with **1–3 years tenure** showed highest engagement.
- **Mobile engagement** surpassed web-based activity across all age groups.
- **Gender differences** were visible in likes received but not in friendships initiated.
- The Random Forest model showed promising predictive capability for classifying user engagement levels.

---
