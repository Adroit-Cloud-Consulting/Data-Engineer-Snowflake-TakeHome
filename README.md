# Adroit Snowflake Data Task Take Home

## Snowflake Demo Account

- **URL**: `<to be provided – Snowflake demo account URL>`
- **User**: `TakeHome`
- **Initial password**: `ToBeProvided`

## CSV File

Download the dataset file named anonymous_customers.csv from this repo

This CSV contains customer information, order details, and a JSON-formatted string of order items in a single flat table.

---

## Task Title

**Loading and Analysing Data in Snowflake with Python**

---

## Objective

This task is designed to assess your ability to:

- Load a CSV file into Snowflake using Python
- Design and create an appropriate schema
- Perform aggregations and analysis
- Showcase any additional tools, libraries, or techniques that you feel add value

---

## Task Details

### 1. Download and Load Data

Write a Python script that:

- Downloads the CSV file from the link above
- Loads the data into the provided Snowflake account

You can run the script locally or use Python capabilities within Snowflake.

The CSV is structured as a single flat table containing:

- Customer details
- Order details
- A JSON array (as a string) describing order items

---

### 2. Table Design and Creation

Design and create at least three tables in Snowflake to model the data:

- **Customer**
- **Order**
- **OrderItem** (parsed from the JSON string)

You may create additional tables if it improves your design.
You may use any modelling approach you prefer (e.g. 3NF, Data Vault, Star Schema/Kimball, etc.).

---

### 3. Data Aggregation

Create a **view** in Snowflake which:

- Aggregates sales data by **week** and **product**
- Includes a Boolean column that flags the top-selling product for each week (`1` for top seller, `0` otherwise)

---

## Notes

- Please ask if you need clarification on any part of the task.
- You can use AI tools, but should let us know where and how they helped.
- We’re also interested in seeing how you document and showcase any additional skills, techniques, or libraries.

---

## Deliverables

- Python script to download the CSV and load it into Snowflake
- SQL queries or DBT models to:
  - Create the **Customer**, **Order**, and **OrderItem** tables
  - Create the aggregation view
- Optional: Notes showcasing any additional features or capabilities you feel are relevant
