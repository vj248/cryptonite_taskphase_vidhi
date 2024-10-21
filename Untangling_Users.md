# Untangling Users

## Becoming root with su
First, we execute su, which runs as root, upon which we are prompted to enter the given password. Then, we can read the flag. 
![image](https://github.com/user-attachments/assets/d80572b0-24c9-4364-a153-4608632ebb96)

## Other users with su
Here, we run su with the argument zardus, to switch to that user instead of root. Upon doing that and running the command, we get the correct flag.
![image](https://github.com/user-attachments/assets/7afd920e-2aa4-4914-96ff-d48c26e58617)

## Cracking Passwords
After cding into the challenge directory, executed the command and after getting the status,I executed the command john --show shadow-leak wherein I got passwords for zardus user and the hacker user. I ran the command su zardus and then entered the password I got, which gave me the flag. 
![image](https://github.com/user-attachments/assets/ee36faf3-77b9-429f-93de-da7290f3f352)

## Using sudo
Sudo defaults to running a command in the root. So, here we can use sudo to read the flag with root access. 
![image](https://github.com/user-attachments/assets/239aed9b-61cc-4b17-9d42-8f0e98c6db00)
