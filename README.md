
# Data Preparation
The CNN/DailyMail dataset will be used for training and evaluating the model.
The dataset can be easily downloaded from the internet sources.

python3 make_data_files.py

## Prerequisites
* Pytorch
* Tensorflow
* Python 3
* rouge

## Model training
Change the config.py file in the data_util folder for setting hyper-parameter and define file paths.
Run
```
python3 train.py
```

## Model testing
Change the config.py file in the data_util folder for setting hyper-parameter and define file paths.
Run
```
python eval.py --task=test --load_model=[NAME OF THE SAVED MODEL].tar
```
