# HospitalLengthOfStay

Watson Studio Local project to estimate Hospital Length of Stay.

Based on this excellent artcile:
https://towardsdatascience.com/predicting-hospital-length-of-stay-at-time-of-admission-55dfdfe69598

Note:  No data supplied with this repository, but you can get access to the data here:  https://mimic.physionet.org/gettingstarted/access/.  More information on this in the article above.

To explore these materials, register for Watson Studio on IBM Cloud:  https://ibm.biz/accelerate-ai then access Watson Studio on cloud here:  http://dataplatform.cloud.ibm.com/ .  There is no cost associated with running this project.

Then, create a project and create a new Storage instance.  Follow defaults.  Lite Plan.
In your project, go to services page.  Create 2 new services:
Create and add a new Watson Machine Learning service:  Follow defaults and lite plan

Create and add a new Spark service to your project:  Follow defaults and lite plan

Create an access token for the project.  Give it a name and add Editor privileges.

Add the ADMISSIONS.csv, DIAGNOSES_ICD.csv, ICUSTAYS.csv and PATIENTS.csv files to the project.

I have made some small adaptions, but the main objectives:

1.  use the notebook to explore and manipulate data.  Save that data to a csv file.
2.  Open the csv file in excel, remove the first column, save as a csv file.
3.  Use Watson Machine Learning to build a regression model to predict LOS (Length of Stay)
4.  Save the machine learning model and deploy it in Watson Machine Learning.
5.  Explore the deployed service.  Run a sanity check test.
6.  Explore the data set and build a regression model in SPSS Flow Editor.  Use the enclosed LOS Predictor.str file and import it into your project as a starter.  Edit the Import node and change the file to the file you created in step 2.

## Materials:

notebook for data exploration
this readme
spss modeler flow configuration (str) file

Enjoy!
Mark
