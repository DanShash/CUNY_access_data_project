# Mapping Accessibility of Public Services Near CUNY Campuses

This project explores the spatial relationship between City University of New York (CUNY) campuses and NYC Benefits Access Centers using open datasets and geospatial analysis.

The goal was to assess how geographically accessible public service centers are to students, supported by data visualization and a bonus machine learning model for borough classification.

## 🔍 Project Highlights

- Merged and cleaned two public datasets using geolocation
- Calculated distances between CUNY campuses and the nearest access centers
- Visualized findings with bar charts, histograms, and an interactive map
- Built a PyTorch model to classify boroughs based on spatial features
- Documented the full process in a formal technical report

## 📄 Full Report

The complete methodology, analysis, and findings are documented in the PDF report:

👉 To View the full report (PDF) go to Report_paper_folder/Project_Report_paper.pdf and open the pdf file.

## 🗂️ Notebooks & Visuals

- Run the main notebook (`.ipynb`) to view data wrangling, analysis, and modeling steps
- Open the `.html` map file locally to explore the interactive map
- Additional charts and model results are included as `.png` images


## 🔄 Extended Analysis Part 2 ( Can be Viewed in Code-Notebook/cuny_benefits_part2_extended_analysis.ipynb)

As a second phase of this project, additional analyses were performed using new
techniques covered in a Data Management II course. This extension focuses on
extracting deeper insights from the existing datasets rather than introducing
new data sources.

### ✨ New Techniques Applied

- **Regular Expressions (Regex):**  
  Unstructured text from access center descriptions was processed using regex to
  identify service characteristics such as child-related services and limited
  in-person operations. This allowed the conversion of free-text fields into
  structured analytical features.

- **Pivot Tables:**  
  Borough-level pivot tables were created to aggregate service characteristics,
  enabling comparisons across NYC boroughs beyond individual locations.

- **Data Visualization:**  
  New bar charts were introduced to visually compare the number of access centers
  and service features by borough, making disparities easier to interpret.

- **Prompt Engineering (Conceptual):**  
  Structured prompt templates were designed to demonstrate how automated,
  data-grounded summaries of analytical results could be generated, without
  relying on external APIs or deployed language models.

### 📊 New Questions Addressed

- How do service characteristics vary across NYC boroughs?
- Which boroughs have higher concentrations of child-related services?
- Where are limited in-person service models more prevalent?
- How does service availability differ even when geographic proximity appears similar?

This extended analysis adds a service-level and borough-level perspective to the
original proximity-focused study, demonstrating how additional data management
techniques can enhance and deepen existing analyses.

## 📬 Contact

Created by Daniels S.  
*Data Science student and aspiring Quant/ML Engineer
