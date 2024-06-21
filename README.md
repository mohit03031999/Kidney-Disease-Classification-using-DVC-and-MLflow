# Kidney-Disease-Classification-using-DVC-and-MLflow

## Project Description

Orchestrated an end-to-end deep learning project for kidney disease classification, including data ingestion, base model preparation, model training and evaluation, MLflow integration, DVC pipeline, prediction pipeline, and deployment on AWS using CI/CD.

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/mohit03031999/Kidney-Disease-Classification-using-DVC-and-MLflow.git
```


### STEP 01- Install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```


## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/agarwalmohit0303/Kidney-Disease-Classification-using-DVC-and-MLflow.mlflow \
MLFLOW_TRACKING_USERNAME=agarwalmohit0303


<img width="1440" alt="Screenshot 2024-06-20 at 4 51 56 PM" src="https://github.com/mohit03031999/Kidney-Disease-Classification-using-DVC-and-MLflow/assets/39363730/74ff8027-ffc1-4907-95a0-cb1c041e68cd">

### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVCs

MLflow

- Its Production Grade
- Trace all of your expriements
- Logging & taging your model


DVC

- Its very lite weight for POC only
- lite weight expriements tracker
- It can perform Orchestration (Creating Pipelines)


## DVC-DAG

<img width="1420" alt="Screenshot 2024-06-20 at 6 40 31 PM" src="https://github.com/mohit03031999/Kidney-Disease-Classification-using-DVC-and-MLflow/assets/39363730/8914d964-40ee-4a9b-af53-9938f4ef8329">
