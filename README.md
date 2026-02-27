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
## Create a directory named "my-folder"

### COMMAND AND OUTPUT
```
mkdir my-folder
```
<img width="387" height="53" alt="image" src="https://github.com/user-attachments/assets/a4584d97-1d40-4875-b307-3230a112660d" />

## Remove the directory "my-folder"

### COMMAND AND OUTPUT
```
rmdir my-folder
```
<img width="408" height="50" alt="image" src="https://github.com/user-attachments/assets/06673c97-64df-4b3c-94d6-27e86168f6df" />

## Create the file Rose.txt

### COMMAND AND OUTPUT
```
type nul > Rose.txt
```
<img width="439" height="55" alt="image" src="https://github.com/user-attachments/assets/1173e1ed-3dcb-4abf-8d17-d6a31f12e396" />

## Create the file hello.txt using echo and redirection

### COMMAND AND OUTPUT
```
echo Hello World > hello.txt
```
<img width="558" height="52" alt="image" src="https://github.com/user-attachments/assets/2185fc8f-4135-4109-80a3-fb9de12a4b9c" />

## Copy the file hello.txt into the file hello1.txt

### COMMAND AND OUTPUT
```
copy hello.txt hello1.txt
```
<img width="497" height="69" alt="image" src="https://github.com/user-attachments/assets/6839f032-428c-4f5c-996d-dc803341f781" />

## Remove the file hello1.txt

### COMMAND AND OUTPUT
```
del hello1.txt
```
<img width="390" height="49" alt="image" src="https://github.com/user-attachments/assets/a54c864c-251f-48a9-ab83-92432dfa3178" />

## List out the file hello1.txt in the current directory

### COMMAND AND OUTPUT
```
dir hello1.txt
```
<img width="438" height="182" alt="image" src="https://github.com/user-attachments/assets/50fe981e-43f2-46f5-b859-a898217fcc29" />

## List out all the associated file extensions 

### COMMAND AND OUTPUT
```
assoc
```
<img width="625" height="880" alt="image" src="https://github.com/user-attachments/assets/15a8f80e-ef7e-433a-afd8-e8390e58acc2" />

## Compare the file hello.txt and rose.txt

### COMMAND AND OUTPUT
```
fc hello.txt Rose.txt
```
<img width="536" height="159" alt="image" src="https://github.com/user-attachments/assets/e6295113-a522-4b5d-858a-c32309011e38" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT



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

