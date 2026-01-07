# bank_loan_analysis
Business Analytics project using SQL, Power BI and Power Query for Bank Loan Analysis (Finance Domain)


Bank Loan Analysis | Enterprise-Grade Business Intelligence Project
Executive Summary

This repository showcases an enterprise-style Bank Loan Analytics solution designed to mirror how data is consumed, validated, and presented in FAANG-scale and consulting-led analytics environments.

The project demonstrates end-to-end ownership of a financial analytics workflow—spanning data ingestion, transformation, SQL-based validation, time intelligence, KPI design, and executive-ready visualization using Power BI.

The outcome is a decision-focused, production-aligned BI asset that enables stakeholders to assess portfolio health, credit risk exposure, and repayment performance with confidence.

Business Problem Statement

Financial institutions must continuously balance loan growth, capital efficiency, and credit risk. Raw loan data alone does not provide the visibility required to:

Monitor portfolio quality

Track repayment effectiveness

Identify high-risk segments early

Compare period-over-period performance

This project addresses that gap by converting granular loan data into actionable intelligence through standardized KPIs, validated metrics, and interactive dashboards.

Analytical Objectives

Measure loan demand and funding efficiency

Evaluate repayment performance and recovery

Segment Good vs Bad Loans for risk visibility

Perform MTD / PMTD trend comparison

Analyze borrower risk using Interest Rate and DTI

Enable multi-dimensional analysis by region, purpose, tenure, and borrower profile

Data & Methodology
Data Source

Loan-level financial dataset (CSV)

Includes borrower attributes, loan terms, repayment metrics, and status flags

ETL & Data Engineering (Power Query)

Schema standardization and data type enforcement

Handling missing and inconsistent categorical values

Feature readiness for time intelligence

Metric normalization (interest rate, DTI)

Performance-optimized data model

SQL as a Validation Layer

SQL was used as a single source of metric truth to:

Validate Power BI KPIs

Cross-check aggregations and percentages

Ensure financial and analytical accuracy

Metrics validated include:

Total Loan Applications

Funded vs Received Amounts

Average Interest Rate and DTI

Good / Bad Loan percentages

MTD and PMTD calculations

Power BI Dashboard Design

The dashboard is structured for executive consumption:

KPI scorecards for instant portfolio health assessment

Time-series trend analysis

Risk segmentation via loan status

Regional and demographic drill-downs

Fully interactive slicers and cross-filtering

The design prioritizes clarity, consistency, and decision velocity.

Business Impact

This solution enables:

Faster identification of high-risk loan segments

Transparent monitoring of repayment efficiency

Data-backed portfolio optimization discussions

Improved stakeholder trust through validated metrics

The framework is scalable and adaptable for real-world banking environments.

Repository Structure
├── data
│   └── financial_loan.csv
├── sql
│   └── bank_loan_analysis.sql
├── powerbi
│   └── bank_loan_analysis.pbix
├── docs
│   ├── Bank Loan Analysis Project.docx
│   └── Domain Knowledge Doc.docx
└── README.md
Core Competencies Demonstrated

Business Intelligence & Analytics Thinking

SQL for Metric Validation

Power BI Dashboard Engineering

ETL & Data Modeling

Time Intelligence (MTD / PMTD)

Financial & Credit Risk Analytics

Executive-Level Data Storytelling

Recruiter-Friendly README (Short Version)
Bank Loan Analysis | SQL + Power BI

A production-style BI project analyzing bank loan performance, credit risk, and repayment efficiency.

Highlights:

End-to-end analytics ownership

SQL-validated KPIs

MTD / PMTD time intelligence

Good vs Bad loan risk framework

Executive-ready Power BI dashboard

Tech Stack: SQL | Power BI | Power Query | Financial Analytics
