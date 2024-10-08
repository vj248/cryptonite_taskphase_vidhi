## File Globbing

## Matching with *
Instead of typing out full file names, we can use globbing. Here, when we add * to any file name, all files that match the characters before the * will be used. Here, the constraint was limiting the cd command to 4 letters. So I was able to use '/ch*' which changed my directory to challenge, and thus helped me get the flag.
![{05927BFD-F044-4DA9-9F58-D18920EBEDF5}](https://github.com/user-attachments/assets/833ad77a-d5a6-4d5b-8964-719157dc186c)

## Matching with ?
In contrast to the * which treated the multiple characters as a wildcard, the ? only works for a single character. Thus, in order to navigate to the challenge directory I cd-ed to '/?ha??enge', which allowed me to successfully get the flag.
![{BA89F44B-CD69-43FF-BEEC-3313FA4E3973}](https://github.com/user-attachments/assets/e00c59ff-ab6e-4c1e-89d6-ce289bf72260)

## Matching with []
Instead of searching and referring to all files having format 'file_' we are specifying the only string characters that we want. Thus, we only run the files from 'file_a, file_b,file_h or file_h'.
Running this gives the flag. 
![{B2FD7EF6-BA4A-4B28-9AA3-675CDFA15A60}](https://github.com/user-attachments/assets/d5a1960a-d1c7-4f08-8cf4-2a88aa5b8a1e)

## Matching paths with []
This was the same as the previous problem. Here, we are using the [] in a file path. The working is the same, wherein it matches with files that contain the characters int he brackets. 
![{023DB454-BA54-407A-946A-73896BB64E60}](https://github.com/user-attachments/assets/7afb7e95-b25b-4594-bbae-e2d34ac7c83a)

## Mixing globs
Since we are only allowed to use 6 characters while writing the glob, we can match with [] first, to get files beginning with C,E and P. Then use * to wildcard the rest of the file name. 
![{44481011-C73D-44B7-9EB1-70661EC1B27A}](https://github.com/user-attachments/assets/a1baaee2-4ddd-474b-a542-fe92848a83ed)

## Exclusionary globbing
Here, we can exclude certain search alphabets from our glob by using '!' or '^' in the beginnning of []. So, following the instructions, we exclude files beginning from 'pwn' and use the '*' to wildcard the rest.
![{93037802-D3CF-4A13-84FC-BF6386E206C4}](https://github.com/user-attachments/assets/06eb5f5f-5e19-4987-8516-84a72f92cbf9)

