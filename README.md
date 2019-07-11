# Welcome to IBM WATSON Virtual Recognition Porject
We will utilize IBM Watson Visual Recognition (VR) to upload and classify our images. Watson VR is a service that uses deep learning algorithms to identify objects, faces and other content in an image. 

**Follow the steps below to complete this project.**

**PLEASE NOTE:-** You need an IBM Cloud Account to access the tools demonstrated below.

## Create an IBM Cloud Account
Click on the link below to create an IBM cloud account:

[Sign Up for IBM Watson Visual Recognition on IBM Cloud](https://cloud.ibm.com/)

## Login into your IBM Cloud 
Once created an account confirm the email and login using your IBMid and Password *IBMid in most cases is your email id*. Then go to your Dashboard.

## Create a New Resourse
On your dashboard page, click on the **Create a resource** on the top right to create a new source.
<img width="932" alt="create resource" src="https://user-images.githubusercontent.com/47359757/61061322-a328ab80-a419-11e9-8391-c03a678adf50.PNG">

## Create a WATSON Studio Resource
On the **Catalog page**, select the **AI** category from the left pane, and then select the **Watson Studio** resource.
<img width="942" alt="watsonai" src="https://user-images.githubusercontent.com/47359757/61061518-0581ac00-a41a-11e9-93e4-1e5f27828a10.PNG">

On the next page, you will get to name your service instance and choose your region. Click on the arrow to reveal the drop-down menu of regions. Make sure to select the region that is closest to you. Since I am located in Delhi, then I am choosing London as my region since it is the closest region to me.
<img width="932" alt="watsonregion" src="https://user-images.githubusercontent.com/47359757/61061710-6315f880-a41a-11e9-93d2-9c0e4ae58fe7.PNG">
Then scroll down and make sure that the **lite** plan is selected, and click the **Create button**.
<img width="947" alt="watsoninstange" src="https://user-images.githubusercontent.com/47359757/61061890-c43dcc00-a41a-11e9-9488-0fba48680e8e.PNG">
On the next page, click the Get Started button to start using Watson Studio.
![watsonjio](https://user-images.githubusercontent.com/47359757/61062000-fbac7880-a41a-11e9-898d-6a117ee2cd8c.png)

This will start provisioning your Watson Studio instance.

![watsonsi](https://user-images.githubusercontent.com/47359757/61062076-2bf41700-a41b-11e9-8ed8-817d1dffc354.png)
Once the provisioning process is complete, click the **Get Started** button to start using Watson Studio

## Create a Project
Once you land on the IBM Watson Studio main page, start by creating a project.
![watsonil](https://user-images.githubusercontent.com/47359757/61062211-665db400-a41b-11e9-8733-36c5b2595264.png)
Create a **Visual Recognition project**.
![watsonkil](https://user-images.githubusercontent.com/47359757/61062271-87260980-a41b-11e9-9415-8ff24c0c821f.png)
The closer this region is to your actual location, the faster images can be classified. If you're not sure which to choose, go ahead and select **US South**.
<img width="648" alt="watsonus" src="https://user-images.githubusercontent.com/47359757/61062345-b2a8f400-a41b-11e9-82c3-9ae212645c29.png">

## Setting up your Project
Now let's fill in some project details and click **Create**. The IBM Cloud Object Storage, which provides you storage for your images, should be automatically created for you.
<img width="768" alt="watsona" src="https://user-images.githubusercontent.com/47359757/61062920-b7ba7300-a41c-11e9-912d-aad39b4940d7.png">

## Selecting Built-in Models for Watson Visual Recognition
After creating your project, by default, you will land on the page where you can create your own custom models to classify objects -- but let's skip this step. Instead, let's use some existing image classification models that Watson Visual Recognition comes with by default!

To access the built-in models, click on the name of the service, as seen in the red box below:
<img width="1144" alt="watsonw" src="https://user-images.githubusercontent.com/47359757/61063020-e5072100-a41c-11e9-809e-fd38d6646c97.png">

## Choose the General model.
Now you can see all the built-in image classification models that IBM Watson provides! Let's try the **General** model.
<img width="946" alt="watsonb" src="https://user-images.githubusercontent.com/47359757/61063158-14b62900-a41d-11e9-98b1-d26e5f153515.png">

## Try out the General model
To test the General model, click on **Test**.
<img width="906" alt="watsonc" src="https://user-images.githubusercontent.com/47359757/61063235-3ca58c80-a41d-11e9-883e-2d54fdc43845.png">

## Upload Your Images!
Now you can upload any images you'd like by clicking on **Browse**.
<img width="800" alt="watsonimage" src="https://user-images.githubusercontent.com/47359757/61063403-8aba9000-a41d-11e9-829b-8e1c12a7a6cd.PNG">

## Check Out the Results!
Once you have uploaded your images, Watson Studio Visual Recognition will tell you what it thinks it found in your images! Beside each class of object (or color, age, etc.), it will also give you a confidence score (between 0 and 1) on how confident it thinks it found that particular object in your image (0 for lowest confidence and 1 for highest confidence).

<img width="810" alt="IBM WATSON" src="https://user-images.githubusercontent.com/47359757/61063473-a0c85080-a41d-11e9-86b5-ddcf6de98ee0.PNG">

**IF YOU WANT YOU CAN FILTER YOUR RESULTS TO BEST IDENTIFY THE CLASSIFIERS** 








