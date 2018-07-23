Use IBM’s Watson Studio to create machine learning models and applications. Participants will be led through 4 labs (time permitting). All use the Titanic data set, a common one used in Kaggle competitions.  

1. [Lab-1](https://github.com/bleonardb3/AA/tree/master/Lab-1) - The first lab will use the Watson Machine Learning capability to create a machine learning model based on the Titanic data set. The model will be deployed in the IBM Cloud, and an application will be built that uses the deployed machine learning model to predict survivability given passenger characteristics.

1. [Lab-2](https://github.com/bleonardb3/AA/tree/master/Lab-2) - The second lab will guide participants in using the Watson Studio SPSS Modeler capability to explore, prepare, and model passenger data from the Titanic. The SPSS Modeler is a drag and drop capability to build machine learning pipelines.   

1. [Lab-3](https://github.com/bleonardb3/AA/tree/master/Lab-3) - The third lab features the Data Refinery tool, a fully managed self-service data preparation facility. 

1. [Lab-4](https://github.com/bleonardb3/AA/tree/master/Lab-4) - The fourth lab will leverage Spark machine learning (SparkML) in a Jupyter notebook to predict survivability using pyspark and a supervised learning model.

## Instructions: Create a Watson Studio project and set up the required services. 

### Step 1.  Log into your [Watson Studio](http://datascience.ibm.com/) account, then select `View All Projects`.

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Select%20View%20All%20Projects.png"/>

### Step 2.  If you have an existing project from following the signup instructions then select it, and skip to Step 8.  Otherwise, click on `New Project`. 
> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Select%20New%20Project.png"/>

### Step 3. Enter the project name (eg. Watson Studio Labs), optionally a description, and then click on `Add` in the Storage section. Note if you have already provisioned cloud object storage (you shouldn't see an Add button) , then just click on the `Create` button, and skip to Step 8. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/New%20Project%20Panel%20-%20Add%20Storage.png"/>

### Step 4. Click on the Lite plan, and then click on `Create`. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Create%20Object%20Storage.png"/>

### Step 5. Optionally change the storage name, and then click on `Confirm`

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Confirm%20Creation.png"/>

### Step 6. Click on `Refresh`. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Click%20Refresh.png"/>

### Step 7.  The cloud object storage should appear. Now click on `Create`. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Click%20Project%20Create.png"/>

### Step 8. 

The labs in this Proof of Technology will require the following services to be created and associated with your project. 
1. Object Storage
1. Watson Machine Learning
1. Apache Spark  

The Object Storage service instance should already exist, having been created when the Watson Studio Labs (or whatever you named it) project was created. Both the Watson Machine Learning service, and the Apache Spark service need to be created and then associated with the project.  

### Step 9.  Click on the project `Settings` tab.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Settings.png"/>

### Step 10. Scroll down to `Associated Services`, then select `Add service` and select `Watson`.

> <img src="https://github.com/bleonardb3/WatsonStudio/blob/master/images/SelectWatsonService.png"/>

### Step 11. Select the `Machine Learning` service 

> <img src="https://github.com/bleonardb3/WatsonStudio/blob/master/images/SelectMachineLearningService.png"/>

### Step 12. Select `New`.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20New%20Service.png"/>

### Step 13. Select the `Lite` plan. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Lite%20ML.png"/>

### Step 13. Scroll down and click `Create`, then change the `Service name` to `Machine Learning` in the `Confirm Creation` panel and click `Confirm`.  

> <img src="https://github.com/bleonardb3/WatsonStudio/blob/master/images/ConfirmMachineLearningCreation.png"/>

### Step 14. The Machine Learning service that you created should now appear in `Associated Services`. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/See%20ML%20in%20Associated%20Services..png"/>

### Step 15. Follow the same process as in steps 10-14, except this time add a Spark service. 


