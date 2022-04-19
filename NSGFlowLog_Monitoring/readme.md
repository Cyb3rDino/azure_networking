# Workbook for Monitoring NGS Flow Logs

To Deploy the Template Klick -> **"Deploy to Azure"** <br>

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FCyb3rDino%2Fazure_networking%2Fmain%2FNSGFlow_Monitoring%2Fwbt_nsgflow_monitoring.json)
<br>
Adapted workbook with the basics from [JamesDLD](https://github.com/JamesDLD/AzureRm-Template/tree/master/Create-AzWorkbookNetwork). <br>

## Setup

1. To start using the Workbook, Network Security Group - FlowLog mus be enabled. And reporting to LogAnalytics Workspace must be also active.
[How to Enable Azure FlowLogs](https://docs.microsoft.com/de-de/azure/network-watcher/network-watcher-nsg-flow-logging-portal)

2. The LogAnalyticsWorkspace which contains the FlowLogs must be marked -> See Picture <br>
![SelectLAWS](https://github.com/Cyb3rDino/azure_networking/blob/27fa42cca2aac24a856273e6a2d3414f29a742d9/ExpressRoute_Monitoring/SelectLAWS.PNG)

