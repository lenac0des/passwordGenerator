# password-generator

## Clarify/Define the Problem

We need to develop a method so that we may have a secured randomly generated password for our clients.

We want to generate a secure password for the user at any length

What is a password generator?
A Password generator is usually a software tool that creates random or customized passwords for the user.

How will it work?
The user will load up the landing page, then there will be a button to click that will allow you to generate a new random password.

The button will have an on click function that will be made in javascript to run a line of code that will generate a random password then it will be printed to the landing page (using the letters, numbers and special characters from aA-zZ, 0-9,!-+) for the user to see and note down for their own personal use.

Who is it for
This app is for everyone who wants to generate passwords that would be hard to break. For people with bad memory.


## Solutions (What app can do):
    
- the user has to create an account to generate password
- generate a new random password
- password is going to be not  less than 8 characters
- password will include numbers, letters, special characters
- uppercase and lowercase characters
- app will store all passwords
- app will remind once a year to change all passwords
- Implement password generator popup window/button, that will generate a random unique password per user.
- Generate new password everytime the application is accessed.
- Creates a safer user experience.

## Research/Brainstorm

Longer passwords are more secure. Many sites restrict passwords to be between 8 and 16 characters.

The app will be installed as an addition to a browser, because it is convinient to generate password while you creating a new account on a webpage

## Choose a solution/Take action
- An array of possible letters, numbers, and symbols
- Use random number function to generate index numbers in a for loop (16 times)
- Use += to append new character

## Hit singles/Coding - Tools

*HTML*
*CSS3*
*Javascript*
    -const pwEl = document.getElementById("pw");
    -const copyEl = document.getElementById("copy");
    -const lenEl = document.getElementById("len");
    -const upperEl = document.getElementById("upper");
    -const lowerEl = document.getElementById("lower");
    -const numberEl = document.getElementById("number");
    -const symbolEl = document.getElementById("symbol");
    -const generateEl = document.getElementById("generate");

## Runtime analysis:
- Generating a Password should have a low turnaround time.
(Turnaround: The process of completing or the time needed to complete a task, especially one involving receiving something, processing it, and sending it out again. )


## Testing/Debugging

*test cases*
    - If unique password isnt generated check const characters and symbol list as well as variable - Function generate in javascript file.
    - should fail if the password tried more than twice.
    - should fail if the 4 digit passcode tried by user more than twice.
    - should fail if the user didn't answer the 4 trick questions if the password tried more than twice.
    - should fail if the user didn't remeber the email adress so the app can send the one time password.
# passwordGenerator
