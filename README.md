# student-performance-ml
This is my first attempt of an unguided ML project, my goal was to build strong intuition around EDA, feature engineering, cross-validation, and model comparison.
**Dataset**
	•	Type: Tabular, structured data
	•	Target variable: Final performance score (continuous)
	•	Features include:
	•	Academic history (e.g. previous scores)
	•	Behavioral indicators (e.g. study hours)
	•	Categorical attributes (e.g. extracurricular activities)
This was a regression problem since the target is continuous, and I chose to compare between:
  - Ridge regression
  - Lasso regression
  - Random forests
With different hyperparameters optimized with GridSearchCV.
After inspecting the data and performing GridSearchCV, a random forest was the best for my task.
Then after choosing, I compared the forest's performance against a baseline (which in this case is the mean since our error was calculated using MSE and RMSE.)
My model performed way better than the baseline, indicating that it learned petterns strongly, and after checking feature importance, previous academic performance was the strongest predictor.

I had fun learning different approches to solve my problem, and intuition is not discrete, so I'll keep on learning to develop a mental toolkit to 
tackle different ML problems, but I'm happy with how this turned out!
