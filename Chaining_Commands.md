# Chaining Commands

## Chaining with Semicolons
';' is used to run commands together, instead of pressing enter which would run only one line. Successfully chaining two commands will give the flag.
![image](https://github.com/user-attachments/assets/d6066127-4cc7-404e-bd24-6d1556b1139e)

## Your First Shell Script
If there are multiple commands, we can store them in a bash file. Then we can run this file to execupt the commands. 
![image](https://github.com/user-attachments/assets/8b793709-733c-4404-b85c-c2c5f7c49f54)

## Redirecting Script Output
In this challenge, we have to pipe the output of the script into a single invocation of the /challenge/solve command. Following this, I got the flag.
![image](https://github.com/user-attachments/assets/9547186e-8583-4066-9084-ec75e87185ae)

## Executable Shell Scripts
In this challenge, we had to create a script x.sh and then store the command /challenge/solve in it. Then I changed to file's permissions to give the user executable rights using the chmod command. Then I ran the file in order to get the flag.
![image](https://github.com/user-attachments/assets/3c3cfa01-8229-4d85-9835-4f02cb6f132f)


