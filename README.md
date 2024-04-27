 # Ex08-Windows-basic-commands-batchscript

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
```
NAME:KISHORE.B
REG.NO:212222110020
```
## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![326150191-c206b1a2-a6cd-4a05-8be1-0e757209c1bd](https://github.com/KSIHORE/Windows-basic-commands-batchscript/assets/151484879/6f2a7c76-bbc2-4e9e-b0ce-98cd473dc35c)
## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![326150288-4b447d26-41f7-404f-9b36-abeade389383](https://github.com/KSIHORE/Windows-basic-commands-batchscript/assets/151484879/1dba6f6a-da87-42e5-a870-81a6fb0e07a7)
![326150304-5fdde096-136f-429f-b875-df720b5ace5f](https://github.com/KSIHORE/Windows-basic-commands-batchscript/assets/151484879/19692344-2fcc-4e24-b87c-939e8936fceb)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab
![326150376-d7c09055-e3c0-40a6-acc8-9c7a0d074a87](https://github.com/KSIHORE/Windows-basic-commands-batchscript/assets/151484879/b48de85b-cbdb-4654-bfd0-55a741dadec1)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
 mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![326150461-7ec9d35f-de3b-471f-a9ca-6f2a6d423eb2](https://github.com/KSIHORE/Windows-basic-commands-batchscript/assets/151484879/7aa13bce-e940-4946-a448-613456a19e4e)
![326150446-b745898c-a420-4802-8b01-515134b5f90a](https://github.com/KSIHORE/Windows-basic-commands-batchscript/assets/151484879/54ce9590-ba6e-4bdf-ad5c-837d0d470db0)

## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![326150513-2a79b20b-4617-4582-afe4-b7b93fb63e29](https://github.com/KSIHORE/Windows-basic-commands-batchscript/assets/151484879/b1cf793e-7fba-4c31-9226-79135ec43648)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.







## OUTPUT

![326150530-404d9504-2a72-4f94-aaed-bc617279bb62](https://github.com/KSIHORE/Windows-basic-commands-batchscript/assets/151484879/8953c230-35c0-4b45-84da-0a4392eb9b36)




# RESULT:
The commands/batch files are executed successfully.

