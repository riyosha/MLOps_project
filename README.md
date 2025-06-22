# MLOps_project

## for dagsub
```bash
import dagshub
dagshub.init(repo_owner='riyosha', repo_name='MLOps_project', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
```bash