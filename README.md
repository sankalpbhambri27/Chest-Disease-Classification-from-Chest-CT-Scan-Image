# Chest-Disease-Classification-from-Chest-CT-Scan-Image-Py

 - [Data link](https://drive.google.com/file/d/1z0mreUtRmR-P-magILsDR3T7M6IkGXtY/view?usp=sharing)

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 


## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

MLFLOW_TRACKING_URI=https://dagshub.com/sankalpbhambri27/experiment-tracking.mlflow \
MLFLOW_TRACKING_USERNAME=sankalpbhambri27 \
MLFLOW_TRACKING_PASSWORD=c8f9d438d78977988e3f350a7a39dd9b06eca8aa \
python script.py

## How to run?
## mlflow Dagshub url
export MLFLOW_TRACKING_URI=https://dagshub.com/sankalpbhambri27/experiment-tracking.mlflow
export MLFLOW_TRACKING_USERNAME=sankalpbhambri27 
export MLFLOW_TRACKING_PASSWORD=c8f9d438d78977988e3f350a7a39dd9b06eca8aa