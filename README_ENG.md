# Statistical Analysis on Insurance Dataset

![DALL·E 2024-02-13](https://github.com/exelero565/Project_4/assets/97280394/8cbba5c5-7b10-4a39-91b7-c28a5fd6994d)

## Project Overview

In this project, we delve into the insurance domain to explore how various client characteristics influence the annual insurance payouts. Using statistical tests within an Exploratory Data Analysis (EDA) framework, we aim to uncover patterns and relationships within the data. The insights gained will assist an insurance company in understanding the impact of client attributes on the size of insurance payouts.

## Data Description

The dataset comprises annual insurance payouts alongside client characteristics, structured as follows:

- **age**: Client's age.
- **sex**: Client's gender (female/male).
- **bmi**: Body Mass Index, indicating the body fat based on height and weight.
- **children**: Number of dependents covered by the insurance.
- **smoker**: Smoking status of the client (yes/no).
- **region**: Client's residential area in the US (northeast, southeast, southwest, northwest).
- **charges**: Annual insurance payouts to the client.

Source: ["Medical Cost Personal Datasets" (kaggle.com)](https://www.kaggle.com/datasets/mirichoi0218/insurance/)

## Objectives

The project seeks to answer the following questions with a significance level of $\alpha=0.05$:

1. Are insurance payouts for male clients higher than for female clients?
2. Are insurance payouts for non-smokers less than for smokers?
3. Does the region of residence affect the size of payouts?
4. Is there a relationship between smoking and gender?

## Methodology

- **Data Preprocessing**: Initial data cleaning and preparation for analysis.
- **Exploratory Data Analysis (EDA)**: Conducted to identify patterns and relationships in the data.
- **Statistical Testing**: Employed various statistical tests to answer the research questions, including:
  - Shapiro-Wilk test for normality.
  - Mann-Whitney U test and Kruskal-Wallis test for comparing distributions.
  - Chi-square test for independence between categorical variables.

## Key Findings

- No significant difference in insurance payouts between male and female clients.
- Insurance payouts for non-smokers are significantly lower than for smokers.
- No evidence suggests that the region of residence impacts the size of insurance payouts.
- A significant relationship exists between smoking status and gender, indicating that smoking preferences differ between genders.

## Conclusion

The statistical analysis provides valuable insights into factors influencing insurance payouts, highlighting the importance of smoking status over gender or region of residence. These findings can aid insurance companies in refining their risk assessment models and tailoring insurance policies more effectively.

## How to Use

1. Clone the repository to access the Jupyter notebooks.
2. Install the required Python packages listed in `requirements.txt`.
3. Explore the notebooks to see the data analysis, statistical testing, and conclusions in detail.

## Future Directions

- Incorporate more client characteristics to explore additional factors influencing insurance payouts.
- Apply machine learning models to predict insurance payouts based on client attributes.
- Extend the analysis to compare different insurance products and their dependency on client attributes.

![Statistical Analysis on Insurance Dataset Overview](sandbox:/mnt/data/Create_an_image_that_visually_represents_a_data_sc.png)

### License
The project is distributed under the MIT license. You can freely use and distribute this code for personal and commercial purposes with a mandatory link to the author.

### Acknowledgments
Credits to data providers, contributors, and any references used in the development of this project.

## Author
https://github.com/exelero565
