**Azure Quota & Usage Insights - Overview**

* A Customized, Simple, Inclusive Re-Usable MS Excel Template – Enables users to Proactively review Azure Quota & Usage information for all the Subscriptions across a specific AAD Tenant
* The Data is extracted / derived from Azure Management REST API’s, which automatically loads the “Azure Quota & Usage Insights” Re-Usable MS Excel Template with Azure Quota & Usage information for Compute, Disks, Storage & Network Resources and Usage information for VMs & associated Disks, Web Server Farms & Sites
* To get Started, One can just Download the Azure Quota & Usage Insights Re-usable MS Excel Template…
  * Open the Template, Click ‘Enable Content’ for the ‘Security Warning – External Data Connection have been disabled’
  * Click ‘Yes’ for the ‘Security Warning – Do you want to make this file a Trusted Document’
  * Ensure the Privacy Levels for ‘Global’ & ‘Current Workbook’ under the ‘Query Options’ (Go to Data  Get Data  Query Options) are set to ‘Ignore the Privacy Levels’ 
* Authorize the connection to Azure Management API’s & ‘Refresh All’ for latest Data….
  * You only need to authorize the connection to Azure Management API’s Once for a specific AAD Tenant;
    * Ensure the Permissions to “Global permissions’ for ‘https://management.azure.com’ & ‘Data sources in current workbook’ for https://management.azure.com/subscriptions" & "https://management.azure.com/tenants under Data Source Settings (Go to Data  Get Data  Data Source Settings ) are Cleared
    * Click on Data  Refresh All  Refresh All  Select Organizational Account  Sign in to ‘https://management.azure.com/subscriptions’ at Select level as ‘https://management.azure.com/’  Connect
    * On an Information Message prompt ‘There’s already data in [xxxxx]xxxxx. Do you want to replace it?, Click ‘Yes’ 
    * Ensure the Data Refresh is completed, Click on Data  Refresh All  Refresh Status or Select PivotTable (B4 / R4C2)  PivotTable Analyze  Refresh  Refresh Status
* That’s it…You Are Done…..The Azure Quota & Usage Insights Report is Ready to be Consumed….
  * You can now view the Azure Quota & Usage information for Compute, Disks, Storage & Network Resources and Usage information for VMs & associated Disks, Web Server Farms & Sites
  * You can Refresh the Data as & when required to Ensure Latest Dataset
    * Click on Data  Refresh All  Refresh All  Refresh Status to ensure completion of Dataset Refresh or Select PivotTable (B4 / R4C2)  PivotTable Analyze  Refresh  Refresh All  Refresh Status to ensure completion of Dataset Refresh
* Prerequisites;
  * A Customer Doman Account ID (email ID) with defined RBAC (at least a Reader Role) access to all the Subscriptions across a specific AAD Tenant
  * Ensure ‘Microsoft.Capacity’ Resource provider is registered for all the Azure Subscriptions
  * Ensure access to Microsoft Excel App or Online version
* Further Step wise, One time Setup details with Snapshots, go to this doc link;
  * https://nam06.safelinks.protection.outlook.com/ap/p-59584e83/?url=https%3A%2F%2Fmicrosoftapc-my.sharepoint.com%2F%3Ap%3A%2Fg%2Fpersonal%2Fhemacn_microsoft_com%2FEe1T_5m_fQBPlM9SKPCsLEIBrtJ8-aT_p3kpAq6osEVN9g%3Fe%3DkIROM8&data=05%7C01%7Chemacn%40microsoft.com%7C1e9de399141244da53be08da84e6a3b8%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637968423425968157%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C3000%7C%7C%7C&sdata=JyvGxI3APlD090mTazQ1vPu7%2B5luMgyZciG8OiiR3qQ%3D&reserved=0

  




