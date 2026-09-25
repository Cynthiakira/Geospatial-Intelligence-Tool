# Geospatial-Intelligence-Tool
Overview
This project explores how spatial data can be combined with AI-powered web search to gather market information. The workflow starts with selected towns from a GeoJSON file, searches for land price information, and builds a simple market dataset for analysis.

Files Included
1. sprint2_spatial_questions_to_market_data.py
The Python script that powers the workflow. It:
Loads and validates town data from a GeoJSON file.
Extracts town names automatically.
Uses SerpApi and Google AI Overview to search for land price information.
Processes search results and extracts land price estimates.
Creates a structured market dataset.
Exports results as CSV and JSON files.

2. sprint2_spatial_questions_to_market_data.ipynb
The Jupyter Notebook version of the project. It provides a step-by-step, interactive environment where users can:
Upload and inspect GeoJSON files.
Run searches for market information.
Review AI-generated results.
Build and export datasets.
Experiment with different search questions.

3. market_dataset.csv
The final output dataset generated from the workflow. It contains:
Town names
Estimated land prices per square metre
Supporting sources
Search dates

This file serves as a quick reference for comparing land market information across selected towns.


The goal of this project is not to build an AI model, but to understand how spatial data and AI-assisted search can be combined to answer real-world market questions and create useful datasets for further analysis.

Tools Used
Python
Pandas
SerpApi
Google AI Overview
Jupyter Notebook
