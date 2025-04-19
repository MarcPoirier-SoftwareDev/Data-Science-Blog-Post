# Data Science Blog Post: Analyzing Stack Overflow Developer Survey Trends (2017–2024)

## Overview

This project analyzes trends in the Stack Overflow Developer Surveys from 2017 to 2024 to uncover insights into the evolving landscape of software development. The analysis focuses on four key questions related to learning methods, programming language popularity, AI adoption, and challenges with AI tools. The project follows the CRISP-DM process and is implemented in a Jupyter Notebook.

---

## Libraries Used

The following Python libraries are used in this project:

- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static, interactive, and animated visualizations.
- **Seaborn**: For statistical data visualization, built on top of Matplotlib.
- **NumPy**: For numerical operations and handling arrays.
- **Scikit-learn**: For data preprocessing and machine learning utilities (used in potential modeling).
- **Textwrap**: For wrapping text in titles and labels for better readability.
- **OS**: For interacting with the operating system, particularly for file and directory operations.

---

## Motivation

The motivation for this project is to provide data-driven insights into trends impacting software developers, educators, and tech industry stakeholders. By examining multi-year survey data from Stack Overflow, the project aims to:

- Understand how developers’ learning methods have evolved, informing educational strategies.
- Track programming language popularity to guide skill development and hiring decisions.
- Assess AI adoption across demographics to identify barriers and opportunities.
- Highlight challenges with AI tools to inform product development and user support.

---

## Files in the Repository

- **`Stack-overflow-developper-survey/`**: Directory containing subfolders for each year’s survey data (2017–2024). Each subfolder includes:
  - `survey_results_public.csv`: The main survey response data.
  - `survey_results_schema.csv`: The schema describing the survey questions.

- **`data_science_notebook.ipynb`**: Jupyter Notebook containing the full analysis—data loading, cleaning, analysis, and visualization—structured per the CRISP-DM process with clear documentation.

- **`data_science_blog_post.pdf`**: PDF containing a blog post which uncovers fascinating trends in the world of software developpers based on Stack Overflow's annual surveys from 2017 to 2024.

- **`README.md`**: This file, offering an overview of the project, its motivation, files, results, and acknowledgements.

---

## Summary of Analysis Results

The analysis addresses four key questions, supported by visualizations and statistics:

### 1. How Have Learning Methods Changed Over Time?
- **Insight**: Online resources have grown in popularity, indicating a shift toward self-directed learning, though traditional methods like school and on-the-job training persist.
- **Visualization**: Line chart showing the proportion of respondents using top learning methods (2021–2024).

### 2. How Has Programming Language Popularity Evolved?
- **Insight**: Python’s popularity has surged, especially in data science and AI, while JavaScript remains dominant in web development. C++ and C hold steady in systems programming.
- **Visualization**: Line chart tracking the percentage of respondents using key languages (2017–2024).

### 3. How Does AI Adoption Vary by Age Group in 2024?
- **Insight**: Younger developers (18–34) show higher AI tool adoption, reflecting greater openness among early-career professionals.
- **Visualization**: Stacked bar chart displaying AI adoption rates across age groups in 2024.

### 4. What Are the Biggest Challenges with AI Tools?
- **Insight**: Lack of trust in AI outputs and accuracy concerns are prevalent, pointing to areas for improvement in AI tools.
- **Visualization**: Pie charts showing the percentage of respondents selecting each challenge in 2024.

These findings offer actionable insights for educators, developers, and tech companies.

---

## Acknowledgements

- **Data Source**: The Stack Overflow Developer Surveys, publicly available, provide a rich dataset on the global developer community.
