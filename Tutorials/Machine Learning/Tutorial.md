# Getting started Tutorial
This tutorial guides you through how to use Watson Studio and Machine Learning in IBM Watson™ to make classifications based on Numerical Data.

## Before you begin
  * Create an instance of Watson Studio in your account.
    1. Search for Watson Studio in the catalog. Create a service and name it.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/Machine%20Learning/Pics/name_WS_instance.PNG "Logo Title Text 1")
  * Make sure you have your Cloud Storage Set up.

## Step 1: Create a Project
1. Open the newly created instance of the Watson Studio and click on 'Get Started'.
2. Click on 'New Project' to create a new project and name it.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/Machine%20Learning/Pics/Create_New_Project.PNG "Logo Title Text 1")

## Step 2: Add Machine Learning and Spark Instances
1. Go to the 'Settings' tab in the previously created project.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/Machine%20Learning/Pics/Create_New_Project.PNG "Logo Title Text 1")
  * #### Add Machine Learning
    1. Scroll down to 'Associated Services' tab and click on 'Add Service' and select 'Watson'
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/Machine%20Learning/Pics/Add_Service_MachineLearning.PNG "Logo")
    2. Select Machine Learning in the window that pops up.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/Machine%20Learning/Pics/MachineLearning.PNG "Logo Title Text 1")
    3. Create a new instance of Machine Learning or select a previously created one from the options.
    4. The ML service should now show up in the 'Associated Services' tab.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/Machine%20Learning/Pics/Added_MachineLearning.PNG "Logo Title Text 1")
  * #### Add Spark Instance
    1. Scroll down to 'Associated Services' tab and click on 'Add Service' and select 'Spark' 
    2. Create a new instance of Spark or select a previously created one from the options.
    3. The Spark service should now show up in the 'Associated Services' tab.    
    
## Step 3: Create a New Model
1. Go to 'Assets' tab in your project and scroll down to Watson Machine Learning Models.
2. Click on 'New Watson Machine Learning model'. Select the Machine Learning service and the Spark service that we created in the previous steps. Select Manual on data preperation option.
 ![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/Machine%20Learning/Pics/Create%20a%20Model.PNG "Logo Title Text 1")
