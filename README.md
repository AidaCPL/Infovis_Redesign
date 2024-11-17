# Infovis Redesign Project

## Introduction

This repository contains the code and dataset for the redesign of a visualization from the academic article “Understanding and Combatting Misinformation Across 16 Countries on Six Continents”(Arechar et al., 2023). This project was completed as part of the **INFOSCI 301 - Data Visualization and Information Aesthetics** course. The primary goal of this project was to critically evaluate the original static visualization using both human judgment and feedback from a Large Language Model (LLM), specifically ChatGPT, and to implement a redesigned version that enhances its clarity, accessibility, and interactivity.

The original visualization compared perceived accuracy ratings of true and false headlines across 16 countries, using a static bar chart. While effective in showing basic patterns, it faced issues with readability, accessibility, and interactivity. Guided by principles from *Visualization Analysis and Design* by Tamara Munzner, this project aimed to refine the visualization while maintaining its integrity, as I believe the authors’ initial design choices were carefully thought out and appropriate for their dataset.

### Objectives and Approach

The redesign focused on improving the visualization without introducing unnecessary elements that could distract from its core purpose. Following Munzner’s Chapter 6 guidance that “simplicity isn’t always bad,” the redesigned chart avoided overly complex features like 3D effects or excessive colors, which could compromise clarity. Instead, enhancements such as side-by-side bar grouping, shaded confidence intervals, and interactive features (region-based filtering, tooltips, and annotations) were added to make the visualization more user-friendly.

### Repository Contents

This repository includes:
1. [Code](Code/Infovis_Redesgin_Project_code.ipynb): Python scripts using libraries like Plotly for the redesigned visualization.
2. [Dataset](Data/CR.csv): The original data retreived from the Arechar, et.al, paper.
3. [Final Report](Documentation/README.md): Clear descriptions of the steps taken during redesign, including data transformations and visualization enhancements.

### How to Use This Repository

1. **Run the Code**: The Python notebook provided can be run in Google Colab or locally using Jupyter Notebook. It is designed to be reproducible, with data transformations clearly documented.
2. **Explore the Visualization**: The redesigned chart includes interactive features like hover-over tooltips and a dropdown filter for regions.
3. **Learn from the Process**: The repository includes reflections on the role of LLMs in assisting the critique and redesign process, highlighting both their utility and where human expertise was essential.

This project demonstrates how critical evaluation and iterative refinement can transform a static chart into a dynamic, accessible visualization, bridging the gap between academic rigor and practical usability.
