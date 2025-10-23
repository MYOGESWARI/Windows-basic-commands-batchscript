# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\MyLab'


<img width="707" height="51" alt="image" src="https://github.com/user-attachments/assets/3514d4a9-4b84-42b7-b275-55e5f3342b76" />

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

## COMMAND AND OUTPUT
cd %userprofile%\Desktop\MyLab


<img width="650" height="106" alt="image" src="https://github.com/user-attachments/assets/9e71b3c9-1dc8-42d8-bbf4-a96e82c9ea57" />

type nul > MyFile.txt

<img width="698" height="101" alt="image" src="https://github.com/user-attachments/assets/038a5548-6c7d-44cd-8516-a5bc71af6c50" />

Create the file Rose.txt

## COMMAND AND OUTPUT
dir %userprofile%\Desktop\MyLab

<img width="815" height="321" alt="image" src="https://github.com/user-attachments/assets/d6baec58-cf37-400a-993b-e3a2e8f02577" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

mkdir %userprofile%\Desktop\Backup


<img width="800" height="102" alt="image" src="https://github.com/user-attachments/assets/3a252f76-c863-4465-ab4b-ba7650d01f9c" />


copy MyFile.txt %userprofile%\Desktop\Backup


<img width="925" height="143" alt="image" src="https://github.com/user-attachments/assets/407c7fbb-f6b0-4f58-ab10-6359730aa50d" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Documents


<img width="891" height="223" alt="image" src="https://github.com/user-attachments/assets/fd9b771e-5b08-4a31-97cf-b23ec21b6b57" />



Remove the file hello1.txt


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

COMMAND:

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!


## OUTPUT


<img width="957" height="247" alt="image" src="https://github.com/user-attachments/assets/53be3072-dc22-41e1-984b-e20b1188719b" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

