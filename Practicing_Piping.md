# Practicing Piping

## Redirecting Output
To redirect the output of 'echo' command, we use the '>' symbol followed by the file name. This puts the text into that file, which can be printed using the 'cat' command. In this question,correctly redirecting the word PWN to file COLLEGE gave the flag. 
![{AD4E7998-97AF-4AEE-9511-538A3D82C5B2}](https://github.com/user-attachments/assets/f8064e1f-7c6a-4b95-8b50-21548ebe207f)

## Redirecting More Output
Here, after redirecting the command to a different file, it still prints some information. We can just cat into the other file to obtain our flag.
![{E8389692-92D3-4176-9425-3E49B42CFAE3}](https://github.com/user-attachments/assets/b30e6597-a94a-44b6-b5b9-f1f67a03077b)

## Appending Output
The '<' symbol will overwrite any file if it alreadt contains information. However, the '<<' command will append its contents to the file. So, in thsi question we had to use '<<' to get both parts of the key
![{4032F1EB-F76D-4BA2-8078-03730497DBD8}](https://github.com/user-attachments/assets/65fd6b5d-f7e0-4894-83e1-d6e3581d7953)

## Redirecting Errors
All parts of a command, that is output and errors can be redirected. Using '2>' redirects the errors and '1> or >' redirects the output. Both can also be used together, which is what was done here.
![{BC99E62F-826E-41A4-B4C9-55DFAAC076D7}](https://github.com/user-attachments/assets/fcf3b2c4-00fd-4af1-bd71-c86369c2f6c4)

## Redirecting Input
Similar to redirecting outputs and errors, we can also redirect inputs. To do this we use the '<' symbol. This inputs the program to the mentioned file. Inputting the value of COLLEGE in PWN gives the correct flag here. 
![{615C6C03-4340-494C-9A19-FD73AA521C05}](https://github.com/user-attachments/assets/02596ee6-2b74-464c-9f55-3d56cae69f24)

## Grepping Stored Results
Here, we first store the output of the challenge in a file, and then use the grep command to search the thousands on sentences present for those that start with the format of our flag.
![{92EF102E-9643-4FD9-9E40-4258EE24BC19}](https://github.com/user-attachments/assets/8fe8f820-0fee-4c95-8743-be5ff2a9ab57)

## Grepping Live Output
Instead of first storing output in another file, and then grepping that file, we can use the '|' command to grep the live output for pwn.college, removing the need for another file.
![{F697D5F2-8C4E-49D7-ACB5-858F58D0CBDC}](https://github.com/user-attachments/assets/8162bd05-856d-4540-a6c0-c885bf6a01bc)

## Grepping Errors
If we wish to grep errors, first we can redirect the errors to the output, using '2>&1' and then grep for the flag.
![{7730FA63-B208-47E8-B8AC-47C930C30518}](https://github.com/user-attachments/assets/72650c3f-8349-4e21-b1fc-e31945b5dec7)

## Duplicating Piped Data with tee
We are basically storing the output of the program so that we can see it before piping. This stored output gives the value of the secret code which is needed to get the flag.
![{1823DC7C-A1AD-495F-9936-CBBA207E9DBC}](https://github.com/user-attachments/assets/4d8b4d3c-6876-4a32-9144-6ee58d4cdfd5)

## Writing to Multiple Programs
We run the hack command and store it in both 'the' and 'planet' by using the '|' and '>' commands. Doing this correctly gave the flag. 
![{504EE262-6007-4CAD-8B38-7811EC5A103D}](https://github.com/user-attachments/assets/ad13bd4b-f0b4-4ca5-9bf5-f33c6dec3bca)

## Split piping stderr and stdout
I used the 1> command to redirect the output to 'planet' and 2> to redirect errors to 'the'. 
![{F1F3D5D8-0A42-48E2-B111-F6A3489033D5}](https://github.com/user-attachments/assets/243260d1-3c56-4665-ab71-28aa65977220)
