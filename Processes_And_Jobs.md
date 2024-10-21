# Processes and Jobs

## Listing Processes
Since it has been said that the file name has been randomized, we use the 'ps -ef' command to list every process in full format.
![image](https://github.com/user-attachments/assets/6996e670-576e-4e08-82b7-eef6281adbfd)

## Killing Processes
We can kill various processes running by using the 'kill' command and specifying the PID of that command as the argument
![image](https://github.com/user-attachments/assets/c154254b-ac6b-4c02-96dd-699f5f14dfbf)

## Interrupting Processes
Pressing 'control+C' interrupts the program, which allows a clean exit if the process is waiting from an input from the terminal. Here, interrupting the program gave us the flag.
![image](https://github.com/user-attachments/assets/6bf3052c-2e03-48eb-b6a2-22455c46b851)

## Suspending Processes
We can suspend processes using 'Control+Z". This suspends the process to the background until we wish to resume it again.
![image](https://github.com/user-attachments/assets/547c5e9a-c998-4dd6-b7dd-38e10a0b653a)

## Resuming Processes
We can use 'fg' to resume a suspended program. Here, we frist suspended the run program and then resumed it to siccessfully get the key.
![image](https://github.com/user-attachments/assets/3e9bdaaa-41cb-4fb3-a6f1-d555ace518df)

## Backgrounding Processes
We can use the 'bg' command to run processes in the background, instead of resuming it to the main shell after suspension.
![image](https://github.com/user-attachments/assets/aed3c7f9-6bcc-4386-8df9-d410a2aa2082)

## Foregrounding Processes
We can foreground a backgrounded process using the 'fg' command, which is what had to be done here in order to get the flag.
![image](https://github.com/user-attachments/assets/13cd707c-cbde-4652-accb-a438dd4f6d42)

## Starting Backgrounded Processes
Instead of first suspending a program and then backgrounding it, we can append a '&' to the end of the command to run it in the background right off the bat.
![image](https://github.com/user-attachments/assets/82bdd1f0-835e-4c09-b185-1903b1da370d)

## Process Exit Codes
Each command ends with an exit code, that can be accessed using 'echo $?' to print the exit code of the latest command. In this program, we had to successfully input the correct exit code to get the flag. 
![image](https://github.com/user-attachments/assets/1964ec53-107c-447b-82dd-ead75116925c)



