# Predicting Bike-Sharing Data [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
<br><br>

<p align="center">
    <img src="assets/neural_network.png" width=300px>
<p>

<img alt="NumPy" src="https://raw.githubusercontent.com/numpy/numpy/main/branding/logo/primary/numpylogo.svg" width=10%><br>
**Built with NumPy** 

---

## A. Introduction
Part of Udacity's Deep Learning Nanodegree, In this project, I'll get to build a neural network from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up, I'll have a much better understanding of gradient descent, backpropagation, and other concepts that are important to know before we move to higher-level tools such as PyTorch. I'll also get to see how to apply these networks to solve real prediction problems!

The data comes from the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).

## B. Instructions
- Clone this repository:
```bash
git clone https://github.com/kfrawee/Predicting-Bike-Sharing-Patterns.git
```
- Download anaconda or miniconda.
- Create a new conda environment:
```bash:
conda create --name deep-learning python=3
```
- Activate your new environment:
    - Mac/Linux: 
    ```bash
    source activate deep-learning
    ```
    - Windows:
    ```bash
    activate deep-learning
    ```
- Ensure you have `numpy`, `matplotlib`, `pandas`, and `jupyter notebook` installed by doing the following:
```bash
conda install numpy matplotlib pandas jupyter notebook
```
- Run the following to open up the notebook server:
```bash
jupyter notebook
```
- In your browser, open `Predicting_bike_sharing_data.ipynb`

## C. Results
### Training and Validation loss
After modeling and training the network and tuning the hyper-parameters, we got a `Training loss: 0.073` and a `Validation loss: 0.152`.

### Checking out predictions
Here, used the test data to view how well the network is modeling the data:


---
