﻿Stop Azure Classic VMs
======================

            

This PowerShell Workflow runbook connects to Azure and stops all classic VMs in an Azure subscription or cloud service.    You can attach a schedule to this runbook to run it at a specific time.  


**Requirements**


1. An Automation variable asset called 'AzureSubscriptionId' that contains the GUID for this Azure subscription.  To use an asset with a different name you can pass the asset name as a runbook input parameter or change the default value for the input
 parameter. 


2. An Automation credential asset called 'AzureCredential' that contains the Azure AD user credential with authorization for this subscription.  To use an asset with a different name you can pass the asset name as a runbook input parameter or change
 the default value for the input parameter.


**Runbook content**


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
