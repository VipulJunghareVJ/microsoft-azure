# Future-Ready-Talent-MY-Project
# The Tour Portal-project
# Web App project
Final Project Submission for Microsoft Future-Ready-Talent
Portal for Travel Guide
A company wants to deploy a website in Azure cloud
Problem Statement: An e-commerce company wants to build a sample Front End portal website for traveling guide as the people needs guidance for which places to visit. So we have challenges to build a whole website they have chosen Azure Cloud Platform. Build a website that have: Home Page, Different Places detail Page, Registration page.
Project Description: Core Idea of Project is to build an sample react portal Website for student with the help of HTML, CSS, JAVASCRIPT, Static Web Apps. The primary goal of sample portal is for traveling guide that shows citys that a company can make them visit, which places to be visited in that city. We are using Azure Technologies with GitHub to complete this project.

Please Find Scrrenshots of Projects in ScreenShot Folder of this repository.
Make a code:
- Complete your codding portion on your local machine or editor
- Make a repository in GitHub
- Upload code and complete repository

Deploy on Microsoft Azure:

First step is to go to Azure portal
Go to: https://portal.azure.com

Click on create Resource(+)
Select Web as categories,
On the Basics tab, 
Enter the following values for each setting.
Setting             	Value	                                                           Details
Project Details		
Subscription	Select your Subscription	The web app you are creating must belong to a resource group. Here, you select the Azure subscription to which the resource group belongs                                           (or will belong, if you are creating it within the wizard).
Resource Group	Select your resource group	  The resource group to which the static web app will belong. All Azure resources must belong to a resource group.
Static Web app details                                                                             	
Name	                                  Enter a unique name	The name of your web app. This name will be part of the app's URL: appname.azurewebsites.net. The name you choose must                                          be unique among all Azure web apps.
Plan	Type	                             Free:For hobby or personal projects                
Region	                                Select the geographical region from which your app will be hosted.
Source                                  Select Github as we will deploy from github
GitHub Account                          Click Signin with GitHub, enter credentials and connect your github account then it will shhow your Account name
Organization                            GitHubAccountName
Repository                              Name of repository where you have files/webpages 
Branch                                  by default(main) or other branch if you have

Then click on Review + create

When resource is successfully deployed click on go to resource 
On Overview page you get a URL (for ex like: https://yellow-dune-03bb44410.1.azurestaticapps.net)
Initially it will show default page of static web app then after sometime it will successfully connect and show your website.


Azure Static Web App is Software as a service(SaaS), so we don't have to manage infrastracture or platform part like you don't have to manage Virtual Machines, the infrastructure is build and manged automatically by Microsoft Azure.
Using SaaS we only have to manage Data+Access.
Builing and Deploying on Static Web App service of Micrsoft Azure is easy.

Demo of Azure Static web app: URL: https://yellow-dune-03bb44410.1.azurestaticapps.net
