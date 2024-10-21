# Pondering PATH

## The PATH Variable
There is a special shell variable, called PATH, that stores a bunch of directory paths in which the shell will search for programs corresponding to commands. On executing PATH="" command, we denote nothing to PATH which deletes the flag using rm command. Following this, we can run the command /challenge/run to get the flag.
![image](https://github.com/user-attachments/assets/2cb842e1-b37b-4eee-a3f7-541b1864bde7)

## Setting PATH
In this challenge, we first had to overwrite /challenge/more_commands/ in the PATH. Then on running /challenge/run win was invoked which caught the flag.
![image](https://github.com/user-attachments/assets/cb9a0c19-94f8-4010-b2bb-856adca43d4d)

## Adding Commands
It is commonly used in shell scripts and batch files to output status text to the screen or a file. In this challenge, we had to overwrite PATH with the directory having win. On doing that, when /challenge/run command is executed win is invoked. Then we used the echo command on PATH. Further, I created an empty file called win. Then on running cat /flag, I got the flag.
![image](https://github.com/user-attachments/assets/8dadc6ed-5076-48f8-8018-055290e68628)

## Hijacking Commands
In this challenge, the flag will be deleted using the rm command so I created an empty file named rm, which will be invoked instead of the flag. I stored cat /flag in the rm file. I further, changed the permissions of the file to give executive access to everyone. 
![image](https://github.com/user-attachments/assets/bccdadf4-0d2f-4f24-9977-a2e05ddc584d)

