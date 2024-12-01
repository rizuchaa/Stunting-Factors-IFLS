# Indonesian Life Family Survey - Maternality Lineage 

The **Indonesia Family Life Survey (IFLS)** is a longitudinal dataset spanning more than three decades, starting with **IFLS 1 in 1993**. It captures vital socio-economic, health, and demographic data, making it a cornerstone for research on Indonesian families. This project addresses the critical need to validate and analyze **mother-child connections** across the five waves (IFLS 1-5) to ensure the accuracy and reliability of intergenerational studies.

## Problem Statement
### Background
Mother-child relationships are central to research exploring intergenerational health, education, and socio-economic mobility. However, several challenges arise when analyzing these connections in IFLS:

1. **Longitudinal Complexity**

- Family structures evolve over time due to marriage, divorce, migration, or death, leading to changes in household composition.
- Maintaining the continuity of mother-child relationships across waves is essential but complicated by these dynamics.
2. **Data Inconsistencies and Lineage Issues**

- **Self-Reported Relationships**: Relationships in IFLS are often self-reported, resulting in potential misreporting or inconsistencies.
- **Matrilineal Bias**: Some IFLS waves emphasize matrilineal relationships (e.g., maternal relatives), which may obscure paternal or adoptive ties, complicating analyses of true biological relationships.
3. **Policy and Research Implications**

Accurate mother-child connections are critical for:
- **Health Research**: Understanding how maternal health impacts children’s outcomes.
- **Education Studies**: Assessing the influence of maternal education on children’s academic progress.
- **Socio-Economic Analysis**: Examining resource transfer and mobility across generations.
Errors in identifying these connections can undermine research findings, leading to flawed conclusions and ineffective policies.

4. **Lack of Standardized Tools**

Existing methods for validating mother-child connections are often manual, time-consuming, and error-prone. There is no unified approach to addressing inconsistencies and lineage biases across waves.

## Objectives
This project aims to develop a Python library that:

- **Validates Relationships**: Automates the verification of mother-child connections across IFLS waves.
- **Addresses Lineage Bias**: Mitigates the matrilineal emphasis to provide a complete view of familial ties.
- **Enhances Usability**: Offers user-friendly tools for researchers to perform efficient and accurate analyses.

## Features
- **Data Cleaning**: Handle missing or inconsistent relationship data.
- **Relationship Mapping**: Identify and validate mother-child connections across waves.
- **Lineage Bias Mitigation**: Incorporate paternal and adoptive relationships where relevant.