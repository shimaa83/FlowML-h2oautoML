# FlowML-h2oautoML
1. first step signup to https://dagshub.com/
2. in kaggel notebook install the following :!pip install mlflow dagshub , import mlflow  , import mlflow.h2o
3. to workwith h2o auto ml model install : !pip install h2o , import h2o , from h2o.automl import H2OAutoML
4. create dagshub repo
5. connect your dagshub repo with your code by the following code :dagshub.init(repo_owner=repo username, repo_name=repo name, mlflow=True)
6. use the h2o document and write your code
7. in this code we try 3 expriements by trying 5 ,15 and 20 model each expriement stored in mlflow folder
8. degshub give you link for 1 month
9. try this link for my code : https://dagshub.com/dr.alshimaa22/testme.mlflow
