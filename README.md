# Predicting The Success Of Kickstarter Projects With Machine Learning
# Written in Python

Goal: Will a kickstarter project will be successful or not.
      Trying to get the most accurate results.
      Expanded goal, was to find which classification model would be the most accurate and best for our problem.

Datasets: Webrobots Dataset 26.762K projects, 10 features.
          18k Dataset 18.042k projects, 19 features.
          Kicktraq Dataset 6.800k project, 15 features.
      
Stages: Data cleaning - Data preperation
        Feature Selection
        Hyperparameter Tuning
        Recording of the results with 10 fold cross validation.

Conclusion: It was found that Random Forest was the best model in this particular problem.
            acc 78.29% f1-score 82.10%, in webrobots dataset.
            acc 84.08% και f1-score 84.19%, in 18k dataset. 
            acc 90.39% και f1-score 91.5%, in kicktraq dataset . 
