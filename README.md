# ml-captcha

Deep-Learning-Based CAPTCHA Solving using TensorFlow and CNN Model.  
Dataset used https://www.kaggle.com/aadhavvignesh/captcha-images  

Beside Captcha Solver there are two additional Jupyter Notebooks about Data Preprocessing and Hyperparameter tuning.  

## Getting started
* Download [dataset](https://www.kaggle.com/aadhavvignesh/captcha-images)
* Install OpenCV  `pip install opencv-python`
* Be sure you have all requirements: `tensorflow`, `scikit-learn`, `numpy`.. We will use [Tensorboard](https://www.tensorflow.org/tensorboard/) for visualization

## Resources
[Hyperparameter Tuning with the HParams Dashboard](https://tensorflow.google.cn/tensorboard/hyperparameter_tuning_with_hparams)

## Notes
* If you don’t have a computer that can take the workload use Google Colab (there are 10 000 images ~ 100 000 characters)
* drive folder contains logs from runs (so we can view these logs in TensorBoard without model training)
* Make sure dataset is in folder named dataset
