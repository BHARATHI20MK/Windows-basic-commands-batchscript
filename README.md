# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/d61adf62-5a9d-4517-85e7-7333e5e2135e)

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/a2f9c0ff-e072-4d92-8f87-5207ec28be1c)

List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/e1e74c00-10ff-4dd2-8a52-5ba0dfb5ccbb)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/de89f9f0-c94d-40c9-9f70-35f74c8833a1)

Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/909d474b-6966-47a3-92d8-6153f448518f)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

open a notepad file named BackupScript.bat and enter the following:

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT

![image](https://github.com/user-attachments/assets/b11ae5c2-c8af-42ee-ac5f-ee6ce4b0423e)

# RESULT:
The commands/batch files are executed successfully.

