# Perceiving Permissions

## Changing File Ownership
We can use the chown commade to change the owner of a file from the root to the hacker so that the flag can be accessed by us.
![image](https://github.com/user-attachments/assets/acb56af5-8dd7-478a-8b73-9030927af0b9)

## Groups and Files
We can use the 'chgrp' to change the group ownership from root to hacker. 
![image](https://github.com/user-attachments/assets/22aaf33a-6f40-4e96-a5fd-0015d5e3cda2)

## Fun With Group Names
We first use the 'id' command to figure out what to 'chgrp' to, and then successfully get the flag.
![image](https://github.com/user-attachments/assets/553cd65c-9d6f-44ad-9421-a4be8b263242)

## Changing Permissions
We can change the permissions for a command using 'chmod'.
![image](https://github.com/user-attachments/assets/27e0168e-ebae-4513-8a77-89f3cbefd97c)

## Executable Files
We can make the program executable by using the chmod command, and then run the flag once it is executable.
![image](https://github.com/user-attachments/assets/2a8e2538-f2e1-4e16-b2a9-4d4a6a41b550)

## Permission Tweaking Practice

## Permissions Setting Practice

## The SUID Bit
Here, we added the SUID bit to /challenge/getrun to spawn a root shell. So, regardless of who runs the program, the program will run as the owner.
![image](https://github.com/user-attachments/assets/b4495f10-ef8f-461a-bd1e-79eafb344bbf)



