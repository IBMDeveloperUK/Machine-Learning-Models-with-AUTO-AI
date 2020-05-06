# Machine Learning Models with AUTO AI 

In this workshop you will learn how to build and deploy your own AI Models.

For the workshop we will be using AutoAI, a graphical tool that analyses your dataset and discovers data transformations, algorithms, and parameter settings that work best for your problem setting.

Using AutoAI, you can build and deploy a machine learning model with sophisticated training features and no coding.

We will use some public datasets to build and deploy two different model pipelines, and analyse each of these models.

## Set up

## IBM Cloud

- [Sign up](http://ibm.biz/aipredict) for an IBM Cloud account

- When you are signed up click `Create Resource` at the top of the Resources page. You can find the resources under the hamburger menu at the top left:

 ![](Images/Create_resource.png)
 
- Search for Watson Studio and click on the tile:

![](Images/Watson_Studio.png)

- Select the Lite plan and click `Create`.
- Go back to the Resources list and click on your Watson Studio service and then click `Get Started`. 

![](Images/launch.png)

## IBM Watson Studio

### 1. Create a new Project

- You should now be in Watson Studio.
- Create a new project by clicking on `Get Started` and `New Project`, or `Create Project`
- Give your Project a name.
- Select an Object Storage from the drop-down menu or create a new one for free. This is used to store the notebooks and data. **Do not forget to click refresh when returning to the Project page.**

![](Images/COS.png)

- click `Create`.  

### 2. Once you are in the Project Dashboard, click on "Add to Project" on the top right and select AutoAI Experiment 

![](Images/AutoAI.png)

### 3. Associate a Machine Learning service 

- Give your Auto AI experiment a unique name 
- Associate a Watson Machine Learning service, if you have already created one this will apear in the dropdown or you can create a new one. 
- Once this is done, click the "Reload" button for your Machine Learning service to appear 

![](Images/MLservice.png)


- Your machine learning service will appear under "Associated services"
- Click Create 
