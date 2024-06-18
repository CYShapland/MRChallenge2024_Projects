# Overview
A collection of submitted material for the 2024 MR Data Challenge. The 2024 MR Data Challenge is a session presented at the 2024 Mendelian Randomization Conference, held at the University of Bristol. For more information on the conference, please visit the MR conference [website](https://www.mendelianrandomization.org.uk/).

The report accompanying each project is available for download [here](https://github.com/CYShapland/MRChallenge2024/Projects).

**A plenary session will be held at 9:00 AM on Friday 21st June in Lecture Theatre of the Humanities building at the University of Bristol, showcasing the submitted analyses.**

A key aim of the session will be to bring together methodologists and statisticians with experts from epidemiology, medical and biological sciences, to comment and debate the results. The session will include presentations on an overview of all analyses attempted at a meta-level; quickfire presentations from individuals and teams on their analysis; debate on the strengths and limitations of different methodological approaches.

---

## 1. Causal Inference and Causal Interaction Effects of Genetic Variants on Major Depressive Disorder: A Machine Learning and Mendelian Randomization Study Across Diverse Ancestries

*Nismabi Adimaveettil Nisamudheen<sup>1</sup>*

<sup>1</sup>Genomics & Precision Medicine, College of Health & Life Sciences, Hamad Bin Khalifa University 

### Project Summary

To examine the relationship between Alcohol Use Disorder (AUD) and Major Depressive Disorder (MDD) across African, East Asian, and South Asian populations, we employed Mendelian Randomization (MR) analysis followed by a machine learning-based interaction analysis.

Mendelian Randomization (MR): We first used MR to infer potential causal relationships between AUD and MDD. Utilizing the TwoSampleMR and MendelianRandomisation R packages, we analyzed genetic data. MR leverages genetic variants associated with AUD as instrumental variables to estimate their impact on MDD, mimicking a natural experiment to avoid confounding and reverse causation. We conducted pleiotropy and heterogeneity analyses to ensure the robustness of our findings, assessing whether genetic variants influenced multiple traits (pleiotropy) and checking for variability in effect sizes across different studies (heterogeneity).

Machine Learning-Based Interaction Analysis: Following MR, we applied our custom machine learning approach, termed Genetic Interaction Predictor (GIP), to explore interactions between AUD-related genetic factors and their influence on MDD risk. GIP employs Random Forest models to identify and rank the importance of various AUD-related variables, providing insights into key factors contributing to MDD risk in each population. The performance of GIP was evaluated using Mean Squared Error (MSE) and R² metrics, ensuring the accuracy and reliability of our predictive models. This analysis offered a comprehensive view of how genetic and environmental factors might interact to affect MDD risk in the context of AUD, revealing both shared and distinct aspects across the studied populations.

Together, these methodologies provided a thorough examination of the causal pathways and interaction effects between AUD and MDD, offering valuable insights into the complexities of these disorders across different ethnic groups.

## 2. Cross-Ancestral Comparative Study of AUD's Causative Effect on MDD

*Nismabi Adimaveettil Nisamudheen<sup>1</sup>*

<sup>1</sup>Department of Bioscience & Bioengineering, Indian Institute of Technology Jodhpur 

### Project Summary

TBC

## 3. TBC

*Na Zhang <sup>1</sup>*

<sup>1</sup>School of Public Health, Shanghai Jiao Tong University

### Project Summary

TBC

---

To build the website run the following code.
``` r
rmarkdown::render_site(encoding = 'UTF-8')
```