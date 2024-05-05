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

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![image](https://github.com/Arunkumar215/Windows-basic-commands-batchscript/assets/166196271/2543d001-b53f-4cd7-86e1-4c9c69083faa)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/Arunkumar215/Windows-basic-commands-batchscript/assets/166196271/3aa5fefd-3fc3-4813-92f1-5d7ebdfdb13b)

![image](https://github.com/Arunkumar215/Windows-basic-commands-batchscript/assets/166196271/ada4f191-de97-446e-9688-792f159a4a43)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/Arunkumar215/Windows-basic-commands-batchscript/assets/166196271/e1c81f03-c44f-4378-8720-0aa55129851b)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![image](https://github.com/Arunkumar215/Windows-basic-commands-batchscript/assets/166196271/fe3acdb6-5bdd-43af-8fc8-832c1eaab174)
![image](https://github.com/Arunkumar215/Windows-basic-commands-batchscript/assets/166196271/966b6c45-cd36-46e6-bb1b-f40f17c7dc5d)


## COMMAND AND OUTPUT
![image](https://github.com/Arunkumar215/Windows-basic-commands-batchscript/assets/166196271/d989fca9-6afa-4d4c-8a63-f9ee9acf125e)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!







## OUTPUT


![image](https://github.com/Arunkumar215/Windows-basic-commands-batchscript/assets/166196271/ca4acbd9-7903-4239-be38-de6958e39c33)


# RESULT:
The commands/batch files are executed successfully.

