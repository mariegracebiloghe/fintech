# Transaction Fraud Detector

## Project Overview
Transaction Fraud Detector is a Python project aimed at identifying suspicious financial transactions using a combination of rule-based detection and beginner-level machine learning.  
This project is part of my internship preparation portfolio and focuses on connecting backend engineering with practical risk analysis in finance.

## Problem Statement
Fraud detection is critical for digital payments and financial platforms. Even a simple transaction system needs mechanisms to:
- detect unusual behavior early,
- reduce false alerts,
- support faster human review.

As a beginner, my goal is to build a foundational fraud detection workflow that is understandable, testable, and extensible.

## Planned Features
- Transaction ingestion from sample datasets
- Rule-based checks (high amount, unusual frequency, location mismatch)
- Feature extraction for basic ML classification
- Suspicious transaction scoring and flagging
- Flask API endpoint to submit and evaluate transactions
- Logging and explanation output for flagged decisions

## Tech Stack (Planned)
- **Python** – core language
- **Pandas** – transaction data processing
- **Scikit-learn** – introductory machine learning models
- **Flask** – API layer for fraud-check requests

## Project Architecture (High Level)
Planned architecture combines deterministic rules with simple ML:

1. **Input/API Layer (Flask)**
   - Accepts transaction data and returns fraud risk response.
2. **Preprocessing Layer (Pandas)**
   - Cleans and transforms transaction fields.
3. **Rule Engine**
   - Applies explicit fraud heuristics.
4. **ML Scoring Module**
   - Produces basic risk predictions from engineered features.
5. **Decision Layer**
   - Combines rule and ML outputs into a final flag/score.
6. **Logging Layer**
   - Stores decision context for traceability and review.

The design is intentionally simple to prioritize learning and clear reasoning.

## Development Timeline (5 Weeks)
> Note: This project is developed in parallel with two other projects within an overall 6-week internship-preparation schedule.

- **Week 1: Scope Definition & Data Understanding**
  - Identify fraud scenarios to simulate
  - Prepare sample transaction schema
- **Week 2: Rule-Based Detection Engine**
  - Implement baseline rules and thresholds
  - Test against synthetic edge cases
- **Week 3: Feature Engineering & ML Baseline**
  - Create core features from transaction data
  - Train a simple classification model
- **Week 4: API Integration & Decision Logic**
  - Expose detection flow through Flask endpoints
  - Merge rule-based and ML signals
- **Week 5: Testing, Analysis, Documentation**
  - Evaluate false positives/negatives at a basic level
  - Refactor and document design decisions

## Learning Goals
- Understand fraud detection fundamentals from an engineering perspective
- Learn to combine rule-based logic with machine learning
- Practice feature engineering with transactional data
- Improve backend API design and response formatting
- Build confidence interpreting model outputs and limitations
- Develop responsible habits around explainability and traceability

## Collaboration & Mentorship
I am developing this as a first-year student with guidance from classmates at École Supérieure Polytechnique de Dakar.  
Our collaboration includes:
- peer discussion on fraud logic and edge cases,
- code walkthroughs to improve structure,
- shared debugging sessions for Flask and model behavior,
- feedback to keep the project realistic for internship-level expectations.

## How the Project Will Be Tested
Planned testing strategy:
- **Unit tests** for rule functions and feature calculations
- **API tests** for request validation and response format
- **Scenario-based tests** with synthetic fraudulent and non-fraudulent cases
- **Basic model evaluation** (precision/recall awareness at beginner level)
- **Error-handling tests** for malformed or missing transaction fields

## Future Improvements
- Add model monitoring for performance drift
- Introduce more advanced anomaly detection approaches
- Improve explainability with clearer reason codes per flag
- Expand dataset realism with temporal and user-behavior features
- Deploy API and add simple reviewer dashboard

## Author
**Name:** [Your Name]  
First-year Software Engineering Student, École Supérieure Polytechnique de Dakar  
Built as part of my internship preparation journey to connect backend systems, data thinking, and fintech problem solving.
