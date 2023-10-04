# SHELL-SCRIPTING-
## shell scripting project content

## Introduction to shell Scripting and user input

We use shell scripting to carry out repetitive tasks in a shell using Bash scripts which are a series of commands used and 

written in a file with a .sh extension from the command line or other scripts.

 First of all we have to get to the server using git bash  to set up the work enviroment.

   Below is a ready to use work enviroment.

![image](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/d9a282e9-8bcf-40cb-b00c-d5374b9b7485)

## Shell scripting  Syntax Elements.

### Variables

 Alows you to define work in Bash

   they can store work in  
   
-  Numbers
-  
-  strings
-  
-  arrays
  
=  -assigns value to a valuable

$  -retrives value from a valuable.

  These two variables have been demonstrated below.

![=        $](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/395b8e7f-7e29-4415-b7be-962b7787e919)

### Control Flow

 These are if and else statements and are used depending on the condition.

 Below is a screen shot showing the if and else statements excecution using a code which propmpts you to type numbers and statements to say if the 
  
  number is positive or negative 
   .

 ![if and else](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/457411c7-91c4-4506-b0bb-26ba89e792c3)

  Below is an 'for loop' execution showing an example to print numbers.
  
![for loop](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/2a3910e5-223f-4e89-a0c4-3a5d739dfddf)

### Command substitution

BacktrickS are used for command substitition  as well as syntax ie '' or $() as shown below.

![''            $()](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/9454f92b-769c-4946-a653-be2cd7614138)

### Input and output

 Some of thw commands used here are :
 -  read command to accept user input

 -  echo command output text to the console
   
-  output of a file to a file >

-  <input from a file

-  | pipe the output of one command as an input to another .

These has been demonstrated on the screen shot below.

![input output](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/4716312c-0bf8-448b-b9bf-8f88ba917235)

### Function

Using bash, you can carry out these commands which allows you to modularize your code and make it more reusable for 

example declaring the function name follewed by parentesis as demonstrated on the screenshot below.

![modularise and more reusable code sample](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/cc4c0f09-072e-4e74-af84-c1f1404157f3)

## Sample First Script Shell.

First is directory and file creation using the linux commands mkdir and touch commands where after using the nano 
 
 command  the text is copied and by use of keys ctrl x and ctrl y  into the file
 
 We check the file content using the cat command . ls -ll helps us to see the 
 
 rights the user has on the file created There after chmod +x command is
 
 used to give the user the rights to execute the file created hence can easily run the script using the ./file name . sh.

  The directory created here is "shell scripting and the file is user-input.sh"

   The screen shot below provides step to step guide of the shell script and the output of the code run at the end .

   ![first shell script](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/7db23853-e210-4a6c-85eb-3615df9fd6f1)

## Directory Manipulation and Navigation.

 The steps involved here are as listed below 

 - File creation (navigating -linux-file system.sh)

 - Pasting code provided into the file using nano command wher eafter copying the code you save it and exit the editor by
 
 -   use of ctrl x and ctrl y then enter 

 -  Checking file content copied usung the cat command

 - ls -ll helps us be able to know which rightes the usre has not the file

 - Here we finfd the user has no execution rights hence we have to chmod  +x to give him the execution rights

 -  The script is then run ./navigating -linux-file system.sh wher the expected results are shown on the second
     
    screenshot.

 ![directory manipulation and navigation 2](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/8ed04a68-bb6d-453b-80f1-497618713a3b)

 ![directory manipulation and navigation 1](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/b61e80a8-3857-45cd-b74e-47f41ad01be3)

 ## File operations and sorting 

 the shell script here demonstarates file operations and sorting . this has been carried out using the same steps as the 
 
 previous shell created  the only difference is that we are dealing with a file hence no directory created . ie sorting 
 
 .sh file
 
 The screen short below demonstratesthe step by step guide with the output at the end of the screenshot.

 ![fileoperations and sorting](https://github.com/NANA-2016/SHELL-SCRIPTING-/assets/141503408/6cd0edad-9c6f-4307-8a77-6badf4b19022)


 




    

   

   










 










