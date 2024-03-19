# This repo is for Tensorflow probability practice.

TODO: Create environment.yml .    The environment was constructed with these commands:

```
conda create --name tfp python=3.11  # 3.11 is lateset supported by tf
conda activate tfp
conda install jupyter
conda install seaborn # Installs all kinds of useful depends!
pip install tensorflow 
pip install tensorflow-probability
pip install tensorflow-probability[tf]  # for keras integration
pip install scikit-learn  # for train test split among other things
```


## Guides:

https://www.tensorflow.org/probability/overview

It's important to realize that TFP requires specific versions of tensorflow. 

## Note that with recent (2.16) versions of tensorflow and keras, there are breaking changes. So you hae to als install tensorflow-probability[tf] to get the keras integration, and then you have to use tf_keras instead of keras.  This is poorly documented.  This is so you can use keras 2.0 instead of the new keras 3.0