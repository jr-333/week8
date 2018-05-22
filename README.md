# Week8
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

Vulnerability #1: __________________

Vulnerability #2: __________________


## Green

Vulnerability #1: Username Enumeration
![user_enum](https://user-images.githubusercontent.com/38142630/40336284-a4bad25a-5d1d-11e8-94aa-3daf72427df8.gif)

Vulnerability #2: Cross-Site Scripting (XSS)
![xss](https://user-images.githubusercontent.com/38142630/40337833-9cd7ec9a-5d26-11e8-84ab-576045a2efe6.gif)



## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR)
![idor](https://user-images.githubusercontent.com/38142630/40336864-e87b07dc-5d20-11e8-9977-b1dd118fb3c3.gif)


Vulnerability #2: __________________


## Notes

Describe any challenges encountered while doing the work


## Concept Review
Which attacks were easiest to execute? Which were the most difficult?

What is a good rule of thumb which would prevent accidentally username enumeration vulnerabilities like the one created here?

Since you should be somewhat familiar with the CMS and how it was coded, can you think of another resource which could be made vulnerable to an Insecure Direct Object Reference? What code could be removed which would expose it? (Hint: It was also the answer to the first bonus objective to the Weekly Assignment for week 3.)

Many SQL Injections use OR as part of the injected code. (For example: ' OR 1=1 --'.) Could AND work just as well in place of OR? (For example: ' AND 1=1 --'.) Why or why not?

A stored XSS attack requires patience because it could be stored for months before being triggered. Because of this, what important ingredient would an attacker most likely include in a stored XSS attack script?

Imagine that one of your classmates is an authorized admin for the site's CMS and you are not. How would you get them to visit the self-submitting, hidden form page you created in Objective #5 (CSRF)?

Compare session hijacking and session fixation. Which attack do you think is easier for an attacker to execute? Why? One of them is much easier to defend against than the other. Which one and why?
