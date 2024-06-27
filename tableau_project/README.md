# Tableau Data Analysis Project - European Profitability Insights

## Project Overview:
This project showcases various data analysis and visualisation techniques applied to a dataset of 4,000+ product sales across Europe. 

[Link to Tableau Public Interative Dashboard](https://public.tableau.com/app/profile/sonali.tejura/viz/EuropeanProfitabilityInsightsTechnologyOfficeSuppliesandFurniture/EuropeanProfitabilityInsightsTechnologyOfficeSuppliesandFurniture?publish=yes) 

## Project Aims:
Deliver actionable insights into sales performance, customer behaviour and profitability. 

## Data Analysis and Dashboard Development

- **Data Preparation**: Employing advanced techniques such as table joins and calculated fields for comprehensive analysis.

- **Dashboard Design**: Developed an interactive dashboard to deliver actionable insights on sales and profitability metrics.

  - **Geographical Analysis**: Created a dynamic map for swift identification of top-performing regions.
  
  - **Customer Insights**: Utilised a scatter plot to identify high-value customers for targeted marketing efforts.
  
  - **Product Performance**: Designed a treemap visualisation to showcase product popularity and profitability trends/
  
  - **Time-Based Analysis**: Integrated a yearly filter, allowing users to explore and analyse time-based trends.
  
  - **Interactive Features**: Implemented an actionable filter, for dynamic updates based on user interaction/

![Dashboard](https://github.com/sonalitejura/portfolio-projects/assets/172199569/5470760b-2d06-4eca-aa64-78e4916be264)


# Dashboard Setup Steps

1. **Geographical Mapping**
   - Created a 'Geography' hierarchy with Country, City and State.
   - Set granularity to 'State' for detailed regional analysis.
![Geography](https://github.com/sonalitejura/portfolio-projects/assets/172199569/5b917125-9727-4bea-8449-2a9072db8b9d)

2. **Year Filter**
   - Created a filter for 'Year' formatted as a single-value slider.

3. **Sales Visualization**
   - Moved 'Sales' to 'size' to visually compare sales volumes across regions (larger dots represent higher sales).
![Sales](https://github.com/sonalitejura/portfolio-projects/assets/172199569/df22f986-d0a6-44e3-955c-056caaa1f65c)

4. **Profit Margin Analysis**
   - Calculated profit margin using a calculated field.
   - Assigned profit margin to 'colour' for visual differentiation (each colour represents a different profit margin range).
![calculated_field](https://github.com/sonalitejura/portfolio-projects/assets/172199569/46d749c7-ac7f-4881-8f8c-6e9ee190bba5)

![profit_to_colour](https://github.com/sonalitejura/portfolio-projects/assets/172199569/94c69dd3-7809-44c7-8f2d-86f0057b49d2)

5. **Customer vs. Profit Scatter Plot**
   - Created a scatter plot to analyse customer segments against profit.
   - Applied the 'Year' filter to the scatter plot for temporal insights.
![scatter](https://github.com/sonalitejura/portfolio-projects/assets/172199569/6a6f3d8b-8d00-4669-885b-164b8ed44bce)

6. **Scatter Plot Formatting**
   - Adjusted settings:
     - Mapped profit margin to colour for visual distinction.
     - Changed color scheme to red-blue, shape to circle and increased circle size.
     - Set transparency to 75% to manage overlapping circles.

7. **Product Analysis**
   - Created a treemap to visualise product popularity and profitability.
   - Incorporated the 'Year' filter to track yearly trends.

8. **Performance Metrics**
   - Calculated:
     - Highest sales region.
     - Top-selling products.
     - Average profit margin.

9. **Dashboard Creation**
   - Developed the dashboard layout.
   - Integrated an actionable filter for enhanced user interaction.
   - Formatted the dashboard for clarity and usability.

## Conclusion
This project demonstrates data analysis techniques visualisations to drive business insights and informed decision making. 
