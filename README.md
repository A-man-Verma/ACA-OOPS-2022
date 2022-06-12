# ACA-OOPS-2022
## BASIC COMMANDS IN TERMINAL
### 1) CD: this command changes directory in command promt or it can be used to navigate to other folders in your pc.
### 2) DIR: this command is used to view contents of the folder.
### 3) MKDIR or MD: this command is used to make new folder.
       to make a new folder named "Assignment", we use: MKDIR Assignment
### 4) REN : this command is used to rename files or folder 
       to rename a folder from "Assignment" to "Assignment1", We use: REN Assignment Assignment1
       to rename a file from "Assignment.pdf" to "Assignment1.jpg", We use: REN Assignment.pdf Assignment.jpg
### 5) COPY : this command is used to copy files to a different location.
       to copy "C:\Assignment1.pdf" to "C:\OOPs\Assignment1.pdf" , We use: copy C:\Assignment1.pdf C:\OOPs\Assignment1.pdf
### 6) XCOPY : this command is used to copy a folder and its contents to a different location.
       to copy "C:\OOPs" to "C:\OOPS_BACKUP", We use : xcopy C:\OOPs C:\OOPS_BACKUP
### 7) DEL : this command is used to delete files in a folder.
       to delete a file, lets say, C:\OOPS\Assignment.pdf, We first open that folder and use : del Assignment.pdf
       to delete all files with a specific extension, lets say, ".exe", We first open that folder and use : del *.exe
       to delete all files starting with, lets say, "Aman_",  WE first open that folder and use : del Aman_*.*
       to delete all files in a folder, we first open that folder and use : del *.*
### 8) RD : this command is used to delete a folder
       to delete the folder, we use : RD OOPs
### 9) Change drive : first open the drive, lets say, "C:\" 
       use : C:    
       then press enter
       To change the drive and the directory at the same time, use the cd command, followed by the /d switch.
       The /d parameter is used to change the current drive to a specific folder from another disk volume.
       For instance, if you are now on the D: drive and you want to go back to the OOPs folder from the C: drive
       we use : cd /d C:\OOPs
       then press enter
### 10) Launch an App : First of all, change the working directory to the application's folder
       by using : cd /d c:\OOPs\
       Then, type the name of the app’s executable file.
       we use : OOPs_test_program.exe
### 11) HELP : to get help commands:
       we type : HELP 
       then press enter. A list of commands will appear.
       from the list, we want to use a specific command, lest say, "CALL"
       we use : HELP CALL
       or
       we use : CALL/?
       
