# **Financial Data Validation, Performance & Tax Analysis**

---

## **Overview**

This project focuses on the structured preparation, validation, and analysis of financial data for selected public companies across multiple years.

The objective is not only to analyze financial performance, but also to ensure that the underlying data is **reliable, consistent, and suitable for business interpretation**.

In addition to performance metrics, the project incorporates **tax-adjusted analysis** and **absolute performance (Profit After Tax)** to provide a more complete view of company profitability and **value generation**.

---

## **Business Objective**

The objective of this project is to simulate a real-world **business reporting workflow** by combining:

* Data selection from a wider dataset
* Transformation and metric engineering
* Validation logic to ensure data consistency
* Tax-adjusted financial analysis
* Structured reporting and interpretation

Before deriving insights, the project emphasizes:

* **Data quality**
* **Comparability across years**
* **Transparency of assumptions**

---

## **Dataset**

The dataset is compiled from publicly available company financial statements (**10-K reports and financial disclosures**).

It represents a **longitudinal dataset (2009–2023)** covering multiple companies across different industries.

For reporting purposes, the analysis focuses on the **2010–2022 period** to ensure consistency and comparability across all companies.

---

## **Data Preparation & Transformation**

The project starts from a **wide-format raw dataset** containing multiple financial variables.

From this dataset:

* Relevant fields were selected
* Data was cleaned and structured into a curated dataset
* New financial metrics were engineered to support analysis and reporting

This step reflects a realistic **data preparation layer prior to business analysis**.

---

## **Validation Logic**

To improve data reliability, the project includes:

* Year-to-year linking using **Key / PreviousKey logic**
* Handling of missing or non-comparable values
* Identification of edge cases (e.g. negative prior values)
* Error handling using **IFERROR**

A **Data Status** field is introduced to flag records that require attention before interpretation.

---

## **Tax Calculation Approach**

The project incorporates a **simplified income tax calculation** based on standardized tax rates by industry.

These tax rates are used as **analytical assumptions** to enable consistent comparison across companies and do not represent actual reported tax rates.

This allows the estimation of:

* **Estimated Tax Amount**
* **Profit After Tax**

---

## **Key Metrics**

The analysis focuses on both **relative and absolute performance metrics**:

* Revenue Growth
* Net Income Growth
* Profit Margin
* EBITDA Margin
* **Profit After Tax (absolute performance and value generation)**

These metrics support both **performance comparison** and **evaluation of value generation**.

---

## **Reporting**

The final output includes:

* Structured tables and validated datasets
* Charts for key financial indicators
* Business-oriented insights
* A final presentation (**PDF**) summarizing key findings

The analysis highlights differences in **growth patterns, profitability, and overall value generation** across companies.

---

## **Skills Demonstrated**

* Data cleaning and preparation
* Feature selection and metric engineering
* Validation logic design
* Financial and tax-adjusted analysis
* Business-oriented thinking
* Structured reporting and storytelling

---

## **Professional Value**

This project reflects a structured, **end-to-end analytical workflow** similar to a business reporting pipeline:

**Data selection → Transformation → Validation → Metric engineering → Tax adjustment → Reporting**

It demonstrates the ability to move beyond raw data analysis and deliver **reliable, business-ready outputs**.

---

