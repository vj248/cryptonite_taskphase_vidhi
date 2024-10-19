# Shell Variables

## Printing Variables
This was quite a basic program which demonstrated the use of the 'echo' command. It will print the values of variables if the variable name is preceded by a '$' sign.
![image](https://github.com/user-attachments/assets/1bb588b3-4d97-41c6-9f07-90dc5ac8c804)

## Setting Variables
We can assign values to variables by using the equals sign, however, it must be noted that there can be no spaces between the words and the sign.
![image](https://github.com/user-attachments/assets/d7af2807-a458-44b2-aa01-f78c8e5da264)

## Multi Word Variables
To assign multiple words to a variable, we have to enclose the words in "". Since, ;inux encounters a space, it stops the assignemnt at that point. 
![image](https://github.com/user-attachments/assets/c56d766c-3a77-4807-bf51-01cd4a98260e)

## Exporting Variables
The variables we define are limited to the shell where they are created. In order to ensure that they are available in other shells, we can use the 'export' command.
![image](https://github.com/user-attachments/assets/5b371f0f-da60-4117-8c7a-d1af83fe1379)

## Printing Exported Variables
The 'env' command is an alternative to echo, that prints every exported variable. I looked through all the exported variables and found the flag. 
![image](https://github.com/user-attachments/assets/d15b09f0-3315-4199-8bbc-86e482141186)

## Storing Command Output
We can store the outputs of a command into a variable and then echo the contents of the variable. This can also be used in nesting. The syntax is " =$(command) "
![image](https://github.com/user-attachments/assets/df49bd37-066c-4e3e-8bf9-29fa50c42ff2)

## Reading Input
The user can provide input using the read command. If the "-p" command is also used, it allows a text to be displayed which can be used to differentiate between input and output. The user's answer is stored in the mentioned variable. 
![image](https://github.com/user-attachments/assets/56661fc7-64fa-45b6-b1b9-7c21734871c8)

## Reading Files
