MOOC Learner Engagement Analysis
This repository contains an analysis of learner engagement on a Massive Open Online Course (MOOC) platform over a five-year period, using the CRISP-DM methodology. The goal is to uncover trends in geographic engagement, device usage, and content completion rates, and identify areas for improving learner experience and retention.

Project Overview
This analysis explores:

Engagement by geographic region
Device type trends
Completion rates and video consumption patterns
Data visualizations—such as bar plots, line graphs, heatmaps, and bubble charts—highlight how engagement patterns vary across time and regions, informing strategies to enhance engagement.

Data and Prerequisites

Data Source: Five-year learner engagement data from FutureLearn, including video views, device types, and geographic details.
Requirements: R Studio with the ProjectTemplate library. Required packages are specified in the configuration.
Installation
Clone the Repository:
bash
Copy code
git clone https://github.com/jimm29sc/University-Wok.git
Navigate to the Directory:
bash
Copy code
cd University-Wok
Load the Project in R Studio: Run the following lines in R to load the project environment:
R
Copy code
library('ProjectTemplate')
load.project()
Usage

Prepare Data: Ensure all data is cleaned, standardized, and includes identifiers for each year to support trend analysis.

Run Analysis:
Each script in src runs a specific part of the analysis, generating visualizations saved in output/visualizations.
Data Preparation: Process and clean data with data_preparation.R.
Visualization: Generate visuals by running analysis_script.R.
Interpret Results:
Regional Distribution: Bar chart displaying engagement by region.
Video Completion: Line plots showing viewer drop-off rates.
Device Usage: Heatmaps and bubble charts identifying trends by device.
Results and Insights
Results are stored in the output folder. Key findings include regional and device-based engagement patterns and trends in completion rates, supporting strategies for optimizing content and engagement.

This README outlines setup, running analysis, and interpreting results. Enjoy exploring the insights from the MOOC Learner Engagement Analysis!








