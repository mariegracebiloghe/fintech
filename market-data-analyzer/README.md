# Market Data Analyzer

## Project Overview
Market Data Analyzer is a Python data project focused on loading market datasets, computing core statistics, visualizing trends, and applying simple predictive models.  
It is part of my internship preparation portfolio for software engineering roles, and it is designed to strengthen my ability to transform financial questions into reproducible data workflows.

## Problem Statement
Financial data is large, noisy, and hard to interpret without structure. Beginners often struggle to:
- clean and organize raw datasets,
- identify meaningful trends,
- connect descriptive analytics with basic forecasting.

This project addresses that gap by building a clear, step-by-step analysis pipeline for market data.

## Planned Features
- Dataset loading from CSV files
- Data cleaning (missing values, type conversion, date formatting)
- Descriptive statistics (returns, moving averages, volatility proxies)
- Trend visualizations (price movement, rolling metrics)
- Basic predictive modeling (simple regression/baseline forecasting)
- Reusable analysis scripts for multiple datasets

## Tech Stack (Planned)
- **Python** – core language
- **Pandas** – data ingestion and transformation
- **NumPy** – numerical operations
- **Matplotlib** – static visualizations for trend analysis

## Project Architecture (High Level)
Planned pipeline-oriented architecture:

1. **Data Ingestion Module**
   - Reads and validates input datasets.
2. **Data Preparation Module**
   - Cleans records and standardizes schema.
3. **Analytics Module**
   - Computes indicators and summary statistics.
4. **Visualization Module**
   - Produces line charts and comparison plots.
5. **Modeling Module**
   - Applies basic predictive techniques for learning purposes.

This modular structure helps me understand each phase of a real analytics workflow.

## Development Timeline (5 Weeks)
> Note: This project is built in parallel with two other portfolio projects inside a broader 6-week plan.

- **Week 1: Project Framing & Dataset Selection**
  - Define analysis objectives
  - Collect and inspect sample market datasets
- **Week 2: Data Cleaning Pipeline**
  - Standardize date formats and numeric columns
  - Handle missing or inconsistent rows
- **Week 3: Descriptive Analytics**
  - Compute returns, rolling averages, and summary metrics
  - Compare indicators across time windows
- **Week 4: Visualization & Basic Prediction**
  - Build trend charts in Matplotlib
  - Add a simple baseline predictive model
- **Week 5: Validation, Refactoring, Documentation**
  - Verify outputs on multiple datasets
  - Improve code readability and document assumptions

## Learning Goals
- Build practical confidence in Pandas/NumPy workflows
- Learn to design clean, reusable data analysis pipelines
- Improve data storytelling through clear visualizations
- Understand limits of basic predictive models
- Practice technical communication for interviews and project presentations
- Strengthen debugging and validation habits with real datasets

## Collaboration & Mentorship
This project is developed with support from classmates who help me:
- review analysis choices,
- identify mistakes in data cleaning assumptions,
- improve code structure and readability,
- discuss trade-offs between model simplicity and interpretation.

As a beginner, this collaborative process is essential for deep learning and steady progress.

## How the Project Will Be Tested
Planned testing and validation strategy:
- **Data integrity checks** after ingestion and cleaning
- **Unit tests** for transformation and metric functions
- **Output consistency tests** on small controlled datasets
- **Visualization review** to verify trend correctness
- **Model sanity checks** comparing predictions to simple baselines

## Future Improvements
- Add interactive visualizations (Plotly)
- Expand to multiple asset classes and cross-market comparison
- Integrate external APIs for automated data updates
- Introduce time-series models after mastering fundamentals
- Package the pipeline as a reusable command-line tool

## Author
**Name:** [Your Name]  
First-year Software Engineering Student, École Supérieure Polytechnique de Dakar  
Built as part of my internship preparation in software engineering, data analysis, and fintech-oriented problem solving.
