# Credit-Risk-Model
This is an assignment to predict the probabilities of default(PD)

# Approach
1. Target - loan_status
Keep only "Fully Paid" & "Charged off" values.
2. Find NULL value % for each feature. If its >50% then remove that feature.
3. Features which needs booleans, apply "dummies" on it. Features like sub_grade,home_ownership,etc
4. Apply RandomForest ML model on data
