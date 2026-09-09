# Operation Next Nest 🏡

**Operation Next Nest** is a hands-on analytics project that uses real public data to help answer a very practical question:

> **Where should my family live near the SAS campus in Cary, North Carolina?**

Along the way, we’ll play **data detective** — combining demographic, housing, commute, and amenity data to identify neighborhoods that best match a family's priorities.

## What You'll Do

This project demonstrates a complete analytics workflow using multiple programming languages inside **SAS Viya Workbench for Learners**:

* **Python — Data Engineering**
  Collect, clean, combine, and enrich neighborhood-level data from sources including the U.S. Census Bureau and OpenStreetMap.

* **SAS — Scoring and Selection**
  Create a weighted scoring system, apply family preferences and constraints, and identify neighborhoods with the strongest overall fit.

* **R — Mapping and Visualization**
  Build interactive maps to compare selected neighborhoods across different family-priority scenarios.

The result is a **polyglot data science workflow** in which Python, SAS, and R each handle a different part of the analytics lifecycle.

## The Question

Finding the “best” neighborhood is not simply a matter of finding the cheapest house or the shortest commute.

Instead, we’ll consider trade-offs among factors such as:

* Commute time to the SAS campus
* Housing costs
* Household income
* Families with young children
* Parks
* Grocery stores
* Bike trails
* Other neighborhood characteristics

We’ll then explore how the recommended neighborhoods change when our priorities change.

## Project Workflow

### 1. Python — Build the Data

Create the analytical dataset using:

* American Community Survey (ACS) data
* Census TIGER/Line geographic boundaries
* OpenStreetMap amenities
* Geographic calculations for distance and estimated commute time

### 2. SAS — Compare Neighborhood Scenarios

Use SAS to create neighborhood scores and evaluate several scenarios, such as:

* **Base**
* **Commute First**
* **Kid Friendly**
* **Amenity Heavy**

Each scenario changes the relative importance of the factors used to evaluate neighborhoods.

### 3. R — Map the Results

Use R and Leaflet to visualize:

* Selected neighborhoods
* The SAS campus
* Differences across scenarios
* Neighborhoods that consistently perform well

### 4. Student Mini-Project — Make It Your Own

After completing the guided workflow, extend the project through a student mini-project.

You might change:

* The research question
* The geography
* The data sources
* The decision criteria
* The weighting strategy
* The analytical approach
* The final visualization or communication format

The goal is to move from following an existing workflow to designing and defending your own analytical approach.

## Repository Structure

Work through the notebooks in order:

1. **`01 - OperationNextNest - Data Engineering in Python.ipynb`**
   Build and enrich the neighborhood-level analytical dataset using Census, geographic, commute, and amenity data.

2. **`02 - OperationNextNest - PROC OPTMODEL in SAS.sasnb`**
   Use SAS to create weighted neighborhood scores, apply constraints, and compare different family-priority scenarios.

3. **`03 - OperationNextNest - Neighborhood Mapping in R.ipynb`**
   Visualize the selected neighborhoods in R using interactive maps and compare results across scenarios.

4. **`04 - Student Mini-Project Details.ipynb`**
   **Take the next step.** Use the Operation Next Nest workflow as a starting point for your own mini-project by changing the question, geography, data, priorities, or analytical approach.

## Getting Started

This project is designed to run in **SAS Viya Workbench for Learners**.

From a terminal in your Workbench, clone this repository:

```bash
git clone https://github.com/lincolngroves/OperationNextNest.git
```

Then open the `OperationNextNest` folder and work through the notebooks in order.

## What You'll Learn

By completing Operation Next Nest, you'll practice how to:

* Combine data from multiple public sources
* Work with geographic and demographic data
* Engineer analytical features
* Translate real-world preferences into measurable criteria
* Compare competing decision scenarios
* Move data between Python, SAS, and R
* Communicate analytical results through maps and visualizations
* Extend a guided workflow into an independent analytical project

Most importantly, you'll see how analytics can help structure a real decision when there is **no single perfect answer**.

## About the Project

Operation Next Nest was developed as a teaching example for **SAS Viya Workbench for Learners** and the broader idea of the **polyglot data scientist** — choosing the right language or tool for each part of the analytical problem.

After completing the three-part Operation Next Nest workflow, continue to **Notebook 04: Student Mini-Project Details** to extend the analysis and make the project your own.
