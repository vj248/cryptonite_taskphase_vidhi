# Comprehending Commands

## cat : not the pet but the command
The 'cat' function is essentially used to print the contents of a file. If multiple files are provided as arguments, it will print all of them. In this problem, the flag is obtained successfully by reading the file 'flag'.
![image](https://github.com/user-attachments/assets/5e0b4e20-37a7-4fac-8f53-4c595d876eda)

## catting absolute paths
Similar to the last problem, instead of the file being in the home directory, it is in the root directory, so we use an absolute path.
![image](https://github.com/user-attachments/assets/23db2c24-9c45-48f6-a11e-6f3a332d53cb)

## More catting practice
Since we are not allowed to change directories, we use an absolute path given to us and retrieve the flag
![image](https://github.com/user-attachments/assets/59af63ab-39be-4f82-89e6-a63186e43bfc)

## Grepping for a needle in a haystack
We are using the grep command. It essentially acts as a search function, where we can search for a string and print only that line instead of printing the whole file using cat. Since each flag startes with pwn.college, we search the file using that.
![image](https://github.com/user-attachments/assets/1dfe72f5-b239-4669-82ed-347ed8b7b18c)

## Listing files
I used the ls command to first see what files are present in the challenge directory. Made a slight mistake when i accidently used the cat command on the run file, however i fixed thar and got the flag
![image](https://github.com/user-attachments/assets/d576ed64-1fa4-4b7f-a917-1e0d5b9e510d)

## Touching files
I used the touch command to create two files, and then ran the command which gave me access to the flag.
![image](https://github.com/user-attachments/assets/ca76052a-6464-4cca-84a8-42f0409ed9d5)

## Removing files
We can use the 'rm' command to delete files. In this problem, we simply use the command and then obtain the flag on successful removal.
![image](https://github.com/user-attachments/assets/51dbbfc8-b777-428c-8c65-a78556cefd2d)

## Hidden files
First I checked the list of files usinf 'ls'. Then, I used 'ls -a' to check the hidden files that begin with a fullstop. Then I used the 'cat' command to find the flag.
![image](https://github.com/user-attachments/assets/a0d2bf1f-a340-4e4a-bfb1-e309bd839808)

## An epic filesystem quest
This was a pretty long task compared to the previous ones. After about a dozen times of 'ls-ing' and 'cat-ing' I finally found the flag. Some hints did not allow cd to be used, while some were stored in hidden files that had to be accessed using 'ls -a'
![image](https://github.com/user-attachments/assets/4092a5f2-5a30-4c54-bdd3-b66270bbeef9)

