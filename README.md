# Visual-CS-Rev-tmp
Used For HTB Visual - Initial Access Using Pre-build events in .NET 6.0
Note: Don't use the source code for malicious purposes

Step 1 - Move all the files including the obj folder out of the Visual folder and place it in Visual-HTB-Initial-Access-Using-Prebuild-Events-.NET <br>

Step 2 - This untrusted .NET project will execute a pre-buid event from a .bat file. Look into .csproj file to modify the event if necessary<br>
Link - https://learn.microsoft.com/en-us/visualstudio/ide/how-to-specify-build-events-csharp?view=vs-2022 <br>
![image](https://github.com/josephalan42/Visual-HTB-Initial-Access-Using-Prebuild-Events-.NET/assets/49631504/80f3bab4-bb12-4b53-a65c-5a3d1b54e61e)  <br>

Step 3 - The .bat file contains a base64 encoded reverse shell payload  <br>

![image](https://github.com/josephalan42/Visual-CS-Rev-tmp/assets/49631504/2ba90a5b-bbf4-41d7-afaa-5a5dd1af7157)<br>  

Step 4 - Follow the steps given in the link below if the repo is to be hosted over a vpn to a box which does not have WAN access  <br>

Link - https://theartofmachinery.com/2016/07/02/git_over_http.html  <br>

Step 5 - Start listening on the local machine while the target machine starts prcoessing the project  <br>

Note - Make sure to commit any changes made like for example changing IP address or the reverse shell payload  <br>

Goodluck Capture The Flag!!!<br>
<br>
