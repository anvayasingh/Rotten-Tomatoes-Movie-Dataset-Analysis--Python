# Rotten Tomatoes Movie Dataset Analysis

# Project Overview
This notebook performs a complete analysis of the **Rotten Tomatoes Movies dataset** from Maven Analytics.

The goal is to:
- Explore critic vs audience ratings  
- Analyze differences across genres  
- Create visual comparisons  
- Understand patterns in review counts and ratings  

# Data Used
- `Rotten Tomatoes Movies.csv`

# Workflow Summary

# 1. Data Loading
- Imported raw movie dataset
- Selected relevant columns such as:
  - movie_title  
  - genre  
  - critic_rating / critic_count  
  - audience_rating / audience_count  
  - release_year  

# 2. Data Preparation
- Cleaned genre and rating fields  
- Created new calculated columns:
  - Rating difference  
  - Genre flags (Animation, Action & Adventure, Comedy etc.)  
- Filtered subsets for category-wise comparisons  

# 3. Exploratory Data Analysis (EDA)
Performed deep-dive into:
- Popular genres  
- Rating distributions  
- Relationship between critic & audience scores  
- Trends across categories  
- Which genre has highest engagement (count of reviews)

# 4. Genre-wise Comparisons
You analyzed:
- **Animation vs Non-Animation**
- **Action & Adventure vs Others**
- **Comedy vs Non-Comedy**

For each:
- Avg critic rating  
- Avg audience rating  
- Visual comparison using Seaborn & Matplotlib  

# 5. Visualizations
You created:
- Bar charts  
- Histograms  
- Category-wise comparison plots  
- Reviewer count distributions  

Libraries used:
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

# Key Insights
- Critics and audiences show **different positivity levels** depending on genre.
- Certain genres consistently get higher audience love than critic approval.
- Animation often has **higher average ratings** and more consistency.
