---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Lead Data Scientist
    company: SCI99.com
    company_url: ''
    company_logo: workfusion
    location: Shandong, China
    date_start: '2022-03-31'
    date_end: ''
    description: |2-
      Built and deployed advanced LSTM and Transformer-based forecasting models, boosting prediction accuracy by 15%, with scalable deployment via RESTful API and Docker.

      Conducted extensive research on time-series forecasting frameworks, applied hyperparameter optimization (HPO), and used MLflow for experiment tracking and model performance monitoring.

      Created interactive dashboards using Tableau and Looker to deliver actionable insights; optimized BigQuery and Snowflake pipelines to reduce query runtime by 40%.

  - title: Data Scientist
    company: WorkFusion
    # company_url: ''
    company_logo: workfusion
    location: New York, NY
    date_start: '2018-03-01'
    date_end: '2021-03-01'
    description: |2-
      Led R&D projects for AutoML platform enhancements, developing machine learning models in Python and Java for business process automation.

      Improved model quality by applying linear SVM to reduce noisy data by 70%, resulting in a 5% increase in F1 score.

      Designed Japanese-language models for invoice preprocessing, enabling first market delivery in Japan with over $500,000 in revenue. 
  - title: Data Scientist
    company: Koudai.com
    # company_url: ''
    # company_logo: org-x
    location: Beijing, China
    date_start: '2015-05-01'
    date_end: '2016-07-01'
    description: Utilized data visualization, engineering, and regression techniques to address business challenges and support decision-making.

  - title: Data Analyst
    company: Amazon
    # company_url: ''
    # company_logo: org-x
    location: Beijing, China
    date_start: '2013-07-01'
    date_end: '2015-05-01'
    # description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '1'
---
