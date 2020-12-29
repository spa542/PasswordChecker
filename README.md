# Password Checker Program
# Author: Ryan Rosiak
<br /> <br />
## Project Description:
This project is a simple program to check the security and validity of your passwords/usernames/emails... etc. This program uses the PWNED Password API as a resource for checking
online public databases with hacked passwords and usernames to check if your information is vulnerable.
<br /> <br />
## Dependencies:
* python 3.5 or greater
* requests pip3 module
## To install requests module:
"pip3 install requests"
<br /> <br />
## How to Run:
To run this program, you simple must run the python3 interpreter and the file that is provided with as many arguments as you see fit. Each argument should be a
username/passowrd/etc that you want to check for vulnerabilities. The jprogram will read off the amount of pings (databases found) that contain each argument that you provided.
<br /> <br />
## Sample Execution:
"python3 checkmypass.py arg1 arg2 arg3 ...."
<br /> <br />
## Current Issues:
This program currently needs to be reworked because a weird change was made to the PWNED Password API. This will be fixed soon.
