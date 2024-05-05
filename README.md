# Evidently AI

### Set up
```
python --verison
Python 3.11.7

pip install -r requirements.txt
```

### To see reports inside a Jupyter notebook, Run the following commands:

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

To view the Accuracy Highcharts on Jupyter:

```
open accuracy-monitoring.ipynb
```

To view the Accuracy Highcharts on web:

```
open with live server accuracy_comparison.html file
```

Integration with MLFlow:

```
run mlflow-integration.ipynb file
```

Run the following command in the terminal:
```
mlflow ui
```