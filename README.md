# Sleep Health Analysis Using Public Sleep Data

## Overview
This project analyzes anonymized sleep and lifestyle data from 374 individuals to identify how various factors impact sleep quality and duration. The dataset includes details like occupation, BMI category, sleep disorders, physical activity, and more. Our goal is to extract actionable insights that could improve sleep health.

## Dataset
The dataset includes the following columns:
- **Sleep Duration (hours)**
- **Quality of Sleep (scale: 1-10)**
- **Occupation**
- **BMI Category** (Underweight, Normal, Overweight, Obese)
- **Sleep Disorder** (None, Insomnia, Sleep Apnea)
- And other lifestyle features (exercise, stress, etc.)

## Analysis Steps
1. **Load & Inspect Data**: Cleaned and explored the dataset using pandas.
2. **Occupation & Sleep**:
   - Identified which occupation has the lowest average sleep duration.
   - Compared average sleep quality across occupations.
3. **BMI & Insomnia**:
   - Calculated insomnia prevalence across BMI categories: Normal, Overweight, Obese.
4. **Data-Driven Insights**:
   - Discovered patterns that may assist in personalized sleep health recommendations.

## Key Insights
- Certain occupations are associated with both lower sleep duration and sleep quality.
- Higher BMI categories (Overweight, Obese) show a higher proportion of users with insomnia.
- Sleep quality and duration are not always correlated across professions.

## Tools & Libraries
- Python
- Pandas

## Results
The final results are printed in the script and reveal meaningful lifestyle correlations with sleep metrics. This can help healthcare providers and app developers prioritize features and content based on real-world trends.




