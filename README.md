[<img src="https://www.intelgic.com/static/img/intelgic.png" width="200">](https://www.intelgic.com/ "Powered By Intelgic")
  

 📧 OneDrive Automation
====================================

# :sparkler: OneDrive File or Folder upload
This bot can be used to upload files or folder to OneDrive. It will take the Sheet1 of "master.xlsx" for reference of which files or folders need to be uploaded. When it gets a folder to upload it will search in the OneDrive if the foldername is already exist or not. If there is no folder exists in the grive with same name at first the bot will create a folder and then read the whole folder and upload each file one by one to google drive else it will upload files to the existing folder.

## 🔥 Features:
- Read Sheet1 of "master.xlsx" which consist of 3 columns i.e. File name with proper extension, file path without file name, and Type. 
- upload files or folder to google drive.
- When it gets a folder to upload it will search in the OneDrive if the foldername is already exists or not. If there is no folder exist in the grive with same name at first the bot will create a folder and then read the whole folder and upload each file one by one to OneDrive else it will upload files to the existing folder.
## :heavy_check_mark: How to use?
1. Import the script xml file to your working directory of Dwmaker. `Default: My Scripts`
2. Set Client ID, Client secret and Refresh token which you have got from you Apps setup in Microsoft Azure portal  `(Line:1-3) `.
3. Set full path to the directory where you have saved your "master.xlsx" file `(Line: 7) Default: C:\Intelgic\master.xlsx`.
        - ***Please note:*** *Sample of "master.xlsx" with Sheet1 and Sheet2 is provided in the folder name "Intelgic". Sheet1 need to be customized as per user's requirment but Sheet2 needs to be keep as it is. In the Sheet1 of the "master.xlsx" user need to add the files and folders they want to upload with name and local path as sample*
4. Save the bot.
5. Run the bot.
        - ***Please note:*** *Bot will upload the files and folders to the OneDrive associated with the user you have logged in with the APP and accepted the consent*