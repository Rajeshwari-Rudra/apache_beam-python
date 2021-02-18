<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSFdAvw2XOHzl55u-rBk2XMdtGh14HiTzS1AA&usqp=CAU" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="40" height="60">
# apache_beam-python
A demo project on batch data-parallel processing using Apache Beam and Python

## Team Members
-----------------------------------------------------
<table>
  <tr>
    <td align="center"><a href="https://github.com/Rajeshwari-Rudra"><img src="https://avatars.githubusercontent.com/u/60014358?s=400&u=19b829f44dbee95ca692106697ff733c5f71ccee&v=4" width="100px;" alt=""/><br /><sub><b>Rajeshwari Rudravaram</b></sub></a><br /><a href="https://github.com/Rajeshwari-Rudra" title="Code">💻</a></td>
     <td align="center"><a href="https://github.com/sudheera96"><img src="https://avatars.githubusercontent.com/u/22390581?s=460&u=e2a3ccb663ae34048a4c2233bb9a530d2de29a9c&v=4" width="100px;" alt=""/><br /><sub><b>Sri Sudheera Chitipolu</b></sub></a><br /><a href="https://github.com/sudheera96" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/GUNDUPOOJA"><img src="https://avatars.githubusercontent.com/u/60015515?s=400&u=a691ffb3d3f0d5b6668835340aa29ca8599d7667&v=4" width="100px;" alt=""/><br /><sub><b>Pooja Gundu</b></sub></a><br /><a href="https://github.com/GUNDUPOOJA" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/nrajubn"><img src="https://avatars.githubusercontent.com/u/60019513?s=400&u=6601ccba9a28d0a3095067e657e7305603bd6dda&v=4" width="100px;" alt=""/><br /><sub><b>Raju Nooka</b></sub></a><br /><a href="https://github.com/nrajubn" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/SaiGorla"><img src="https://avatars.githubusercontent.com/u/41150392?s=460&u=a16092ba3d43983167f66442ef1f07425bfecfc3&v=4" width="100px; alt=""/><br /><sub><b>Sai Rohith Gorla</b></sub></a><br /><a href="https://github.com/SaiGorla" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Avisakula123"><img src="https://avatars.githubusercontent.com/u/60164504?s=460&u=9401e8b6d44679177550d9b4b5c574cb9100c975&v=4" width="100px; alt=""/><br /><sub><b>Rohith Reddy Avisakula</b></sub></a><br /><a href="https://github.com/Avisakula123" title="Code">💻</a></td>
        
    
  </tr>
</table>

## Introduction

Apache beam is a dataprocessing platform. Data process can either be for Analytic purpose or ETL. Also, it doesn't rely on anyone of the execution engine and data agnostic, programming agnostic.

## Working Process

![](https://raw.githubusercontent.com/Rajeshwari-Rudra/apache_beam-python/main/pipeline.png)

## Apache Beam 
- Apache Beam provides a simple, powerful programming model for building both batch and streaming parallel data processing pipelines.
- Batch pipeline : The type of pipeline used to process the data in batches.
- Streaming data pipelines : These pipelines handles millions of events at scale in real time.
- Apache Beam SDK(Software Development Kit) for python provides access to the Apache Beam capabilities using Python Programming Language.
- Using Apache Beam SDK one can build a program that defines the pipeline.

## Roles and Responsibilities 
- Raju - Ascending order
- Sri Sudheera Chitipolu - Groupby Transformation
- Rohith - Descending order
- Pooja - Word count
- Sai Rohith - Maximum count
- Rajeshwari Rudravaram - I'll be working on minimum count of a word in Dataset.

# Sri Sudheera Chitipolu
## Demonstration on GroupBy Transformation
- Apache Beam python GroupBy Transformation on [netflix_titles.csv](https://github.com/Rajeshwari-Rudra/apache_beam-python/blob/main/netflix_titles.csv)
- [Sri Sudheera's Google Colab Notebook on GroupBy Transformation](https://github.com/sudheera96/abeam_python_Groupby/blob/main/netflixGroupBy.ipynb)
- Demonstration Video: [Sri Sudheera's GroupBy Transformation on Apache Beam Python](https://use.vg/tUaEWU)
- My Personal Repo on apache beam python with README file-https://github.com/sudheera96/abeam_python_Groupby
### Prerequisites
- Apache Beam
- Python 
- Google Colab
- Kaggle for data set
### Process and Commands
- Open firefox or safari browser
- Type Google Colab
- Click on first link that is Google Colab
- Sign in with google account
- Click on notebook after appearing the window with recent

`
Note: Google Colab works similar to jupyter notebook
`

- After writing and execution of code,save file in local or Github
- Give the command to install apache beam
```powershell
!pip install --quiet -U apache-beam
```
Program
![](https://github.com/Rajeshwari-Rudra/apache_beam-python/blob/main/doc/Screenshot%20(284).png)
Output
![](https://raw.githubusercontent.com/Rajeshwari-Rudra/apache_beam-python/main/doc/Screenshot%20(285).png)

#### References
- [Apache Beam Group By](https://beam.apache.org/documentation/transforms/python/aggregation/groupby/)
- [Kaggle data set](https://www.kaggle.com/shivamb/netflix-shows)
- [Apache Beam Colab](https://colab.research.google.com/github/apache/beam/blob/master/examples/notebooks/get-started/try-apache-beam-py.ipynb)


# Rajeshwari Rudravaram

## Sub-topic : Minimal Word Count
-------------------------------------------------------
* I have worked on "Minimal Word Count" for the file 'key_benifits.csv' of Shopify app store.
* The dataset, I have choosen is Kaggle. Here is the link [Shopify app store](https://www.kaggle.com/usernam3/shopify-app-store)
* I have choosen the Google colaboratory to run the code.

## Steps followed by me
- I have imported the apache beam as an alias beam in Google colab notebook.


## Prerequisites
- Apache Beam
- Python
- Google Colab 

### Commands to check the versions on your machine
```powershell
python --version
```
```powershell
pip --version
```
- Note:- Python must be greater than 3.6.0

## Command to install Apache beam 
```powershell
python -m pip install apache-beam
```
## Command to install executive engines 
```powershell
pip install apache-beam[gcp,aws,test,docs]
``` 

## Dataset
* [Kaggle](https://www.kaggle.com/)
* [Apache Beam Documentation](https://beam.apache.org/get-started/quickstart-py/)
* [Google Colab](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb)

# Pooja Gundu
## Sub-topic : WordCount
- I have worked on "Word Count" for the file 'superbowl-ads.csv' This file contains data about all advertisements shown during the Super Bowl(most watched US Program) across the years from 1967 to 2020.
* The dataset, I have choosen is Kaggle. Here is the link [superbowl-ads.csv](https://www.kaggle.com/prondeau/superbowlads)
* I have choosen the Google colaboratory to run the code.
- [Pooja's Google Colab Notebook on wordcount Transformation](https://github.com/GUNDUPOOJA/apache_beam_python-wordcount/blob/main/superbowl_ads.ipynb)
- Demonstration Video: 
- My Personal Repo on apache beam python with README file - https://github.com/GUNDUPOOJA/apache_beam_python-wordcount



