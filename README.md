# Data 550: Final Project - Condition Prevalence Analysis for Medi-Cal Patients in California
------------------------------------------------------------------------
## Project Description

In this project, we examine the prevalence of various chronic health conditions across different age bands. Healthcare Payments Data (HPD) Healthcare Measures is a dataset that contains data in three main categories: Health Conditions, Utilization, and Demographics.  It includes the prevalence of long-term illnesses, healthcare usage rates, and demographic information, such as age and health coverage. Furthermore, measures are grouped in various ways, including year, region, and payer type. The objectives for this analysis is to identify possible trends in health condition prevalence amongst Medi-Cal patients. This may later inform healthcare initiatives targeting age-specific health issues amongst Medi-Cal recipients.

## Goals

- Analyze and visualize the prevalence of chronic conditions by age band.
- Generate a heatmap for the prevalence across different conditions and age groups.
- Create a comprehensive report documenting the results and insights from the analysis.

## Definitions

The dataset used in this project contains information on:
- `age_band`: The age range a member falls into based on age on the last day of the reporting period.
- `measure_name`: The name of the chronic condition being assessed.
- `Prevalence`: The prevalence of the condition in the given population and age group.
- `payer_type`: Payers are the companies, programs, and organizations that oversee insurance plans and reimburse healthcare providers. The three main types of payers are Commercial, Medi-Cal, and Medicare.
- `measure_numerator`: Count of members identified as having [measure_name] during the measurement year
- `measure_denominator`: Count of members enrolled during the measurement year



## Packages

To run the project, you will need the following packages in R:

```r
install.packages(c("here", "dplyr", "ggplot2", "tidyr", "rmarkdown", "knitr"))
```
## Files

- `Code/process_data.R`: Processes the raw data and generates filtered data.
- `Code/heatmap.R`: Generates the heatmap for chronic condition prevalence by age band.
- `Code/table.R`: Creates a table with the prevalence of conditions across age bands.
- `Code/render_report.R`: Renders the final report from the RMarkdown file.
- `Final_Project_Report.Rmd`: The RMarkdown file containing the analysis report, including tables, figures, and conclusions.
- `Output/`: Folder where outputs are stored.

## Running the Project

1. Clone or download the repository to your local machine.
2. Open the RStudio project or R console and set the working directory to the root of the project.
3. Use the provided `Makefile` to automate the process

## Output

The project generates the following outputs:
- **Heatmap**: A visual representation of the prevalence of chronic conditions across different age groups.
- **Prevalence Table**: A table listing the prevalence of conditions across age bands.
- **Final Project Report**: A comprehensive HTML report that includes data analysis, tables, figures, and insights.

## Acknowledgments

- The Helathcare Payments Data Measures dataset used in this project was obtained from the Department of Health Care Access and Information

```
