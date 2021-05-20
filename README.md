# MLEND Project3-BCN Bicing Usage

## Introduction
The repo includes the code and relevant information for the implementation of a predictor for the usage of bicycle sharing system of Barcelona within the AWS Sagemaker platform.

## Description
The code consists of two jupyter notebooks:
* Data Analysis: collecting and processing the data from the [OpenDataBCN](https://opendata-ajuntament.barcelona.cat/es). The data are also converted and saved in json files. 
* Predictor: loading the data files to then performs training and test of a Deep AR model.

The first Jupyter notebook can execute outside AWS, as it does not require any Sagemaker library. The raw data source consists of .csv file that are not included in this repo but they can be downloaded at the following links: [Stations](https://opendata-ajuntament.barcelona.cat/data/ca/dataset/bicing) and [Usage](https://opendata-ajuntament.barcelona.cat/data/ca/dataset/us-del-servei-bicing).
The Predictor requires sagemaker and must be imported as a Notebook Instance in Amazon Sagemaker.

## Library Versions
The project was developed using the following library versions:
* Sagemaker 2.41.0
* pandas 1.2.4
* matplotlib 3.4.2
