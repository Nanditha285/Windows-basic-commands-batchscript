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
<img width="701" height="193" alt="image" src="https://github.com/user-attachments/assets/ff160eba-b8a8-4252-b117-90eda179cec7" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="998" height="209" alt="image" src="https://github.com/user-attachments/assets/c42b5a15-4320-4e7e-b178-43da0ed8fbbd" />

Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="720" height="200" alt="image" src="https://github.com/user-attachments/assets/6dcf94d8-188a-4bfb-8ec2-35440d7e27a2" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="838" height="221" alt="image" src="https://github.com/user-attachments/assets/6f22520e-5345-483d-8eb7-654462b8e68b" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="805" height="242" alt="image" src="https://github.com/user-attachments/assets/dee09d71-a069-46e1-aa56-f3d84494b1c1" />


Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="670" height="213" alt="image" src="https://github.com/user-attachments/assets/09497e84-e407-4470-b36a-8d89c8a5f9ee" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="755" height="188" alt="image" src="https://github.com/user-attachments/assets/948e3937-8d87-409b-9edb-8d14556f04fb" />


List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="729" height="537" alt="image" src="https://github.com/user-attachments/assets/7fe03b58-5565-44b6-bc8a-c58efad6e8db" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="879" height="391" alt="image" src="https://github.com/user-attachments/assets/ea25272b-f4a2-462b-b6c3-63f635de2db5" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="1041" height="219" alt="image" src="https://github.com/user-attachments/assets/33e9e685-aedf-4ef4-b82b-603ee4e136b1" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/9902b47f-6b67-4732-925b-798cb41a2ce7" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/9f244c95-a90b-438e-a1e6-2ec33015d535" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="1818" height="865" alt="image" src="https://github.com/user-attachments/assets/b4748e1a-3d79-46b7-b25a-8d40044a6134" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.
## OUTPUT
<img width="1693" height="929" alt="image" src="https://github.com/user-attachments/assets/1c6e7b6c-75fa-4082-93d7-58639d016c6e" />


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

