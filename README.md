# Visual-CS-Rev-tmp
Used For HTB Visual - Initial Access Using Pre-build events in dotnet 6.0
Note: Don't use the source code for malicious purposes

Step 1 - Move all the files including the obj folder out of the Visual folder and place it in Visual-CS-Rev-tmp\n
Step 2 - This untrusted .NET project will execute a pre-buid event from a .bat file\n
Step 3 - The .bat file contains a base64 encoded reverse shell payload\n
![image](https://github.com/josephalan42/Visual-CS-Rev-tmp/assets/49631504/2ba90a5b-bbf4-41d7-afaa-5a5dd1af7157)
Step 4 - Follow this if the repo is to be hosted over a vpn to a box which does not have WAN access\n
Link - https://theartofmachinery.com/2016/07/02/git_over_http.html\n
Step 5 - Start listening on the local machine while the target machine starts prcoessing the project\n
Note - Make sure to commit any changes made like for example changing IP address or the reverse shell payload\n
Goodluck Capture The Flag!!!
