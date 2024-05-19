# Evidently AI

### Set up
```
python --verison
Python 3.11.7

pip install -r requirements.txt
```

```
conda install -c conda-forge jupyter_contrib_nbextensions

# sample output:
https://gist.github.com/rajasgs/7817cc1b2c42cd291bebfcd592d03482
```

```
pip install --upgrade notebook==6.4.12
```

```
jupyter nbextension enable evidently --py --sys-prefix

output:
Enabling notebook extension evidently/extension...
      - Validating: OK
```


### Test Local:
```
jupyter lab

verify:
http://0.0.0.0:
```

### Report Generation:

Open and Run the following Notebook:

```
report-generation.ipynb
```

### Accessing the values produced in the report:

Open and Run the following Notebook:

```
accessing-report.ipynb
```

### Integration with MLFlow:

Run the following command in the terminal:
```
mlflow ui
```

```
run mlflow-integration.ipynb file
```

```
Reload the MLFlow UI to view the new experiment
```


