# Tableau Data Analysis Project - European Profitability Insights

## Project Overview
This project showcases data analysis and visualisation techniques applied to a dataset of 4,000+ product sales across Europe. 

[Link to Tableau Public Interative Dashboard](https://public.tableau.com/app/profile/sonali.tejura/viz/EuropeanProfitabilityInsights/EuropeanProfitabilityInsightsTechnologyOfficeSuppliesandFurniture?publish=yes)
- To optimally view the dashboard, navigate to the 'See this in full screen' button located on the bottom right corner of the dashboard.
- ![full_screen](https://github.com/sonalitejura/portfolio-projects/assets/172199569/0d71818d-c7ea-4062-be17-ebc63dc19571)

## Project Aims
1. Deliver actionable insights into sales performance and identify key trends.
2. Evaluate how sales performance compares to target sales.
3. Analyse customer behavior to understand purchasing patterns and preferences.

## Project Highlights
- **Data Preparation**: Employed advanced techniques such as table joins, calculated fields and data blending for comprehensive analysis.

- **Dashboard Design**: Developed an interactive dashboard to deliver actionable insights on sales and profitability metrics.

  - **Geographical Analysis**: Created a dynamic map for swift identification of top-performing regions.
  
  - **Customer Insights**: Utilised a scatter plot to identify high-value customers for targeted marketing efforts.
  
  - **Sales Performance**: Designed a dual-axis chart to evaluate actual sales vs the target sales.
  
  - **Time-Based Analysis**: Integrated a yearly filter to allow users to explore and analyse time-based trends.
  
  - **Interactive Features**: Implemented an actionable filter for dynamic updates based on user interaction.


## Dashboard Setup Steps

1. **Geographical Mapping**
   - Created a 'Geography' hierarchy with Country, City and State.
   - Set granularity to 'State' for detailed regional analysis.
![Geography](https://github.com/sonalitejura/portfolio-projects/assets/172199569/5b917125-9727-4bea-8449-2a9072db8b9d)

2. **Year Filter**
   - Created a filter for 'Year' formatted as a single-value slider.

3. **Sales Visualisation**
   - Moved 'Sales' to 'Size' to visually compare sales volumes across regions (larger dots represent higher sales).
![Sales](https://github.com/sonalitejura/portfolio-projects/assets/172199569/df22f986-d0a6-44e3-955c-056caaa1f65c)

4. **Profit Margin Analysis**
   - Calculated profit margin using a calculated field.
   - Assigned profit margin to 'colour' for visual differentiation (each colour represents a different profit margin range).
![Picture 1](https://github.com/sonalitejura/portfolio-projects/assets/172199569/416c7ac1-35ff-4ac8-81a9-ef58ad9ae513)
  ![profit_to_colour](https://github.com/sonalitejura/portfolio-projects/assets/172199569/94c69dd3-7809-44c7-8f2d-86f0057b49d2)

5. **Customer vs. Profit Scatter Plot**
   - Created a scatter plot to analyse customer purchases against profit.
   - Applied the 'Year' filter to the scatter plot for temporal insights.
![scatter](https://github.com/sonalitejura/portfolio-projects/assets/172199569/6a6f3d8b-8d00-4669-885b-164b8ed44bce)

6. **Scatter Plot Formatting**
   - Mapped profit margin to colour for visual distinction.
   - Changed colour scheme to red-blue, shape to circle and increased circle size.
   - Set transparency to 75% to manage overlapping circles.
![formatted_scatter](https://github.com/sonalitejura/portfolio-projects/assets/172199569/22779cc5-5813-4a02-9807-548729e2c86e)

7. **Sales Performance Analysis**
- Created a new data source for 'Sales Target'
    - Mapped ‘Sales’ data to rows and created a bar chart.
    - Assigned 'categories' to rows and mapped it to colour for comparative analysis.
     ![Picture1](https://github.com/sonalitejura/portfolio-projects/assets/172199569/fc6a3902-3948-450d-92c4-22cf184bf6b0)

- Utilised data blending to create a dual-axis chart for sales performance
  - Moved 'Target' data to rows, enabling direct comparison with sales figures.
  - Transformed the visualisation into an area chart to easily identify trends.
  - Created a dual-axis chart with a synchornised axis, facilitating seamless comparisons of sales and targets.
  ![Picture2](https://github.com/sonalitejura/portfolio-projects/assets/172199569/42cfa4cb-6361-4943-8c32-a20cc0c898a1)
  ![Picture3](https://github.com/sonalitejura/portfolio-projects/assets/172199569/c16a81e6-fc73-4ae6-a61c-d12f53dc514a)


- Created a calculated field to illustrate the difference between actual sales and sales target.
  - Simplified the existing chart by implementing 'category' data as filter
  - Created a calculated field called 'Excess of Target'
  - Formatted the chart - changed the colour scheme to red-blue, changed the font size and made the text bold.
![Picture4](https://github.com/sonalitejura/portfolio-projects/assets/172199569/c23c74b0-41e9-4c7a-8500-71e5f029bb50)
![Picture5](https://github.com/sonalitejura/portfolio-projects/assets/172199569/5069455b-20af-4c1f-bf4d-083fd955d777)
    
9. **Dashboard Creation**
   - Developed the dashboard layout.
   - Integrated an actionable filter for enhanced user interaction.
   - Formatted the dashboard for clarity and usability.
![Picture6](https://github.com/sonalitejura/portfolio-projects/assets/172199569/913a1688-d95e-48b4-b611-99a61b1c9eeb)

## Conclusion
This project demonstrates data analysis techniques and visualisations to drive business insights and informed decision making. 
