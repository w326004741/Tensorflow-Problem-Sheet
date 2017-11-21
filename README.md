# Tensorflow-Problem-Sheet
> Module: Emerging Technologies / 4th Year  
> Lecturer: Dr Ian McLoughlin  
[Problem set: Tensorflow](https://github.com/w326004741/Tensorflow-Problem-Sheet/wiki/Problem-set:-Tensorflow)


These problems relate to the Python package [Tensorflow](https://www.tensorflow.org/). We will again use the famous [iris data set](https://en.wikipedia.org/wiki/Iris_flower_data_set). Download Iris data set [here](https://github.com/w326004741/Tensorflow-Problem-Sheet/blob/master/irisdata.csv)

## Need Components:
- [Tensorflow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [Jupyter](http://jupyter.org/index.html)
- [Numpy](https://docs.scipy.org/doc/numpy-dev/user/quickstart.html)
- [Iris data set](https://en.wikipedia.org/wiki/Iris_flower_data_set)
 

## Installing Tensorflow
 #### In order to install Tensorflow, your system must contain one of the following Python versions:
 - [Python 2.7](https://www.python.org/downloads/)
 - [Python 3.X](https://www.python.org/downloads/)
#### Use pip to install [Tensorflow](https://www.tensorflow.org/install/):
 - `$ pip install tensorflow`      
 - `$ pip3 install tensorflow`     
#### Validate your installation:
Start a terminal(for mac, windows enter your cmd or cmder). If you installed through [Anaconda](https://www.anaconda.com/download/#macos), activate your [Anaconda](https://www.anaconda.com/download/#macos) environment. Invoke python from your terminal as follows:
```bash
$ python
```
Enter the following short program inside the python interactive shell:
```bash
>>> import tensorflow as tf
>>> hello = tf.constant('Hello, TensorFlow!')
>>> sess = tf.Session()
>>> print(sess.run(hello))
```
If the system outputs the following, then you are ready to begin writing TensorFlow programs:
```bash
Hello, TensorFlow!
```
## Installing Keras
Before installing Keras, please install one of its backend engines: TensorFlow, Theano, or CNTK. We recommend the TensorFlow backend.

#### Install Keras from PyPI (recommended):
 - `sudo pip install keras`
 #### If you are using a virtualenv, you may want to avoid using sudo:
 - `pip install keras`
 #### If you want using a [Anaconda Navigator](https://www.anaconda.com/download/#macos):
 ```
 1. Open Anaonda Navigator
 2. Click Environments
 3. Change installed to All
 4. Enter keras in the search package
 5. Select keras and click Apply
```


