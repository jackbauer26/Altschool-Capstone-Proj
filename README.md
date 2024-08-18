# Altschool-Capstone-Proj
A project that describes a microservices-based architecture application, deployed on Kubernetes and with a need to create a clear IaaC (Infrastructure as Code) deployment to be able to deploy the services in a fast manner.   

## Requirements

- First of all, create an account on a cloud provider, this can either be an AWS or Azure account or any other cloud provider
- Install an IDE of choice such as a VS Code, Atom or any other one of choice
- Ensure that an appropriate CLI depending on what cloud provider is being used is installed. In my case, an Azure CLI is installed for configuration.
- Other requirement include kubectl, helm, and terraform
- Clone the required repo and inside the repo https://github.com/microservices-demo/microservices-demo/tree/master, the required files can be found in the kubernetes folder under in another folder named deploy. 
- Using the github student pack, create a domain name on NameCheap. If you do not have a student pack, you can as well purchase a domain name

## Start
Create a project folder in your preferred IDE, in my case, I used the VS Code and named my project folder as Altschool-Capstone-Proj. In this folder, launch your azure CLI and log in by connecting to you azure account with the command below

> Step 1 >  ```az login```

After  we type the command above, we'll be prompted to connect to our Azure Portal account which will be used to run the project as evident in the screenshot below

![Alt text](assets\asset_az_login.png)

> Step 2 > `terraform init`

With the terraform init command, we initialize out project file to run terraform commands. This command allows our system or project understand that we're about running terraform commands to create our resources as an IaC tool

![Alt text](assets\asset_tf_init.png)


> Step 3 > `terraform plan`

This is the next step after initializing your project file with terraform init

![Alt text](assets\assets_tf_plan.png)

> Step 4 > `terraform apply`

![Alt text](assets\assets_apply.png)
