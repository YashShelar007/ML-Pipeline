# ML-Pipeline

# Workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml

# MLflow

<a href="https://mlflow.org/docs/latest/index.html">Documentation</a>

# Dagshub

<b>Using MLflow Tracking</b>

import dagshub<br>
dagshub.init(repo_owner='', repo_name='', mlflow=True)<br><br>

import mlflow<br>
with mlflow.start_run():<br>
mlflow.log_param('parameter name', 'value')<br>
mlflow.log_metric('metric name', 1)

# DVC

<b> DVC Command Line </b>
<br>
1. dvc init
2. dvc repro
3. dvc dag

# AWS-CICD-Deployment-with-Github-Actions
