# 🏨 Hotel Bookings Data Analysis (R Project)

## 📌 Project Overview
This mini project analyzes hotel booking behavior using R. The objective is to understand booking patterns across hotel types by examining lead time,
market segments, and customer characteristics. The project demonstrates data cleaning, transformation, visualization, and reporting using tidyverse tools and R Markdown.


## 🎯 Objectives
- Analyze lead time differences between city and resort hotels  
- Explore booking behavior across market segments  
- Visualize relationships between lead time and number of children  
- Practice reproducible analysis using R Markdown  


## 🧰 Tools & Packages Used
- **R**
- **tidyverse**
- **ggplot2**
- **dplyr**
- **skimr**
- **janitor**
- **lubridate**
- **R Markdown**


## 📂 Dataset
- **Source:** Hotel Bookings Dataset  
- **Format:** CSV (`hotel_bookings.csv`)  
- **Description:** Contains booking information such as hotel type, lead time, market segment, number of children, and arrival year.


## 🔄 Project Workflow
1. Import and inspect data  
2. Clean column names and select relevant variables  
3. Transform data by creating new variables  
4. Perform summary analysis using group_by and summarize  
5. Create visualizations using ggplot2  
6. Document and export analysis using R Markdown  


##  Key Visualizations
- Lead Time vs Number of Children (faceted by hotel type)  
- Market Segment Distribution by Hotel Type  


##  Key Insights
- City hotels generally receive bookings earlier than resort hotels  
- Market segment distribution varies significantly by hotel type  
- Visualization reveals patterns not obvious from summary statistics  


##  How to Run This Project
1. Clone the repository  
2. Open the `.Rmd` file in RStudio  
3. Ensure `hotel_bookings.csv` is in the project directory  
4. Install required packages (first time only)  
5. Click **Knit** to generate the HTML report  


## Project Files
- `hotel_bookings_analysis.Rmd` – Main analysis report  
- `hotel_booking_analysis.html` – Rendered HTML output  
- `hotel_bookings.csv` – Dataset  
- `README.md` – Project documentation  

##  Author
**Heba Fatima**  
MBA (Hospital Administration)
FMSR, AMU

##  Why This Project Matters
This project demonstrates practical skills in data cleaning, transformation, visualization, and reproducible reporting using
R—key competencies for data analyst and healthcare analytics roles.
