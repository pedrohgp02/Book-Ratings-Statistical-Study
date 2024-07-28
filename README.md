# The Influence of Book Length on Average Ratings in Goodreads

## Overview

This project investigates whether the length of a book, measured by the number of pages, influences its average rating on Goodreads. Utilizing a dataset of 200 books, this analysis employs multiple regression techniques to explore the relationship between book length and reader ratings.

## Project Structure

- `Statistical Analysis.ipynb`: The Jupyter Notebook containing the analysis.
- `sampled-books.csv`: The dataset used for the analysis.
- `The Influence of Book Length on Average Ratings in Goodreads.pdf`: The detailed research paper explaining the methods and findings.

## Dataset

The dataset comprises 200 entries from Goodreads, focusing on the following variables:
- **Independent Variable**: Number of pages (quantitative).
- **Dependent Variable**: Average rating (continuous).

### Key Points:
- The dataset may have temporal limitations, affecting the relevance of the average ratings.
- Outliers and inaccuracies were addressed during the analysis to ensure data quality.

## Methods

The analysis involves:
1. **Descriptive Statistics**: Calculation of mean, median, mode, standard deviation, and range.
2. **Regression Analysis**: Evaluation of linear relationships using Pearson's r, regression equations, and statistical significance tests.
3. **Model Conditions**: Ensuring LINE (Linear, Independent, Normal Distributed, Equal Variances) conditions for valid regression analysis.

### Tools:
- Python for statistical calculations and data visualization.
- Standard statistical formulas for regression and correlation analysis.

## Multiple Regression

To enhance the model's predictive power, a multiple regression analysis was conducted, incorporating the count of text reviews alongside the number of pages.

### Findings:
- The inclusion of additional variables provided a slight improvement in the model's fit.
- The primary model with only the number of pages remained the most significant predictor of average ratings.

## Conclusion

The project found a weak positive correlation between book length and average ratings, suggesting that longer books tend to receive slightly higher ratings. However, the effect size is small, indicating that other factors may play a more significant role in determining reader ratings.

## How to Use
1. **Clone the Repository**: `git clone https://github.com/pedrohgp02/Book-Ratings-Statistical-Study.git`
2. **Install Dependencies**: Ensure you have Python and necessary libraries installed.
3. **Run the Jupyter Notebook**: Open `Statistical Analysis.ipynb` in Jupyter Notebook to explore the analysis.

## Contact

For any questions or further information, please contact pedro@uni.minerva.edu.
