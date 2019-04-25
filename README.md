# Project Demo4


# Deployment Project Demo4
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-vm-simple-linux%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


Use the template
PowerShell

New-AzResourceGroup -Name <resource-group-name> -Location <resource-group-location> #use this command when you need to create a new resource group for your deployment
New-AzResourceGroupDeployment -ResourceGroupName <resource-group-name> -TemplateUri https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/zabbix-monitoring-cluster/azuredeploy.json



 <div class="row column">
        <h3>Use the template</h3>
        <h4 class="text-heading5">PowerShell</h4>
        <pre class="copy-to-clipboard prettyprint lang-powershell">New-AzResourceGroup -Name <span class="nocode">&lt;resource-group-name&gt;</span> -Location <span class="nocode">&lt;resource-group-location&gt;</span> #use this command when you need to create a new resource group for your deployment<br />New-AzResourceGroupDeployment -ResourceGroupName <span class="nocode">&lt;resource-group-name&gt;</span> -TemplateUri <span class="nocode">https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/zabbix-monitoring-cluster/azuredeploy.json</span></pre>
        <a class="arrowLink" href="/en-us/documentation/articles/powershell-install-configure/">Install and configure Azure PowerShell</a>
    </div>





## Continuous Integration ![image](https://dev.azure.com/DP157DevOps/Demo4MiniMooBookStore/_apis/build/status/Continuous%20Integration?branchName=master)
## Continuous Delivery ![image](https://vsrm.dev.azure.com/DP157DevOps/_apis/public/Release/badge/52752702-e31c-4a1b-9602-855eab975bfd/4/10)
## Continuous Deployment ![image](https://vsrm.dev.azure.com/DP157DevOps/_apis/public/Release/badge/52752702-e31c-4a1b-9602-855eab975bfd/6/12)



## Goal project "Demo4" 
The Main Goal is to prepare fully automated solution to deploy ASP.NET MVC application to the MS Azure. As a CI service Azure DevOps should be used. As a PaaS cloud provider MS Azure AppServices should be used.

#	Background
##	System Overview
iSmartBook Corp. is a small company. As its primary business is to develop and support word wide online book store including web site and mobile application. 
The company was established in 2015 as a small portal for users who likes to read books and share their expressions. Currently it has grown globally and run their own online book store in the US. Company has plans to expand their services globally in the Europe and Asia as well.
The intent of this project is to developing cloud based online book store.
##	Business Case
The intent of this project is to developing cloud based online book store:
•	Data managers should be able to add book entry via admin panel including book file, basic information about the book: author, year, description. Preferable way to keep books is secure blob storage. 
•	Customers should be able to view general book information and also add chosen book to the Cart.
•	Preferable stack is ASP.NET MVC , MS SQL and Azure Cloud.

##	Technology stack Description
### Development tools:
•	MS Visual Studio 2017
•	ASP.NET Core MVC Framework 
•	Entity Framework Core 2.1.1
### CI/CD service :
•	Azure DevOps Pipelines
### Deployment service :
•	Azure AppServices;
•	Azure SQL
•	Azure Insights



### Environment Diagram
![image](https://github.com/vitalidn/Demo4/blob/master/images/01.jpg)

### Deployment Diagram
![image](https://github.com/vitalidn/Demo4/blob/master/images/02.jpg)







