# Back runable transaction classifier [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A classifier for back-runable ethereum transactions made with neural network.

## 1. About
I created this classifier during a competition on the recognition of ethereum transactions subject to back-running (more information on this can be found in the useful links). Also does not include code for the regression problem as no significant results were found and the model could not learn with the available data

This repository shows only the best performing model that the author has been able to obtain, and is the result of several tests and tuning steps of the model.

## 2. Requirements
* Google account 
* 10gb+ of gdrive space
* Colab TPU runtime 

## 3. Description

Looking at the application domain and the type of data, after several tests I realized that it would be more appropriate to use a RNN (particularly useful in time series), in particular the LSTM architecture has proved more performant.

#### Architecture 
![Neural Network architecture](https://github.com/AlessandroPaparella/BR-transaction-classifier/blob/main/NN_architecture.png "Neural Network architecture")

### 3.1


### 3.2 Files

## 4. Useful links
 * Challenge: https://alphamev.ai/ 
 * What is MEV: https://messari.io/article/understanding-mev
 * Back-running practice: https://www.mev.wiki/attack-examples/back-running
 * NN graph created with: https://netron.app/
