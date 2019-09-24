# armvirtualNetwork
Azure Resource Manager template for deploying two virtual networks across the following EU regions:

  - West Europe
  - North Europe
 
The template can be used to deploy a LAB-like environment for learning, testing and evaluation purposes. The template, uses a multi-tiered network zone architecture to ISOLATE and SEGMENT services across functional boundaries, each of which are protected by a Network Security Group firewall at the Subnet Level. Once deployed, the architecture allows for testing HA and Disaster Recovery scenarios for Web Servers, Identity Services and Databases across regions.

The template is customisable and can be used to build and generate similar network patterns within an Azure Subscription and of course can be expanded to support your unique use cases. The use of the fictitious Litware Inc company, naming conventions and IP schemas can be changed to better reflect your context and as such are not dependancies for success.

[![Deploy to Azure](https://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/) <a href="http://armviz.io/#/?load=https://https://raw.githubusercontent.com/DarrenMayes/armvirtualNetwork/master/azuredeploy.json" target="_blank"><img src="http://armviz.io/visualizebutton.png"/></a>
