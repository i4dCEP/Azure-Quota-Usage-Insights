Azure Quota & Usage Insights - Overview
![image](https://user-images.githubusercontent.com/96905217/186290898-8bfec30b-2bc5-4b88-8c0c-96dc0222fcc2.png)
Azure Quota & Usage Insights
A Customized, Simple, Inclusive Re-Usable MS Excel Template – Enables users to Proactively review Azure Quota & Usage information for all the Subscriptions across a specific AAD Tenant
The Data is extracted / derived from Azure Management REST API’s, which automatically loads the “Azure Quota & Usage Insights” Re-Usable MS Excel Template with Azure Quota & Usage information for Compute, Disks, Storage & Network Resources and Usage information for VMs & associated Disks, Web Server Farms & Sites
To get Started, One can just Download the Azure Quota & Usage Insights Re-usable MS Excel Template…
Open the Template, Click ‘Enable Content’ for the ‘Security Warning – External Data Connection have been disabled’
Click ‘Yes’ for the ‘Security Warning – Do you want to make this file a Trusted Document’
Ensure the Privacy Levels for ‘Global’ & ‘Current Workbook’ under the ‘Query Options’ (Go to Data  Get Data  Query Options) are set to ‘Ignore the Privacy Levels’ 
Authorize the connection to Azure Management API’s & ‘Refresh All’ for latest Data…. 
You only need to authorize the connection to Azure Management API’s Once for a specific AAD Tenant;
Ensure the Permissions to “Global permissions’ for ‘https://management.azure.com’ & ‘Data sources in current workbook’ for https://management.azure.com/subscriptions" & "https://management.azure.com/tenants under Data Source Settings (Go to Data  Get Data  Data Source Settings ) are Cleared
Click on Data  Refresh All  Refresh All  Select Organizational Account  Sign in to ‘https://management.azure.com/subscriptions’ at Select level as ‘https://management.azure.com/’  Connect
On an Information Message prompt ‘There’s already data in [xxxxx]xxxxx. Do you want to replace it?, Click ‘Yes’ 
Ensure the Data Refresh is completed, Click on Data  Refresh All  Refresh Status or Select PivotTable (B4 / R4C2)  PivotTable Analyze  Refresh  Refresh Status
That’s it…You Are Done…..The Azure Quota & Usage Insights Report is Ready to be Consumed….
You can now view the Azure Quota & Usage information for Compute, Disks, Storage & Network Resources and Usage information for VMs & associated Disks, Web Server Farms & Sites
You can Refresh the Data as & when required to Ensure Latest Dataset
Click on Data  Refresh All  Refresh All  Refresh Status to ensure completion of Dataset Refresh or Select PivotTable (B4 / R4C2)  PivotTable Analyze  Refresh  Refresh All  Refresh Status to ensure completion of Dataset Refresh
Prerequisites;
A Customer Doman Account ID (email ID) with defined RBAC (at least a Reader Role) access to all the Subscriptions across a specific AAD Tenant
Ensure ‘Microsoft.Capacity’ Resource provider is registered for all the Azure Subscriptions
Ensure access to Microsoft Excel App or Online version
Further Slides will provide Step wise, One time Setup details with Snapshots….
![image](https://user-images.githubusercontent.com/96905217/186290918-784cda37-a2a2-4a68-9f26-20e71a21b02c.png)
