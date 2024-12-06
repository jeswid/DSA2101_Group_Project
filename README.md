# San Francisco Rental Prices Analysis

This repository contains an analysis of San Francisco rental prices using data from the [TidyTuesday project (2022-07-05)](https://github.com/rfordatascience/tidytuesday/blob/main/data/2022/2022-07-05/readme.md). The analysis examines rental trends and insights into housing availability, pricing, and affordability across neighborhoods in San Francisco.

## Project Structure

- **`Final_Report.html`**: The rendered report detailing the findings of the analysis, including visualizations and insights.
- **`Final_Report.Rmd`**: The R Markdown source file used to generate the HTML report.

## Key Features

1. **Exploratory Data Analysis (EDA)**:
   - Overview of rental price distributions by neighborhood.
   - Time series analysis of rental trends.

2. **Visualizations**:
   - Graphs depicting rental price variations.
   - Neighborhood-specific insights into affordability.

3. **Insights**:
   - Highlights the impact of housing availability on rental prices.
   - Discussion on affordability challenges faced by residents.

## Data Source

The data used in this project originates from the [TidyTuesday 2022-07-05 dataset](https://github.com/rfordatascience/tidytuesday/blob/main/data/2022/2022-07-05/readme.md). It includes detailed rental price information and other housing-related variables for San Francisco.

## Requirements

### R Packages
The analysis requires the following R packages:
- `tidyverse`
- `ggplot2`
- `dplyr`
- `rmarkdown`

### Installation
Install the required packages using:
```r
install.packages(c("tidyverse", "ggplot2", "dplyr", "rmarkdown"))

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sf-rental-analysis.git
   cd sf-rental-analysis
  ```

2. Open the `Final_Report.Rmd` file in RStudio.
3. Install the required R packages (if not already installed)
4. Knit the R Markdown file to generate the HTML report:
   ```r
   rmarkdown::render("Final_Report.Rmd")
   ```
5. Explore the generated `Final_Report.html` for insights.

## Contributors  
1. Jessica Widyawati - [jessicawidyawati@gmail.com](mailto:jessicawidyawati@gmail.com)  
2. Kwek Wan Ting
3. Leong Yao Heng
4. Charles Goek Cher Jun
5. Ryan Toh Jun Hui 
