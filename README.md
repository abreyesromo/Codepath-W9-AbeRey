# Week9-Codepath
# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

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

Vulnerability #1: XSS
>Step 1
>Step 2
>Step 3
>Step 4

Vulnerability #2: SQLi
>Step 1
>Step 2
>Step 3
>Step 4

## Green

Vulnerability #1: Username Enumeration
>Step 1 use a known username(pperson)
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-Green-Vul1-1.png">
>Step 2 Saw the login failed was bold
>Step 3 used a unknown user (1)
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-Green-Vul1-2.png">
>Step 4 Saw the login failed was not bold
>Step 5 test as many users as I want and test what works.

Vulnerability #2:Session Hijacking/Fixation
>Step 1
>Step 2
>Step 3
>Step 4

## Red ##

Vulnerability #1: IDOR
>Step 1 Clicked on a salesman
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-RED-Vul1-1.png">
>Step 2 Saw ?id=4 in the URL and assumed IDOR, so tested numbers
>Step 3 Tested ?id=11 and found this
 <img src="https://github.com/abreyesromo/Week9-Codepath/blob/master/Images/Week9-RED-Vul1-1.png">
>Step 4 Thats it.

Vulnerability #2: CRSF(See html file)
>Step 1 used
>Step 2
>Step 3
>Step 4


## Notes

Describe any challenges encountered while doing the work

