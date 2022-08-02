# Campaign Acceptance Machine Learning Description

-- **campaign correlation.ipynb** - Python script using seaborn heat map to show campaign acceptance correlation.

-- **decision tree campaign files** - Python scripts sklearn decision tree algorithm to analysis and predict campaign acceptance in the population.


*The decision tree algorithm was chosen to analysis and predict campaign acceptance in the population for 1 main reasons: *
- Although decision tree is considered to be less accurate than random forest for example, it is more descriptive about how it preforms the classification and allows us to interpret it more easily.

*Adjusted columns: *
- After applying the decision tree algorithm for each campaign I've decided to check if the **Education** **Marital_Status**, **Kidhome** & **Teenhome** columns are adding too much of unnecessary information to the algorithm and if simplifying them will increase the algorithm accuracy. there for I've replaced the categorical **Education** & **Marital_Status** columns and the numerical **Kidhome** & **Teenhome** columns to the binary **High_Education**, **Relationship** & **Childrenhome** columns.
- **High_Education** - 1 for academic education (2n Cycle, Master, PhD) and 0 for basic education (basic, graduation)
- **Relationship** - 1 for in relationship 0 for not in relationship.
- **Childrenhome** - 1 if any kids or teens at home 0 for none.


