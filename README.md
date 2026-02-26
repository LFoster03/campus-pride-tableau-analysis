# LGBTQ Inclusion in U.S. Higher Education: A Tableau Analysis

## Project Overview

This project analyzes LGBTQ inclusion across colleges and universities in the United States using Campus Pride Index ratings and state-level policy data. The goal was to identify patterns in institutional inclusion based on campus characteristics such as degree offerings, community type, minority-serving status, enrollment size, and public vs. private control.

Using Tableau, interactive dashboards and storyboards were created to explore how institutional and geographic factors relate to LGBTQ inclusion ratings.

**Interactive Tableau Public Dashboard:**
[https://public.tableau.com/](https://public.tableau.com/views/Foster_Final_CampusPrideIndexRating/DataStoryGuide?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Data Sources

**Primary dataset:**
Campus Pride Index — national benchmarking tool measuring LGBTQ-inclusive policies, programs, and practices at colleges and universities.

**Additional dataset:**
Municipal Equality Index (MEI) / State-level LGBTQ policy tally, measuring statewide legal protections and policies affecting LGBTQ individuals.

**Domain:** Higher education, LGBTQ inclusion, and institutional policy analysis.

**Dataset contents included:**

Campus-level variables:

* Campus name
* State and location
* Pride Index rating (1–5 stars)
* Enrollment (number of students)
* Public vs. private status
* Community type (urban, suburban, rural, etc.)
* Degree levels offered
* Minority-serving institution indicators (HBCU, Hispanic-serving, AAPI-serving, etc.)

State-level variables:

* State abbreviation
* State LGBTQ policy tally score

Approximate dataset size:

* ~238 campuses
* Multiple institutional and geographic attributes

---

## Data Cleaning and Preparation

Several cleaning and transformation steps were performed:

* Split campus location fields to extract state abbreviations
* Joined campus-level data with state-level policy data using state abbreviation
* Created calculated fields for:

  * Degree level count and category
  * Minority-serving classification
  * Average ratings by category
* Handled missing values by categorizing unknown degree levels separately
* Verified enrollment values and institutional classifications
* Structured the dataset for Tableau geographic and categorical analysis

---

## Tools Used

**Tableau Public**
Primary visualization tool used to create interactive dashboards and storyboards
https://public.tableau.com/

**Microsoft Excel**
Used for initial data cleaning and joining

**GitHub**
Used to host project files and documentation
https://github.com/

---

## Visualizations and Key Insights

### Goal 1: State Policy Environment vs. Campus Inclusion

A choropleth map compared campus Pride Index ratings with state-level LGBTQ policy scores. Many campuses maintain high inclusion ratings even in states with fewer legal protections, suggesting institutional policies may operate independently from state law.

### Goal 2: Degree Level and Inclusion Ratings

Box plots showed that doctoral and baccalaureate institutions generally have higher and more consistent inclusion ratings, while community colleges show slightly lower and more variable ratings.

### Goal 3: Minority-Serving Institutions

Bar charts showed minority-serving campuses have inclusion ratings comparable to or slightly higher than non-minority-serving campuses, demonstrating strong LGBTQ support across diverse institutional missions.

### Goal 4: Community Type and Inclusion

A lollipop chart showed campuses in large urban areas have the highest average ratings, while rural and very small town campuses have slightly lower averages.

### Goal 5: Public vs. Private Institutions

Treemap visualizations showed public institutions tend to have more consistently high inclusion ratings, while private institutions display greater variability.

### Goal 6: Enrollment Size and Inclusion

A quadrant scatter plot showed that both small and large campuses can achieve high inclusion ratings. Public campuses tend to maintain strong ratings even with large student populations.

---

## Conclusions

Overall, LGBTQ inclusion is strong across many U.S. colleges and universities, regardless of institutional size or location. Doctoral institutions, urban campuses, and public universities tend to show the most consistent inclusion ratings. Minority-serving institutions perform equally well compared to other campuses, demonstrating strong inclusive environments across diverse student populations.

While many campuses show strong performance, smaller and rural institutions display greater variability, suggesting opportunities for targeted inclusion initiatives.

These findings highlight the importance of institutional leadership and policy in fostering inclusive campus environments, independent of broader state-level protections.

---

## Repository Contents

* campus_pride_analysis.twbx — Tableau packaged workbook
* cleaned_dataset.xlsx — cleaned dataset used for analysis (optional)
* screenshots/ — dashboard screenshots (optional)
* README.md — project documentation

---

## Author

Lindsay Foster
Data Analytics and Visualization Project
Tableau Public | GitHub Portfolio

