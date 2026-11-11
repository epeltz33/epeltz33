# Eric Peltzman

**Entry-level software developer** · Python, Flask, PostgreSQL

[StockWatch live demo](https://stockwatch-cqzs.onrender.com/demo/) · [LinkedIn](https://www.linkedin.com/in/eric-peltzman) · [erpeltz@gmail.com](mailto:erpeltz@gmail.com)

I build small web apps and take them all the way to deployed: database, auth, tests, CI, and a live URL.
Open to entry-level **backend or fullstack** roles.

## Featured project

### [StockWatch](https://github.com/epeltz33/StockWatch)

[![CI](https://github.com/epeltz33/StockWatch/actions/workflows/ci.yml/badge.svg)](https://github.com/epeltz33/StockWatch/actions/workflows/ci.yml)

Multi-user stock watchlists and a cost-basis portfolio ledger, deployed and running end to end.

[![StockWatch market view: price chart, watchlist, and stock details](https://raw.githubusercontent.com/epeltz33/StockWatch/main/docs/screenshots/demo-market.png)](https://stockwatch-cqzs.onrender.com/demo/)

**[Try the demo](https://stockwatch-cqzs.onrender.com/demo/)** (sample data, no login; free-tier host, so the first load after idle can take ~30s)

- **App structure:** Flask application factory + blueprints, Plotly Dash charts
- **Data:** PostgreSQL in production, SQLite locally, Alembic migrations
- **Market data:** Massive.com API behind layered response caching to stay inside rate limits
- **Auth:** Flask-Login with hashed passwords and CSRF protection
- **Quality:** 240+ pytest tests and ruff, run in GitHub Actions
- **Ops:** Docker Compose for local Postgres, hosted on Render

## Other projects

| Project | What it is | Stack |
|---|---|---|
| [Care Gap SMART App](https://github.com/epeltz33/Care-Gap-SMART-App) | SMART on FHIR app that finds gaps in preventive and chronic-disease care and shows the evidence behind each one. In development; synthetic data only. | React · Flask · FHIR R4 |
| [Churn Predictor](https://github.com/epeltz33/Churn-predictor) | Telecom churn classifier: EDA, feature engineering, class-imbalance handling, and a Streamlit dashboard for predictions. | scikit-learn · XGBoost · Streamlit |
| [NoteLab](https://github.com/epeltz33/NoteLab) | Full-stack notes app with create / edit / delete and filtering by type. | AngularJS · Express · MongoDB |
| [Task Tracker](https://github.com/epeltz33/Task_Tracker) | Dependency-free CLI for add / update / complete / list with JSON persistence and file-error handling. | Python |

## What I work with

**Languages:** Python · SQL · Java · JavaScript  
**Backend:** Flask · SQLAlchemy · Flask-Login · Alembic  
**Data:** PostgreSQL · REST APIs  
**Dashboards:** Plotly Dash · Dash Bootstrap  
**Tooling:** Git · pytest · GitHub Actions · Docker · Render

## Currently

- Building the Care Gap SMART App (Phase 1 of 4): SMART launch and FHIR patient summary.
- Tightening StockWatch: tests, deploy, and docs.
