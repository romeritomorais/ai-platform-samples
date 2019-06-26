# AI Platform Training

## Overview

To use hyperparameter tuning in your training job you must perform the following steps:

 - Specify the hyperparameter tuning configuration for your training job by
   including a HyperparameterSpec in your TrainingInput object.
 - Include the config in your training application.

Parse the command-line arguments representing the hyperparameters you want to
tune, and use the values to set the hyperparameters for your training trial.

 - Add your hyperparameter metric to the summary for your graph.
 - Add your hyperparameter configuration information to your configuration YAML file.

## Prerequisites

* Follow the instructions in the [setup](../../../../setup) directory in order to setup your environment
* Create a Python 3 virtual environment and activate it.
* Change the directory to this sample and run `python setup.py install`.
  Optional: You can also run `pip install -r requirements.txt`
* Run code in `tensorflow/structured/base/trainer/` location using the `config.yaml` in this folder.
Note: This is mostly for local testing of your code. When you submit a training job, no code will be executed on your local machine.


## Documentation

Please go to the official AI platform [documentation]((https://cloud.google.com/ml-engine/docs/tensorflow/using-hyperparameter-tuning)) for more details.