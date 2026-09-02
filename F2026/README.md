# Stat 220, Fall 2026

Course material, posted unit by unit as we get to it. If a unit is not here yet,
it is because we have not covered it.

## What is here now

| | |
|---|---|
| `220_Syllabus_F2026.pdf` | Grading, exam dates, the AI policy, and what the course covers |
| `Slides/` | The deck for each unit |
| `Notebooks/` | Code companions. Every technique from the unit, run on real data, with output |
| `Homework/` | The assignment notebooks you fill in and submit on Learning Suite |
| `Practice/` | Multiple-choice practice for the midterm, with answers and explanations |

## Unit 1: Statistical Inference

Signal against noise, the standard error, the t-statistic, p-values, the two kinds
of error, power, confidence intervals, and the assumptions all of it rests on.

- `Slides/Unit_01_Inference.pdf`
- `Notebooks/Code_Unit01_Inference.ipynb`
- `Homework/Stat_220_HW_Unit01_Inference.ipynb`
- `Practice/Practice_Inference.pdf`

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
```
