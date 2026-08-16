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
<img width="1210" height="42" alt="Screenshot 2026-08-15 214410" src="https://github.com/user-attachments/assets/9fbf8b19-42cc-4486-94aa-162882fafdc1" />



Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="1218" height="42" alt="Screenshot 2026-08-15 214424" src="https://github.com/user-attachments/assets/db3f0179-394d-4947-851a-8b769f887551" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="1725" height="371" alt="Screenshot 2026-08-15 230820" src="https://github.com/user-attachments/assets/3abb55f4-50ea-442b-9a64-3dc200507025" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="1208" height="97" alt="Screenshot 2026-08-15 232749" src="https://github.com/user-attachments/assets/6f3a6b67-8f03-4f6b-afba-ff41dc20d75f" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="1411" height="117" alt="Screenshot 2026-08-15 232802" src="https://github.com/user-attachments/assets/9ba18cf9-e019-43cd-bc00-44e1d59572dc" />


Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="1342" height="138" alt="Screenshot 2026-08-15 232810" src="https://github.com/user-attachments/assets/1cb118f3-9082-4cce-a6a8-479c203f9bf6" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="1271" height="43" alt="Screenshot 2026-08-15 232819" src="https://github.com/user-attachments/assets/4743f49d-7f41-4cea-9f4d-6198843d629d" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="1187" height="350" alt="Screenshot 2026-08-15 232826" src="https://github.com/user-attachments/assets/159706d9-3a04-4052-94b0-2b5820aae83b" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="1283" height="233" alt="Screenshot 2026-08-15 232838" src="https://github.com/user-attachments/assets/1f65d8b7-49cf-4cad-8603-b9bb0cb7e540" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT

![alt text](<Screenshot 2026-08-15 235229.png>)

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

![alt text](<Screenshot 2026-08-15 235234.png>)


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


![alt text](<Screenshot 2026-08-15 235229-1.png>)

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
![alt text](<Screenshot 2026-08-15 230820.png>)

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

![alt text](<Screenshot 2026-08-15 235234-1.png>)

# RESULT:
The commands/batch files are executed successfully.

