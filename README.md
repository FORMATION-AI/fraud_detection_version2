Fraud-Detection/
│
├── artifacts/                 # Pre-trained models, preprocessors, and schema files
│   ├── model.pkl
│   ├── preprocessor.pkl
│   ├── encoder.pkl
│   ├── schema.json
│   └── feature_columns.json
│
├── src/                       # Source code
│   ├── components/
│   │   └── data_ingestion.py
│   │   └── data_transformation.py
│   │   └── model_trainer.py
│   ├── pipeline/
│   │   └── predict_pipeline.py
│   ├── utils.py               # Utility functions for model evaluation and saving objects
│   └── exception.py           # Custom exception handling
│
├── templates/
│   └── home.html              # Flask web app template
│   └── index.html  
│
├── app.py                     # Streamlit app 
├── main.py                    # Flask application for predictions
├── requirements.txt           # Python dependencies
└── README.md
