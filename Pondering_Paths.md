# Pondering Paths

## The Root

We have to access the pwn program, so we just simply type /pwn to invoke the program using absolute path, since we are giving the direct address.
![image](https://github.com/user-attachments/assets/b6709ce2-8f3f-4048-b0c2-9ab592492b64)

## Program and absolute paths

This is just another step further, where we are first accessing the challenge directory which contains the run program.
![image](https://github.com/user-attachments/assets/60dbec32-6ddb-4501-84fa-9074c6bdd99a)

## Position thy self

Here we are first changing our directory to the sys directory. Then we can run our command to access the flag
![image](https://github.com/user-attachments/assets/3d8ffdef-8d8a-4561-87f1-000ace29f70a)

## Position elsewhere

Similar to the previous problem, we first change our directory to tmp, and then run our command.
![image](https://github.com/user-attachments/assets/fda61351-09f1-4c32-a2cd-160e6fe69273)

## Position yet elsewhere

Again, same as the last problem. The only difference here is that the directory we are changing to does not have a direct location from the root directory.
![image](https://github.com/user-attachments/assets/b3e88d55-af8a-4bb0-bfeb-36c3533c039c)

## Implicit relative paths, form /

First I used the cd function to naviagte to the root directory. Then challenge/run is used to get the key.
![image](https://github.com/user-attachments/assets/3edd14c4-5184-46ca-b476-cff1824a203a)

## Explicit relative paths, from /

Initially I made an error because I used the command for absoulte path instead of relative path. But I soon fixed it and got the correct key.
![image](https://github.com/user-attachments/assets/7ca90f4f-f145-4710-a371-c91c829da454)

## Implicit relative paths

Here we are basically understanding why we are using implicit relative paths. We cannot run the program as is, since we might have a program with the same name in the previous directory and make an error. So we use implicit relative functions, with a '.' to prevent that.
![image](https://github.com/user-attachments/assets/b33e629c-de70-4bc0-8e2b-1bffb52c8586)

## Home sweet home


