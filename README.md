Extract user list from Azure Active Directory to an excel file
==============================================================

            

Want to know about innovative and interesting ideas in Azure and automation? Check out my blog: https://manjunathrao.com/


 


This script will authenticate to your Azure Active Directory and fetch all the user details. Finally, it will save the details to the excel sheet.


 


Below are the user attributes the script fetches:


1. Display Name


2. Object ID


3. Type


4. Principal Name


5. Role Name


6. Role Description


 


The excel sheet is saved as: C:\AzureADUserList\AzureADUserList.xlsx


 


Pre-Requisites: This script needs 'MSOnline' and 'AzureRM' PowerShell modules


 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
