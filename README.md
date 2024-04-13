# ml_checklist
[reference](https://github.com/ageron/handson-ml3/blob/main/ml-project-checklist.md)
<details>
<summary>1. Frame the problem and look at the big picture </summary>

1. Define the objective.
2. How will your solution be used?
3. What are the current solutions/workarounds?
4. How should you frame this problem (supervised/ unsupervised, online/offline, etc.)?
5. How should performance be measured?
6. Is the performance measure aligned with the business objective?
7. What would be the minimum performance needed to reach the business objective?
8. What are comparable problems? Can you reuse experiance or tools?
9. Is human expertise available?
10. How would you solve the problem manually?
11. List the assumptions you or others have made so far?
12. Verify assumptions if possible.
</details>

<details>
<summary>2. Get the data </summary>

Automate as much as possible
1. List the data you need and how much you need.
2. Find and document where you can get that data.
3. Check how much space it will take.
4. Check legal obligations, and get the authorization if necessary.
5. Get access authorizations. 
6. Create a workspace (with enough storage space).
7. Get the data. 
8. Convert the date to a format you can easily manipulate (without changing the data itself).
9. Ensure sensitive information is deleted or protected (e.g. anonymized)
10. Check the size and type of data (time series, sample, geographical, etc.)
11. Sample a test set, put it aside, and never look at it (no data snooping!).

</details>

<details>
<summary> 3. Explore the data </summary>
Try to get insights from a field expert for these steps.

1. Create a copy of the data for exploration (sampling it down to a manageable size if necessary).
2. Creata a jupyter notebook to keep record of your data exploration.
3. Study each attribute and its characteristics:
    - Name
    - Type (categorical, int/flozt, bounded/unbounded, text, structured, etc.)
    - % of missing values
    - Noisiness and type of noise (stochastic, outliers, rounding errors, etc.)
    - Possibly useful for the task?
    - Type of distribution (Gaussian, uniform, logarithmic, etc.)
4. For supervised learning rate, identify the target attribute(s).
5. Visualize the data.
6. Study the correlations between attributes.
7. Study how you would solve the problem manually.
8. Identify the promising transformations you may want to apply.
9. Identify extra data that would be useful (go back to 'Get the data')
10. Document what you have learned.
</details>

<details>
<summary> 4. Prepare the data </summary>
Notes:
- Work on copies of the data (keep the original dataset intact)
- Write functions for all data transformations you apply, for five reasons:
    - So you can easily prepare the data the next time you get a fresh dataset
    - So you can apply these transformations in future projects 
    - To clean and prepare the test set 
    - To clean and prepare the new data instances 
    - To make it easy to treat your preparation choices as hyperparameters

1. Data Clearning:
    1.1. Fix or remove outliers(optional)
    1.2. Fill in missing values (e.g. with zero, mean, median...) or drop their rows (or columns).
2. Feature selection (optional):
    2.1. Drop the attributes that provide no useful information for the task
3. Feature engineering, where appropriate:
</details>





