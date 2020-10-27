Authenticate to Azure using Azure RunAs account.
================================================

            

This runbook authenticates to Azure using the built in Azure RunAs account. It should be called from a parent runbook to easily authenticate against Azure before calling Azure activities. If an optional subscription id is not passed in, then the subscription
 id of where the automation account exists will be used.


Exceptions are converted to errors so that they can be handled using the error activity if required. It currently just returns the exception that was thrown by an activity.



![Image](https://github.com/azureautomation/authenticate-to-azure-using-azure-runas-account./raw/master/authenticaterunas.png)


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
