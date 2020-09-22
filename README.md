# SageMaker Deployment Project

Project Overview:

 A simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker.

In the final architecture AWS API Gateway and AWS Lambda functions is used as well. The application architecture diagram is:
![](https://github.com/Vikashr21/Sagemaker-Sentiment-Analysis/Web App Diagram.svg)

#instructions
Please see the [Original README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).For the solutions only clone this repository:
		
		cd SageMaker
		git clone https://github.com/Vikashr21/Sagemaker-Sentiment-Analysis
		exit


#General Outline
Step 1: Downloading the data
Step 2: Preparing and Processing the data
Step 3: Upload the data to S3
Step 4: Build and Train the PyTorch Model
Step 5: Testing the Model
Step 6: Deploying the model for testing
Step 7: Use the model for testing
Step 6 Deploy the model for the web app
Step 7 Use the model for the web app

#Web app final result
The final project will be executed in a simple html page which can be deployed anywhere.

You will see the following:

![](https://github.com/Vikashr21/Sagemaker-Sentiment-Analysis/WebAppResult.gif)
