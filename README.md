# Simple DevOps Project

### Purpose:
By following this repository we can able to setup a DevOps CI/CD Pipeline to build and deploy a java application.
git- For local Version Control System.
github -As distrubuted version Control System.
Jenkins- As Continous Integration Tool.
Maven- As a build tool.
Ansible- Ansible For Configuration Management and deployment.
Docker- For Containerization.
Kubernetes-for Container management Tool.

We will setup all this enviromnent in AWS, usually we have source code with developer and developer commit that code on distributed version control system that is github ,now we have to build this code that is we have continous Integration tool called jenkins that pull the code from github and build with the help of Maven ,This process is nothing but Continous Integration. Once jenkins build the code it generate Artifact (webapp.war file) ,now we have deploy it in target environment so the tool to deploy artifact in target environment is we use ansible as deployment tool ,This process is nothing but Continous Delivery.
we are going to deploy our application on three different kind of target environment, Initially we have to deploy in virtual machine ,second one is in docker container, atlast in kubernetes cluster.
For this we going to set up CI/CD pipeline with the help of Github,jenkins,maven, and Tomcat.
