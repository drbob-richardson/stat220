# Stat 220, Fall 2026

Course material, posted unit by unit as we get to it. If a unit is not here yet,
it is because we have not covered it.

| | |
|---|---|
| `220_Syllabus_F2026.pdf` | Grading, exam dates, the AI policy, and what the course covers |
| `Slides/` | The deck for each unit |
| `Notebooks/` | Code companions. Every technique from the unit, run on real data, with output |
| `Homework/` | The assignment notebooks you fill in and submit on Learning Suite |
| `Practice/` | Multiple-choice practice for the midterm, with answers and explanations |
| `data/` | Data files used by the assignments |

## Unit 1: Statistical Inference

Signal against noise, the standard error, the t-statistic, p-values, the two kinds
of error, power, confidence intervals, and the assumptions all of it rests on.

- `Slides/Unit_01_Inference.pdf`
- `Notebooks/Code_Unit01_Inference.ipynb`
- `Homework/Stat_220_HW_Unit01_Inference.ipynb`
- `Practice/Practice_Inference.pdf`

## Unit 2: A Map of Models

What is on the menu and how to choose. The model families and what each one
assumes, the difference between a probability model and a non-probability one,
the five jobs people hand a model, and how to tell whether one model is better
than another.

- `Slides/Unit_02_A_Map_of_Models.pdf`
- `Notebooks/Code_Unit02_Map_of_Models.ipynb`
- `Homework/Stat_220_HW_Unit02_Map_of_Models.ipynb`
- `Practice/Practice_Models.pdf`

## Unit 3: Linear Regression

Fitting a line and reading what it says. What least squares minimizes, a slope with
its units and its standard error, residual plots, binary and categorical predictors,
interactions, and what happens to a coefficient when another variable joins the model.

- `Slides/Unit_03_Linear_Regression.pdf`
- `Notebooks/Code_Unit03_Regression.ipynb`
- `Homework/Stat_220_HW_Unit03_Regression.ipynb`
- `Practice/Practice_Regression.pdf`

## Unit 4: Prediction and Choosing Predictors

Using the whole model at once. Predicting a new case, the difference between a
confidence interval and a prediction interval, extrapolation including combinations
of values the data never contained, why error on your own rows is too small,
cross-validation, overfitting and underfitting, and how to decide which predictors
belong.

- `Slides/Unit_04_Prediction_and_Choosing_Predictors.pdf`
- `Notebooks/Code_Unit04_Prediction.ipynb`
- `Homework/Stat_220_HW_Unit04_Prediction.ipynb`
- `Practice/Practice_Prediction.pdf`

## How to work the homework

Each assignment opens with simulated data, where you set the truth yourself and can
check your answer against it. It then moves to a real dataset and a real question,
where nobody knows the truth and the last part is deciding what can and cannot be
said. That last part is the point of the course.

Homework is due at 5:00 PM on the date posted on Learning Suite. Start the code
companion first. It has the syntax you need, so you can spend your time on the
reasoning instead of on pandas.

## Data

Datasets load straight from the web, so there is nothing to download:

```python
import pandas as pd
rent = pd.read_csv("https://richardson.byu.edu/220/rent.csv")
cafe = pd.read_csv("https://drbob-richardson.github.io/stat220/F2026/data/campus_cafe.csv")
routes = pd.read_csv("https://drbob-richardson.github.io/stat220/F2026/data/delivery_routes.csv")
```
