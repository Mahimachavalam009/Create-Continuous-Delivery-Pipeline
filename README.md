# Overview : 

![image](https://github.com/user-attachments/assets/6c2c422c-f184-4ea2-b7d0-740e4e567954)

 1. Set up a GitHub repository for the application code
 2. Create an AWS Elastic Beanstalk environment to deploy the application
 3. Configure AWS CodeBuild to build the source code from GitHub
 4. Use AWS CodePipeline to set up the continuous delivery pipeline with source, build, and deploy stages

# Step 1
A. Fork a GitHub repository to create a new one

B. Store code and metadata in GitHub

C. Interact with a code repository using Git


We have created a code repository containing a simple web app. We will be using this repository to start our continuous delivery pipeline. It's important to set it up properly so we push code to it.


![image](https://github.com/user-attachments/assets/3b31d8df-8d39-4cab-bed0-7451edd5d243)

Clone the repo :

![image](https://github.com/user-attachments/assets/d3d0e513-20d5-418f-afda-4432dab467cf)

make changes in the app.js : 

```
git add app.js
git commit -m "change message"
```

now push the clean code :

```
git push
```

![image](https://github.com/user-attachments/assets/7e0b1c1a-c3a0-4b66-aa72-a3e3756976c2)



Test your changes : 

Choose the app.js file. The contents of the file, including your change, should be displayed.

# Step 2 : 

A. Configure and create an AWS Elastic Beanstalk environment

B. Deploy a sample web app to AWS Elastic Beanstalk

C. Test the sample web app 

# Key concepts

AWS Elastic Beanstalk - A service that makes it easy to deploy your application on AWS. You simply upload your code and Elastic Beanstalk deploys, manages, and scales your application.

Environment - Collection of AWS resources provisioned by Elastic Beanstalk that are used to run your application.

EC2 instance - Virtual server in the cloud. Elastic Beanstalk will provision one or more Amazon EC2 instances when creating an environment.

Web server - Software that uses the HTTP protocol to serve content over the Internet. It is used to store, process, and deliver web pages.

Platform—Combination of operating system, programming language runtime, web server, application server, and Elastic Beanstalk components. Your application runs using the components provided by a platform.

# Configure AWS Elastic beanstalk app

![image](https://github.com/user-attachments/assets/9309dd13-bab6-411e-b514-d28de3ab202b)

work in progress

