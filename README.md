# End-to-End-Chest-Cancer-Classification-using-MLflow-DVC


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml



## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtube.com/playlist?list=PLkz_y24mlSJZrqiZ4_cLUiP0CBN5wFmTb&si=zEp_C8zLHt1DzWKK)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/kamran-blouch/End-to-End-Chest-Cancer-Classification-using-MLflow-DVC.mlflow \
MLFLOW_TRACKING_USERNAME=kamran-blouch \
MLFLOW_TRACKING_PASSWORD=a739adc1e3a8cbe032c5bd234d3ac180793f15e1 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/kamran-blouch/End-to-End-Chest-Cancer-Classification-using-MLflow-DVC.mlflow
export MLFLOW_TRACKING_USERNAME=kamran-blouch 

export MLFLOW_TRACKING_PASSWORD=a739adc1e3a8cbe032c5bd234d3ac180793f15e1

```
