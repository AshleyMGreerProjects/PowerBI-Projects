# Data Careers Survey Analysis

## Overview
This report provides an in-depth analysis of data professionals' career trends, based on survey data. It includes insights into preferred programming languages, job satisfaction levels, career growth opportunities, and more.

## Report Structure

### 1. Overview Page
- **Purpose:** Provides a high-level summary of key metrics from the survey.
- **Visuals Used:** 
  - **KPI Cards:** Displaying average job satisfaction, career growth, and other key metrics.
  - **Bar Charts:** Showing the distribution of respondents across different job roles.

### 2. Programming Languages Analysis
- **Purpose:** Analyzes the programming languages preferred by data professionals.
- **Visuals Used:**
  - **Pie Chart:** Illustrates the percentage of professionals using each programming language.
  - **Bar Chart:** Breaks down language preference by job role.

### 3. Job Satisfaction
- **Purpose:** Evaluates the satisfaction levels of data professionals in their current roles.
- **Visuals Used:**
  - **Gauge Chart:** Represents overall job satisfaction.
  - **Heat Map:** Shows the correlation between job satisfaction and years of experience.

### 4. Career Growth
- **Purpose:** Examines the opportunities for career growth within the data profession.
- **Visuals Used:**
  - **Line Chart:** Tracks career growth opportunities over time.
  - **Stacked Bar Chart:** Compares career growth across different sectors.

## Data Model
- **Tables:** 
  - **Survey Responses:** Contains individual responses to the survey questions.
  - **Job Roles:** Details on the different job roles within the data profession.
  - **Programming Languages:** Lists the programming languages included in the survey.
- **Relationships:**
  - **One-to-Many:** Between `Job Roles` and `Survey Responses`.
  - **Many-to-Many:** Between `Programming Languages` and `Survey Responses`.

## Key Insights
- **Most Popular Programming Language:** Python is the most preferred programming language among data professionals.
- **Job Satisfaction:** The majority of respondents report high job satisfaction, particularly those with 5+ years of experience.
- **Career Growth:** Data professionals in the tech sector report the most significant career growth opportunities.

## Filters and Slicers
- **Filters Applied:**
  - **Date Range:** Limited to surveys conducted in the last 3 years.
  - **Job Role:** Users can filter results by specific job roles.
- **Slicers:**
  - **Programming Language:** Allows users to view data specific to one or more programming languages.

## Conclusion
The "Data Careers Survey Analysis" report provides valuable insights into the current state of the data profession. The findings highlight the importance of Python in the field, the generally high levels of job satisfaction, and the promising career growth opportunities in the tech sector.

