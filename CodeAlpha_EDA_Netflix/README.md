Netflix Data Analysis Project

📊 Overview
This project performs an Exploratory Data Analysis (EDA) on Netflix's content dataset to uncover insights about their movie and TV show offerings. The analysis helps understand content distribution patterns, trends in release years, and director availability across different content types.

🎯 Key Objectives
Analyze Netflix's content library composition

Identify trends in content release years

Compare Movies vs TV Shows distribution

Examine director availability and top contributors

Handle data quality issues through preprocessing

📁 Dataset Information
File: netflix_titles.csv

Records: 8,807 rows × 12 columns

Source: Netflix publicly available dataset

Dataset Columns:
show_id

type (Movie/TV Show)

title

director

cast

country

date_added

release_year

rating

duration

listed_in (genres)

description

🔧 Data Preprocessing
Missing Value Handling:
Director: 2,634 missing → filled with "unknown"

Country: 831 missing → filled with "not available"

Cast: 825 missing → filled with "not available"

Rating: 4 missing → filled with "not rated"

date_added: 10 missing → filled with "not available"

duration: 3 missing → filled with "not available"

📈 Key Findings
1. Content Distribution
Movies: 6,131 (69.6%)

TV Shows: 2,676 (30.4%)

Netflix has significantly more movie content than TV shows

2. Release Year Trends
Range: 1925 to 2021

Mean Release Year: 2014.18

Median: 2017

Insight: Content production increased dramatically post-2015

3. Director Analysis
Top 10 Directors by Content Count:

unknown (2,634)

Rajiv Chilaka (19)

Raúl Campos, Jan Suter (18)

Suhas Kadav (16)

Marcus Raboy (16)

Jay Karas (14)

Cathy Garcia-Molina (13)

Martin Scorsese (12)

Youssef Chahine (12)

Jay Chapman (12)

Movies vs TV Shows Director Availability:

Movies: 6,131 (94.6% of total)

TV Shows: 267 (5.4% of total)

Movies have a much wider pool of directors compared to TV shows

📊 Visualizations
1. Release Year Distribution (Histogram)
Shows exponential growth in content creation after 2015

Very few titles released before 2000

2. Director Availability by Content Type (Bar Chart)
Clear visualization of director concentration in movies

Suggests TV shows rely on a smaller group of directors

🛠️ Technical Stack
Python Libraries:

pandas (Data manipulation)

numpy (Numerical operations)

matplotlib (Basic plotting)

seaborn (Advanced visualizations)

💡 Business Insights
Strategic Implications:
Content Strategy: Netflix's focus is predominantly on movies

Production Trends: Significant ramp-up in content creation post-2015

Director Relationships: Movies engage a broader director network

International Presence: Multiple countries represented in production

Recommendations:
TV Show Expansion: Opportunity to diversify TV show offerings

Director Relationships: Could strengthen TV show director networks

Content Acquisition: Consider balancing movie/TV show ratio

Market Analysis: Further analysis of country-specific trends


