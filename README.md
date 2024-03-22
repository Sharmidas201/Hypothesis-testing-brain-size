# Hypothesis Testing in Python

This Python code performs hypothesis tests using the `scipy.stats` module to analyze the brain size dataset provided in the `brain_size.csv` file (Dietz et al., 2017). The following hypothesis tests are conducted:

1. **One-sample t-test:** Test if the average Verbal Intelligence Quotient (VIQ) is significantly different from 0.
2. **Two-sample t-test:** Test if there is a significant difference in average VIQ scores between females and males.
3. **Paired t-test:** Test if there is a significant difference between Full Scale IQ (FSIQ) and Performance IQ (PIQ) in the same individuals.

## Importing Libraries and Loading Data
The necessary libraries, including `pandas` and `scipy.stats`, are imported. The brain size dataset is loaded from the `brain_size.csv` file.

## Hypothesis Test 1: One-sample t-test (VIQ = 0)
This test determines if the average VIQ score significantly differs from 0. The result indicates that the average VIQ is significantly different from 0 at a 5% significance level.

## Hypothesis Test 2: Two-sample t-test (Female VIQ = Male VIQ)
This test evaluates if there is a significant difference in average VIQ scores between females and males. The result suggests no significant difference in average VIQ scores between genders.

## Hypothesis Test 3: Paired t-test (FSIQ = PIQ)
This test assesses if there is a significant difference between Full Scale IQ (FSIQ) and Performance IQ (PIQ) in the same individuals. The result indicates no significant difference between FSIQ and PIQ in the same individuals.

## Overall Interpretation and Conclusion
- The average VIQ score in the sample is significantly different from 0.
- There is no significant difference in average VIQ scores between females and males.
- There is no significant difference between FSIQ and PIQ in the same individuals.

The code provides a comprehensive analysis of the brain size dataset through hypothesis testing, shedding light on the relationships between various intelligence measures.

