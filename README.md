# Data Analysis and Science
Repo for models and tests

# Description

## Use Jupyter with Docker
```
docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "${PWD}":/home/jovyan/ jupyter/datascience-notebook:33add21fab64
```