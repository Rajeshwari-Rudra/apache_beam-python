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
- Pooja Gundu - I will be working on word count of a word in a Dataset taken from Kaggle.
- Sai Rohith - Maximum count
- Rajeshwari Rudravaram - I'll be working on minimum count of a word in Dataset.

<img src="https://avatars.githubusercontent.com/u/22390581?s=460&u=e2a3ccb663ae34048a4c2233bb9a530d2de29a9c&v=4" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="110" height="120">
     
# Sri Sudheera Chitipolu [![](https://img.shields.io/badge/Github-Sudheera96-orange)](https://github.com/sudheera96)

[![](https://img.shields.io/badge/Github-Sudheera96%20Commits-orange)](https://github.com/Rajeshwari-Rudra/apache_beam-python/commits?author=sudheera96) [![](https://img.shields.io/badge/Github-Sudheera96%20Issues-orange)](https://github.com/Rajeshwari-Rudra/apache_beam-python/issues?q=is%3Aissue+is%3Aclosed+author%3Asudheera96)

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

<img src="https://avatars.githubusercontent.com/u/60014358?s=400&u=19b829f44dbee95ca692106697ff733c5f71ccee&v=4" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="110" height="120">
# Rajeshwari Rudravaram [![](https://img.shields.io/badge/Github-Rajeshwari-Rudra)](https://github.com/Rajeshwari-Rudra)


## Sub-topic : Minimal Word Count
-------------------------------------------------------
* I have worked on "Minimal Word Count" for the file 'key_benifits.csv' of Shopify app store.
* The dataset, I have choosen is Kaggle. Here is the link [Shopify app store](https://www.kaggle.com/usernam3/shopify-app-store)
* I have choosen the Google colaboratory to run the code.

## Key Concepts for this Project:
1. Reading data from text file
2. Specifying 'inline' transforms
3. Counting a PCollection
4. Writing data to text file


##  Demonstration on Minimal Word Count
- Apache Beam python Minimal Word Count Transformation on [Key_benifits.csv](https://github.com/Rajeshwari-Rudra/apache_beam-python/blob/main/key_benefits.csv)
- [Rajeshwari Rudravaram's Google colab notebook on Minimal word count](https://github.com/Rajeshwari-Rudra/apache_beam-python/blob/main/minimal_word_count.ipynb)
- [Output of the Minimal Word Count](https://github.com/Rajeshwari-Rudra/apache_beam-python/blob/main/output.txt)
- Video link on Demonstration of my project


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
## Guiedlines for Minimal Word Count

- Installation of Apache Beam on Colab notebook and upload the input file to notebook
![](https://github.com/Rajeshwari-Rudra/apache_beam-python/blob/main/doc/command0.png)

- Importing required libraries and run the following commands
![](https://github.com/Rajeshwari-Rudra/apache_beam-python/blob/main/doc/command1.png)

- To check the list of files on your notebook
![](https://github.com/Rajeshwari-Rudra/apache_beam-python/blob/main/doc/command3.png)

- command to add the result to output file
![](https://github.com/Rajeshwari-Rudra/apache_beam-python/blob/main/doc/command4.png)


## References

* [Kaggle](https://www.kaggle.com/)
* [Apache Beam Documentation](https://beam.apache.org/get-started/quickstart-py/)
* [Google Colab](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<img src="https://avatars.githubusercontent.com/u/60015515?s=400&u=a691ffb3d3f0d5b6668835340aa29ca8599d7667&v=4" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="110" height="120">
     
# Pooja Gundu [![](https://img.shields.io/badge/Github-GUNDUPOOJA)](https://github.com/GUNDUPOOJA)
## Sub-topic : WordCount
- I have worked on "Word Count" for the file 'superbowl-ads.csv' This file contains data about all advertisements shown during the Super Bowl(most watched US Program) across the years from 1967 to 2020.
* The dataset, I have choosen is Kaggle. Here is the link [superbowl-ads.csv](https://www.kaggle.com/prondeau/superbowlads)
* I have choosen the Google colaboratory to run the code.
- [Pooja's Google Colab Notebook on wordcount Transformation](https://github.com/GUNDUPOOJA/apache_beam_python-wordcount/blob/main/superbowl_ads.ipynb)
- Demonstration Video: []()
- My Personal Repo on apache beam python with README file - https://github.com/GUNDUPOOJA/apache_beam_python-wordcount

## Prerequisites
- Apache beam
- Google Colab 
- Google drive account
- Python

## Process and the commands used 
- Create a google colab account and open a new notebook, rename it as you required.
- First, install the apache-beam using the below command
```
!pip install --quiet -U apache-beam
```
![]()

- Also, install all the dependencies(executive engines)required using the command
```
!pip install apache-beam[gcp,aws,test,docs]
```
![]()

- Program that performs the word count operation
![]()

- output of the program
![]()

- The command that lists all the files
```
! ls
```
![]()

- First upload your .csv file to your google drive account. The email used should be same for both google drive and google Colab accounts.

- Import the .csv file run the below commands otherwise you will get file not found error because it is not imported into google colab.
![]()
```
# Code to read csv file into colaboratory:
!pip install -U -q PyDrive
from pydrive.auth import GoogleAuth
from pydrive.drive import GoogleDrive
from google.colab import auth
from oauth2client.client import GoogleCredentials
```
```
# Autheticate E-Mail ID
auth.authenticate_user()
gauth = GoogleAuth()
gauth.credentials = GoogleCredentials.get_application_default()
drive = GoogleDrive(gauth)
```

- To get the id of the file, right-click on the file in google drive account, select share link option, then copy the link.
- Remove the part that contains https://
- keep only the id part.

```
# Get File from Drive using file-ID
# Get the file
downloaded = drive.CreateFile({'id':'1b73yN7MjGytqSP5wimYAQmtByOvGGe8Y'}) # replace the id with id of file you want to access
downloaded.GetContentFile('superbowl-ads.csv') 
```


- Command to add the result to a output file
```
!cat output.txt-00000-of-00001 # output file
```
![]()

## References 
- [Google Colab](https://colab.research.google.com/github/apache/beam/blob/master/examples/notebooks/get-started/try-apache-beam-py.ipynb)
- [Kaggle](https://www.kaggle.com/)
- [Apache-beam](https://colab.research.google.com/github/apache/beam/blob/master/examples/notebooks/get-started/try-apache-beam-py.ipynb)
- [Youtube Video shows how to import files to google colab](https://www.youtube.com/watch?v=oqMImCeXi6o)




