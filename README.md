# Hi, I'm Mohammed Suhail 👋

🎓 **AI & Data Science student** · Jordan

I'm a student in Artificial Intelligence and Data Science, and I build projects in my field:
data pipelines, machine-learning models and dashboards, each one tested and documented.

## 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**Exoplanet Regression**](https://github.com/Mohdsuhail06/exoplanet-regression) | Can regression rediscover physics? From 6,473 NASA exoplanets, my from-scratch linear regression recovers Kepler's third law (powers 1.497 / −0.474 vs 1.5 / −0.5) and the planet temperature law, and catches the data traps (values NASA calculated with a formula, self-heating young planets) that would make the results lie | Python · NumPy · pandas · matplotlib · pytest |
| [**Jordan Climate Data Pipeline**](https://github.com/Mohdsuhail06/jordan-climate-pipeline) | ETL pipeline that loads 3 years of weather and air-quality data for 8 Jordanian cities into a DuckDB star-schema warehouse, with data-quality checks, quarantine and an analytics report | Python · pandas · DuckDB · SQL · pytest · GitHub Actions |
| [**Medicine Demand Forecasting**](https://github.com/Mohdsuhail06/medicine-demand-forecasting) | Forecasts 14-day medicine demand per hospital, compares 5 models with rolling-origin backtesting, and turns forecasts into reorder recommendations served by a REST API | Python · scikit-learn · FastAPI · pandas · matplotlib |
| [**MedPredict Dashboard**](https://github.com/Mohdsuhail06/medpredict) · [live demo](https://mohdsuhail06.github.io/medpredict/) | Interactive hospital inventory dashboard prototype presented at AI Expo Jordan 2026 | HTML · CSS · JavaScript · Chart.js |

## 📚 Learning ML from scratch

I'm working through the core ML books (Géron, ISLP) one topic at a time. Every topic ends with a project where
I write the algorithm myself in NumPy first, then check it against scikit-learn. Full list: [**my-ml-journey**](https://github.com/Mohdsuhail06/my-ml-journey).

**Part 1: Regression** ✅

| Project | What I built |
|---|---|
| [linear-regression-from-scratch](https://github.com/Mohdsuhail06/linear-regression-from-scratch) | Closed form + gradient descent on real Jordan used-car prices |
| [price-predictor](https://github.com/Mohdsuhail06/price-predictor) | Multiple regression, one-hot, scaling, hand-written cross-validation and a data-leakage experiment |
| [overfitting-lab](https://github.com/Mohdsuhail06/overfitting-lab) | Polynomial regression that memorizes 12 cars (train error 0, test 57,349 JOD), bias-variance, learning curves |
| [regularization-lab](https://github.com/Mohdsuhail06/regularization-lab) | Ridge, Lasso and Elastic Net from scratch; Lasso keeps 16 of 768 columns |
| [exoplanet-regression](https://github.com/Mohdsuhail06/exoplanet-regression) | Final project: rediscovering physics laws from NASA data |

**Next:** Part 2, Classification (logistic regression, precision/recall, k-NN, Naive Bayes, SVM).

## 🛠️ Tools I use

**Languages:** Python, SQL, JavaScript
**Data engineering:** pandas, DuckDB, ETL design, data validation, REST APIs
**Machine learning:** NumPy, scikit-learn, linear models (Ridge, Lasso), cross-validation, feature engineering, time-series forecasting, model evaluation
**Engineering:** Git, GitHub Actions (CI), pytest, FastAPI, ruff

## 📌 How I work

- Every project ships with **automated tests** and **CI**.
- I compare models against **simple baselines** and evaluate **honestly**: no peeking at the test set, no leaking the future.
- I check **where every value in the data comes from**: a perfect score is a question, not an answer.
- READMEs explain **what the data shows**, not just how to run the code.
