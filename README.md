# Machine Learning Models with AUTO AI 

In this workshop you will learn how to build and deploy your own AI Models.

For the workshop we will be using AutoAI, a graphical tool that analyses your dataset and discovers data transformations, algorithms, and parameter settings that work best for your problem setting.

Using AutoAI, you can build and deploy a machine learning model with sophisticated training features and no coding.

We will use some public datasets to build and deploy two different model pipelines, and analyse each of these models.

## Set up

## IBM Cloud

- [Sign up](http://ibm.biz/odsc_ibm_aiworkshop) for an IBM Cloud account

- When you are signed up click `Create Resource` at the top of the Resources page. You can find the resources under the hamburger menu at the top left:

 ![](Images/Create_resource.png)
 
- Search for Watson Studio and click on the tile:

![](Images/Watson_Studio.png)

- Select the Lite plan and click `Create`.
- Go back to the Resources list and click on your Watson Studio service and then click `Get Started`. 

![](Images/launch.png)

## IBM Watson Studio

### Create a new Project

- You should now be in Watson Studio.
- Create a new project by clicking on `Get Started` and `New Project`, or `Create Project`


![](https://github.com/YaminiRao/Data-Visualisation-with-Python/blob/master/Images/Watson_Studio.png)


- Give your Project a name.
- Select an Object Storage from the drop-down menu or create a new one for free. This is used to store the notebooks and data. **Do not forget to click refresh when returning to the Project page.**

![](Images/COS.png)

- click `Create`.  

### Once you are in the Project Dashboard, click on "Add to Project" on the top right and select AutoAI Experiment 

![](Images/AutoAI.png)

### Associate a Machine Learning service 

- Give your Auto AI experiment a unique name 
- Associate a Watson Machine Learning service, if you have already created one this will apear in the dropdown or you can create a new one. 
- Once this is done, click the "Reload" button for your Machine Learning service to appear 

![](Images/MLservice.png)


- Your machine learning service will appear under "Associated services"
- Click Create 

### Upload your Data Sets

- In this workshop we will be analysing two Datasets 
- One to create a Classification model and the other to create a Regression Model 

- Browse and add your Data source 
- Datasets for this workshop have been acquired from : 

https://www.kaggle.com/noordeen/insurance-premium-prediction

https://github.com/IBM/predictive-model-on-watson-ml (with minor changes to original data)

https://www.kaggle.com/vikrishnan/boston-house-prices (with minor changes to original data)


![](Images/Data_Source.png)


### We will now work through the different aspects of configuring our AutoAI experiment and discuss the Classification Models that are created. 


### Deploying you Model 

- Once you select your final model pipeline. You can choose to Save it as a notebook or an ML model. 

- Choose your option and Click Save 

![](Images/MLModel.png)

- Once your model is saved, Go to the Deployments Tab and Add a Deployment 

![](Images/Deployments.png)

- Create your Deployment by giving it a unique name

- Once the status changes from initializing to "Ready" click on the Model name to test your model 

![](Images/Click.png)

- You can now test your model by providing input Data via the form or in a JSON format 
![](Images/Predict.png) 


