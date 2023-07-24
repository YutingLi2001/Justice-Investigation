# Justice-Investigation : Investigating and Improving "Machine Bias" in Recidivism Prediction

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Data Used](#data-used)
4. [Implementation](#implementation)
5. [Results](#results)
6. [Discussion](#discussion)
7. [Future Work](#future-work)
8. [Conclusion](#conclusion)
9. [References](#references)

## Introduction <a name="introduction"></a>
This project aims to improve upon existing methods for predicting recidivism rates among prisoners. It does so by examining bias in the Correctional Offender Management Profiling for Alternative Sanctions (COMPAS) system, then implementing a prototype system using logistic regression to improve prediction accuracy.

## Objectives <a name="objectives"></a>
The primary objectives of this project are:

1. To prove the bias that exists in the COMPAS system.
2. To create a more accurate predictor for recidivism rates while using fewer variables.

## Data Used <a name="data-used"></a>
Data for this project was sourced from the Broward County of Florida. Please refer to the source code for further details.

## Implementation <a name="implementation"></a>
We employed logistic regression to develop our predictive model. This approach was found to be effective in our case, given its ease of implementation. The details of the prototype system can be found in the 'Implementation' folder.

## Results <a name="results"></a>
We observed a 7% increase in prediction accuracy compared to the existing COMPAS system. The improved accuracy of our system could potentially result in substantial cost savings and a reduction in national crime rates.

## Discussion <a name="discussion"></a>
The use of fewer factors in our system promotes greater transparency and accountability, as it simplifies the decision-making process. Additionally, we assert that flexible punishment assignments for different offenders may lead to a more just penal system.

## Future Work <a name="future-work"></a>
For future iterations of this project, we plan to:

1. Develop a user-friendly interface for the system to facilitate use by non-technical individuals.
2. Incorporate more diverse datasets. Currently, our system may not apply as accurately to defendants outside of Broward County, Florida, as recidivism rates can be influenced by regional, cultural, and familial backgrounds.

## Conclusion <a name="conclusion"></a>
While our project achieved its primary objectives, there is room for further improvement. Greater knowledge of data processing and background information about crime could enhance the overall accuracy of the project.

## References <a name="references"></a>
A full list of references used in this project can be found in the project report in the 'Documentations' folder. Please ensure to give credit where due if you use any part of this project.
