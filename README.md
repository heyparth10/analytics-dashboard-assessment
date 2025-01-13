# MapUp - Analytics Dashboard Assessment

## Overview

The objective of this assessment is to analyze the provided Electric Vehicle (EV) population data and create a frontend dashboard that visualizes key insights about the dataset. This repository contains the necessary data and instructions for you to demonstrate your analytical and dashboard creation skills. Feel free to use any tech stack you want to create the dashboard.

## Dataset

The Electric Vehicle Population dataset is available in the [Electric Vehicle Population Data (CSV)](./data-to-visualize/Electric_Vehicle_Population_Data.csv) within this repository, for more information about the dataset visit [kaggle dataset](https://www.kaggle.com/datasets/willianoliveiragibin/electric-vehicle-population).

**Note:** We've reduced the dataset in the repository to keep the data size small in the frontend bundle.

## Tasks

### Dashboard Creation:

- Create a frontend dashboard that presents key insights from the dataset.
- Design the dashboard to effectively communicate important metrics and visualizations.
- Include visual representations such as charts, graphs, or tables to showcase trends and relationships in the data.
- Ensure the dashboard is user-friendly and intuitive for exploring the dataset.

### Deployment:

- Deploy your frontend dashboard to a hosting platform of your choice.
- Make sure the dashboard is publicly accessible.

## Evaluation Criteria

Your submission will be evaluated based on:

- **Analytical Depth:** The depth of your analysis and insights derived from the dataset.
- **Dashboard Design:** Clarity, aesthetics, and usability of the frontend dashboard.
- **Insightfulness:** Effectiveness in conveying key insights about electric vehicles.

## Submission Guidelines

- Fork this repository to your GitHub account.
- Complete your analysis and create the frontend dashboard.
- Deploy the dashboard to a hosting platform.
- Update this [README.md](README.md) file with the URL to your live dashboard.
- **Repository Access:** Keep your repository private to avoid visibility by other candidates. Add the following email addresses as collaborators to the repository, these are our internal emails and will be evaluating your assessment:
  - vedantp@mapup.ai
  - ajayap@mapupa.ai
  - divyanshs@mapup.ai
- Finally, please fill out the google form that you received via email to submit the assessment for review.

##**Dataset Highlights**:
Number of Entries: 50,000
Key Features:
Electric Vehicle Type (e.g., Battery Electric Vehicle, Plug-In Hybrid)
Make and Model
Model Year
Electric Range
Base MSRP
County, City, and State
Clean Alternative Fuel Vehicle (CAFV) Eligibility
Note: The dataset has been reduced in size to ensure optimal performance in a frontend environment.

##**Exploratory Data Analysis** (EDA)
Before building the frontend dashboard, the following steps were performed as part of EDA:

Validated data types and handled null values.
Descriptive Statistics:
Summarized key metrics like the distribution of electric vehicle types, model years, and electric ranges.
Key Insights:
Most common electric vehicle type: Battery Electric Vehicle (BEV) (39,461 out of 50,000 entries).
Top counties and cities by EV adoption (e.g., Yakima County leads with Yakima City having the highest EV population).
Trends in electric vehicle affordability based on MSRP and eligibility for CAFV incentives.
Dashboard Features
The dashboard was designed to effectively communicate the insights derived from the dataset. It includes:

Visualizations:
Bar Charts: Highlight top electric vehicle makes and models.
Line Charts: Showcase the growth trend in EV adoption over the years.
Tables: Present detailed data, including ranks and counts of EVs by make and city.
User Interaction:
A Download Dataset button allows users to access the dataset directly.
An FAQ Section provides answers to common questions about EV data and trends.
Accessibility:
The dashboard is deployed and publicly accessible for easy sharing and review.
**URL**
https://ev-dashboard-rho.vercel.app/
