# ECON 3916 Midterm Project

## Research Question

How is the share of adults aged 25 or older with a bachelor's degree or higher related to median household income across U.S. counties?

## Data Source

The data come from the U.S. Census Bureau's 2024 ACS 5-Year Data Profiles.

Source: https://api.census.gov/data/2024/acs/acs5/profile.html

The final dataset contains 3,143 counties and county equivalents after excluding Puerto Rico and one missing income value.

## How to Run

Open `midterm_starter.ipynb` in Google Colab and run all cells in order. The notebook reads the CSV file from the `data` folder on GitHub. No API key is needed.

## Main Finding

Education is positively related to median household income. In Model 3, counties with a one percentage point higher education share tend to have about 1.43% higher median household income, controlling for age and state. These results do not imply causation.
