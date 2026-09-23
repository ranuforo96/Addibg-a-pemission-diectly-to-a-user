# Adding-a-pemission-diectly-to-a-user
Steps to add a permission to a user

From your root account, search for and navigate to IAM
<img width="962" height="1080" alt="image" src="https://github.com/user-attachments/assets/118c6d3d-bca2-4270-b1a2-31e2681497b1" />
Select IAM users in the left navigation pane
<img width="981" height="1080" alt="image" src="https://github.com/user-attachments/assets/9878ea04-9098-41d3-bd77-e6a005416b77" />
Right-click the user you want to add the permission to
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/89e574b8-d929-464c-b66b-93f8d5545ae2" />
From here, select the drop-down section for Add permissions and select add permissions
<img width="964" height="1076" alt="image" src="https://github.com/user-attachments/assets/382def94-48d4-430e-8288-9be635a67d4f" />
You are then taken to a page that gives you three options "Add user to group", "Copy permissions", and "Attach policies directly" select Attach policies directly
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/925b0c9c-b301-49ad-b4d8-559853ac3ea7" />
From there, you can search through the many existing policies and select the ones you want to add to your user. For this demonstration, I used "IAMReadOnlyAccess" then click next 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e9d86b1b-f3eb-4f6a-b0a7-9976a9a9ee8f" />
You are then taken to the review page, where you can verify all your settings before finalizing the permissions
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0f5640d6-e2b4-48be-9f29-e20315d649a2" />
Policy was successfully added
<img width="1916" height="525" alt="image" src="https://github.com/user-attachments/assets/146532bd-7a70-4606-b8bd-7a6c0590f5b8" />
You can quickly confirm your changes by trying to create a group in the IAM users account
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ea55156a-ba93-4ca6-99d0-b8a9d00232b2" />
Select Create group and then name the group 
<img width="957" height="1080" alt="image" src="https://github.com/user-attachments/assets/e071fb36-b12f-4be3-9e22-158561a9b3c7" />
The group will not be 
