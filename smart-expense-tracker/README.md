# Smart Expense Tracker

## Project Overview
Smart Expense Tracker is a beginner-friendly backend project designed to help users record daily expenses, organize spending by category, and receive simple insights on saving opportunities.  
This project is part of my internship preparation portfolio for software engineering roles (Ramp, Two Sigma, and similar companies), with a focus on learning how business needs can be translated into clean backend logic.

## Problem Statement
Many students and young professionals track spending manually in notes or spreadsheets, which makes it hard to:
- understand where money is going,
- identify overspending habits,
- make realistic saving decisions.

The goal of this project is to build a Python backend system that turns raw expense records into useful financial feedback.

## Planned Features
- User expense input (amount, date, category, note)
- Category management (food, transport, rent, utilities, etc.)
- Monthly and weekly spending summaries
- Overspending pattern detection (for example: unusually high spending in one category)
- Savings insights (simple recommendations based on spending trends)
- Export-ready summary data for future dashboard integration

## Tech Stack (Planned)
- **Python** – core language
- **Flask** – lightweight backend API
- **SQLite** – local database for expense records
- **Pandas** – data aggregation and trend analysis

## Project Architecture (High Level)
The planned architecture follows a simple layered backend design:

1. **API Layer (Flask Routes)**
   - Handles HTTP requests for creating and retrieving expense data.
2. **Service Layer (Business Logic)**
   - Validates input, computes spending summaries, detects patterns.
3. **Data Layer (SQLite + Pandas)**
   - SQLite stores transactions.
   - Pandas transforms data into analytics-ready tables.
4. **Insights Module**
   - Generates human-readable savings recommendations.

This structure is intentionally simple so I can deeply understand each layer before introducing more advanced frameworks.

## Development Timeline (5 Weeks)
> Note: All portfolio projects are developed in parallel within a 6-week internship-preparation plan.

- **Week 1: Planning & Setup**
  - Define data model and API endpoints
  - Initialize Flask app and SQLite schema
- **Week 2: Core Expense Tracking**
  - Implement create/read operations for expenses
  - Add category-based filtering
- **Week 3: Analytics with Pandas**
  - Build weekly/monthly summaries
  - Compute category-level spending statistics
- **Week 4: Overspending & Savings Insights**
  - Add threshold/rule-based overspending detection
  - Generate simple recommendations
- **Week 5: Testing, Refactoring, Documentation**
  - Write tests for routes and service functions
  - Improve code clarity and update README

## Learning Goals
- Build confidence with Python backend fundamentals
- Learn how to design and consume REST-style API endpoints
- Practice data modeling with SQLite
- Use Pandas for practical financial analytics
- Improve software engineering habits: project structure, testing, and documentation
- Learn how to explain technical decisions clearly for internship interviews

## Collaboration & Mentorship
I am building this project as a first-year software engineering student with support from classmates at École Supérieure Polytechnique de Dakar.  
Our collaboration includes:
- peer reviews of code and architecture decisions,
- discussion sessions to clarify Python and backend concepts,
- feedback on how to make the project more realistic and maintainable.

This mentorship helps me focus on understanding deeply rather than just shipping features quickly.

## How the Project Will Be Tested
Planned testing approach:
- **Unit tests** for core business logic (categorization, summaries, overspending checks)
- **API tests** for Flask endpoints (valid and invalid requests)
- **Data validation checks** to confirm clean input handling
- **Manual scenario tests** using sample student budget datasets
- **Regression checks** when new features are added

## Future Improvements
- Add user authentication and multi-user account support
- Support CSV import/export for bank statement integration
- Add budgeting goals and progress tracking
- Introduce a front-end dashboard (React or simple Flask templates)
- Deploy as a cloud-hosted API for public demo

## Author
**Name:** [Your Name]  
First-year Software Engineering Student, École Supérieure Polytechnique de Dakar  
Built as part of my internship preparation journey in backend and fintech-focused software engineering.
