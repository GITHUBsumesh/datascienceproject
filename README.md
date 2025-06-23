# End to End Data Science Project

### Workflows--ML Pipeline

1. Data Ingestion
2. Data Validation
3. Data Transformation-- Feature Engineering,Data Preprocessing
4. Model Trainer
5. Model Evaluation- MLFLOW,Dagshub

## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py


The error you're encountering:
ModuleNotFoundError: No module named 'distutils._modified'
is caused by a bug introduced in recent versions of setuptools, which replaced distutils but still has internal references to distutils._modified — a module that no longer exists.

pip install setuptools==68.0.0
