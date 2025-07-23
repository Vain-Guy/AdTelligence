## AdTelligence: Modeling Sales Impact from Advertising Channels

**AdTelligence** is a linear regression project that investigates how advertising spend across TV, radio, and newspapers influences product sales. The objective is to determine which advertising channel holds the strongest relationship with sales and offers the most reliable basis for prediction.

### Guiding Question

> Which advertising channel has the strongest relationship with sales volume, and can be reliably used to model and predict future sales?

### Dataset Overview

The dataset contains 200 entries and includes the following columns:

| Column      | Description                                                     |
| ----------- | --------------------------------------------------------------- |
| TV          | Amount spent on TV advertising (in thousands of dollars)        |
| radio     | Amount spent on radio advertising (in thousands of dollars)     |
| newspaper | Amount spent on newspaper advertising (in thousands of dollars) |
| sales     | Number of units sold (in thousands)                             |

### Objectives

* Visualize relationships between advertising channels and sales
* Build separate linear models for TV, radio, and newspaper
* Interpret regression lines and their coefficients
* Compare model strengths to assess predictive reliability

### Key Insights

* TV and radio spend exhibit strong positive correlations with sales.
* Newspaper advertising shows a much weaker relationship.
* Among all predictors, radio advertising had the steepest slope, indicating the highest increase in sales per dollar spent.

### Tools and Technologies

* Python (Pandas, Matplotlib, Seaborn, StatsModels)
* Jupyter Notebook
* Git and GitHub

### Getting Started

To explore or reproduce the analysis:

```bash
git clone https://github.com/your-username/AdTelligence.git
cd AdTelligence
```

Open the notebook file using Jupyter or any compatible environment.

## License

This project is open-source and available under the [MIT License](LICENSE).
