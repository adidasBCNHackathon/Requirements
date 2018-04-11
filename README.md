# Requirements

- [Machine learning](#machine-learning)
  * [Must have](#must-have)
  * [We recommend you](#we-recommend-you)
  * [Nice to have](#nice-to-have)
    + [Install dependencies](#install-dependencies)
  * [Technical talk](#technical-talk)


## Machine learning

You have all the pip requirements in the requirements.txt file.

You have the entire environment in environment.yml file.

If you want you can use one or another. It is located in the [seed project](https://github.com/adidasBCNHackathon/seed-keras-models)

### Must have

- [python 3.x](https://www.python.org/downloads/)
- pip3

### We recommend you

- [virtualenvwrapper](http://virtualenvwrapper.readthedocs.io/en/latest/install.html) *If you are using windows powershell it might not work unless you run it with CMD*
- [anaconda](https://anaconda.org/anaconda/python)

** Use anaconda or virtualenvwrapper

#### Install dependencies

It is up to you to install it or not, or even use another method or technology.

```bash
# with virtualenvwrapper
$ mkvirtualenv -p python3 bot # create virtual environment
$ workon bot # enter VE
(bot) $ pip install -r requirements.txt # install dependencies (make sure you are in the bot VE)
(bot) $ deactivate # exit VE

# with anaconda
$ conda env create -f environment.yml # create virtual environment
$ conda activate bot # enter VE
(bot) $ conda deactivate # exit VE
```

** In the workshop you will be learning to work with Keras (running on top of TensorFlow, CNTK, or Theano). You need TensorFlow to run as backend or CNTK, or Theano.

** Since the 1.7 version of Tensorflow includes Keras, we recommend you to install it

### Nice to have

- [tensorflow 1.7](https://www.tensorflow.org/install/)	
- [cuda 8](https://developer.nvidia.com/cuda-80-ga2-download-archive) *Only if your computer can manage it*
- [cudnn](https://developer.nvidia.com/cudnn) *Only if you managed to install cuda on your system*

### Technical talk

- [ ] Part 1 - Being smarter than AI
- [ ] Part 2 - Train your models in the cloud (AWS)

* The entire talk will be 30 min to 1h
