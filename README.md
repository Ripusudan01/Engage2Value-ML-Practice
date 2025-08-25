# Engage2Value: Purchase Value Prediction from Multi-Session Digital Behavior

This repository contains the code and analysis for the **Engage2Value: From Clicks to Conversions** machine learning competition project, completed as part of the Machine Learning Practice Theory course.

---

## Project Overview

The goal of this project is to predict customer purchase value during user sessions on a digital commerce platform. The dataset includes detailed multi-session behavioral data, device info, marketing sources, and geographic indicators. By modeling these complex user patterns, this project aims to forecast purchase amounts accurately to support marketing optimization and customer value forecasting.

---

## Dataset Description

- Dataset consists of anonymized session-level records with features such as:
  - User engagement metrics (e.g., totalHits, pageViews, bounces, new_visits)
  - Session sequencing and timings (sessionNumber, sessionStart)
  - Device and browser attributes (deviceType, os, browser, screenSize)
  - Marketing and traffic source details (userChannel, trafficSource, adwordsClickInfo)
  - Geographical context (geoNetwork.city, locationCountry, geoNetwork.continent)
  - Unique identifiers (userId, sessionId)
- Target: `purchaseValue` — the amount spent by the customer in a session

---

## Model and Approach

- Performed extensive feature engineering to extract meaningful patterns from raw session data
- Employed regression models including Linear Regression, Random Forest, and XGBoost Regressor
- Used pipelines with imputation, encoding, and scaling for preprocessing
- Tuned models using randomized search and evaluated using r2_score as per competition guidelines
- Achieved an R² score of **0.79075**, ranking **#3 on the leaderboard**, earning an **S grade**

---

## Acknowledgements

- Dataset and competition hosted on Kaggle
- Thanks to instructors and peers from the Machine Learning Practice Theory course for guidance and support

---

## Contact

For questions or suggestions, please open an issue or reach out to me via LinkedIn - https://www.linkedin.com/in/ripusudan-jha/

---

**Happy Modeling!**

