# Purpose

The purpose of this project is to fit an linear model to a dataset and perform model diagnostics. Model diagnostics are considered using QR and SVD. Things properties such as scale, rank, condition number are also explored. 

The data used for this project contains information about student performances. The dataset contains 102 observations that consistes of 5 five columns: `id`, `study_hours_per_week`, `attendance_pct`, `prior_score`, and `final_score`. `id` is the primary key for the dataset and is unique. `final_score` is the response that is being estimated by `study_hours_per_week`, `attendance_pct`, `prior_score` and an intercept term that is not included in the dataset.