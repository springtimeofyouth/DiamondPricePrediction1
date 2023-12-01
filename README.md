## ML Project
## Project Structure
```
.
├── artifacts
│   ├── model.pkl
|   ├── preprocessor.pkl
│   ├── preprocessor.pkl
│   └── rawdata.csv
├── notebook
│   └── data
│       └── gemstone.csv
├── src
|     ├── components
|          └── __init__.py
|          └── data_ingestion.py
|          └── data_transformation.py
|          └── model_trainer.py 
|     ├── pipelines
|          └── __init__.py
|          └── prediction_pipeline.py
|          └── training_pipeline.py
|     └── __init__.py
|     └── exception.py
|     └── utils.py
|     └── logger.py
├── templatess
│   ├── index.html
│   ├── form.html
├── application.py
├── requirements.txt
├── setup.py
└── README.md
```

### Introduction
This is an implementation of end-to-end Machine Learning Project.
Pipelines:
Train Pipeline and Prediction Pipeline

Used html to form an interface

The app is deployed at
https://diamondpricepredict.azurewebsites.net
