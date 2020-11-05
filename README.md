# SonicWall NSv Azure Templates - HA

SonicWall NSv Active-Standby HA - Azure resource manager templates

https://www.sonicwall.com/

The following resources will be deployed:

* Virtual Network with WAN, LAN and HA subnet
* Default Network Security and default Routing Table
* Two Sonicwall NSv VMs
* Public IPs: X1 public IP addresses and a floating IP address


Deploying
=========

Marketplace deployment
--------------------------

Find the SonicWall NSv product in Azure Marketplace: https://azuremarketplace.microsoft.com/marketplace/apps?search=sonicwall

ARM template deployment
-----------------------

Press the "Deploy to Azure" button to load the ARM template into your Azure subscription. 

[![Deploy to Azure](https://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsonicwall-nsv%2Fazure-template%2Ffeature%2FHA%2FazureDeploy.json)

To find out more about ARM templates refer to https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-template-deploy#deploy-with-azure-cli

***


# License

Copyright © 2020 SonicWall, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated files (the "Software"), to utilize the Software
without restriction, including without limitation the rights to use, copy, 
modify, merge, publish, distribute, sublicense, and/or sell copies of the 
Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS OR SONICWALL BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR
THE USE OR OTHER DEALINGS IN THE SOFTWARE.

