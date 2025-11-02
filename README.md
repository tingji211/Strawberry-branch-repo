# Strawberry-branch-repo

Overview

This repository contains a data analysis project examining fungicide usage patterns in U.S. strawberry production, focusing primarily on California and Florida. 
Using USDA NASS data from 2018–2023, we explore which fungicides are most prevalent, how their application rates have evolved, 
and what these trends imply for sustainable agricultural management.

Authors: Tingji Tao, Zhirui Gu, Jizhou Zhang

Main document: strawberryfungicide.qmd

Data: strawberry1024.csv 

Output File: Strawberry Fungicide Analysis.pdf

#   Project Summary
1. Data Cleaning

Original USDA dataset contained 758 rows and 21 columns.

Dropped irrelevant or empty columns (e.g., Program, County, Zip.Code, etc.).

Removed suppressed or unavailable values (D) and (NA) to keep only usable data.

Split Domain.Category and Data.Item into structured columns:
Chem_Group, Fungicide, Code, Value, Indicator, Measurement, Crop_Status.

2. Exploratory Data Analysis (EDA)

California (2023):

Sulfur dominates with ~40 lb/acre/year.

Captan and Thiram follow (~10–15 lb/acre/year).

Florida (2023):

Captan and Thiram are most intensively used.

Coverage levels exceed 80% of the bearing area for most major fungicides.

3. Trends (2018–2023)

California: Sharp increase in Sulfur usage; steady growth in Captan and Thiram.

Florida: Rising Captan and Thiram until 2021, then gradual decline — suggesting adaptive chemical management practices.

4. Key Findings

Captan, Sulfur, and Thiram form the core fungicide trio across both states.

Application intensity reflects regional strategies responding to pest pressure and environmental shifts.

Emphasis on balancing chemical control with sustainability to prevent resistance buildup.