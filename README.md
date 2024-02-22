# transfer_leaning_VGG16


This is a deep learning projec that uses VGG16 model to perform binary classification on a dataset of shells and pebbles. It uses MLflow for model version control and experimentation based on different parameters. While DVC has been used for pipeline version control as one changes the parameters in the `params.yaml`. Changing the parameters would then require to run the command cmd `dvc repro` to train the model based on the new parameters. This project has been deployed on a web application i.e. `app.py` and can be used by running cmd `python app.py`. Docker has also been used in this project to deploy it on aws server but that is under progress.



