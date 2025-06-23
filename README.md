# MLOps_project

## for dagsub
```bash
import dagshub
dagshub.init(repo_owner='riyosha', repo_name='MLOps_project', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
```

```bash

pip install mlflow

mlflow server -h 0.0.0.0 --default-artifact-root s3://mlflow-bucket-rio

export MLFLOW_TRACKING_URI=http://ec2-35-89-84-129.us-west-2.compute.amazonaws.com:5000/

```