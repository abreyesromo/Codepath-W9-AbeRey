# Week9-Codepath
# Project 8 - Pentesting Live Targets

Time spent: **8** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

###### Vulnerability #1: XSS
* Step 1 In the process of elimination i found Blue to be the XSS culprit

###### Vulnerability #2: SQLi
* Step 1 In the process of elimination i found Blue to be the SQLi culprit

## Green

###### Vulnerability #1: Username Enumeration
* Step 1 use a known username(pperson)
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-Green-Vul1-1.png">
* Step 2 Saw the login failed was bold
* Step 3 used a unknown user (1)
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-Green-Vul1-2.png">
* Step 4 Saw the login failed was not bold
* Step 5 test as many users as I want and test what works.

###### Vulnerability #2:Session Hijacking/Fixation
* Step 1 Found out that after 30min Green website times out
* Step 2 makes it vulnerable to both session hijacking and session fixation attacks

## Red ##

###### Vulnerability #1: IDOR
* Step 1 Clicked on a salesman
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-RED-Vul1-1.png">
* Step 2 Saw ?id=4 in the URL and assumed IDOR, so tested numbers
* Step 3 Tested ?id=11 and found this
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-RED-Vul1-1.png">
* Step 4 Thats it.

###### Vulnerability #2: CRSF(See html file-->https://github.com/abreyesromo/Week9-Codepath/blob/master/Abe-CSRF.html)
* Step 1 Search up CRSF form
* Step 2 edited it Abe-CSRF.html
* Step 3 clicked CTRL+O to open the file
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-RED-VUL2-1.png">
* Step 4 once opened i clicked update
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-RED-VUL2-2.png">
* Step 5 Then this happened
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-RED-VUL2-3.png">

## Notes

Describe any challenges encountered while doing the work

