# Getting started Tutorial
This tutorial guides you through how to use Watson Knowledge Studio to train your own NLP services that can be used in conjunction with Discovery for domain specific data.

## Before you begin
  * Create an instance of Watson Knowledge Studio in your account.
    1. Search for Watson Knowledege Studio in the catalog. Create a service and name it.

## Step 1: Create a Model
1. Open the newly created instance of the Watson Knowledge Studio and click on 'Launch Tool'.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/WKS/Capture1.JPG)
2. Click on 'New Workspace' to create a new project and name it.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/WKS/Capture2.JPG)


## Step 2: Add Entities
1. Go to the 'Entity Types' tab in the previously created project.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/WKS/Capture3.JPG)
2. Add the entities that you would like WKS to detect from incoming text. Once filled, it should look something like this -:
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/WKS/Capture3-2.JPG)
    
## Step 3: Add Relations
1. Go to 'Relations' tab in your project.
2. Relations are the relationships between two entities that WKS can detect. For example, two entities, 'VEHICLE NUMBER' & 'VEHICLE MODEL'
can have the relation 'isAPartOf' i.e. 'VEHICLE NUMBER' is a part of 'VEHICLE MODEL'. Relations are user defined and as such can be named anything. In the below example, 'PRODUCT' can be a product of 'ORGANISATION'.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/WKS/Capture4.JPG)

## Step 4: Add a Dictionary
In the process of making a model, user has to manually label all the entities and relations in the data. In order to speed up the process of learning, you can define dictionaries which automatically label the data which is similiar in meaning. For example, IBM, International Buisness Machines, refer to the same company as such you could define them in the dictionary and they would be labeled as references. An example is shown below.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/WKS/Capture5.JPG)

## Step 5: Add Data
In order to train your model, you need text data that you can label with entities and relations. You can upload files in individual .txt format or upload them in a CSV file where the first column is the file name and second is the text in the file. 
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/WKS/Capture6.JPG)
Once you have all the data uploaded, you need to create Annotation Sets which are a combination of all your text sets. You can set how much overlap you want between the different sets you have uploaded.
![](https://github.com/shauryg/Watson-CI/blob/master/Tutorials/WKS/Capture8.JPG)

## Step 6: Human Annotation and Testing
The final part of making the model to to annotate it manually. Ideally you should have about 10 files per each entity. But since this is a tutorial, you can have as many as you want. Begin by adding a Annotation Task. Generally this is used to distribute the annotation between multiple people with 1 overseer who makes sure that the annotation style is consistent between all the human anotators. 








