# 03 JavaScript: Password Generator

I created an application that generates a random password based on user-selected criteria. This app will run in the browser and feature dynamically updated HTML and CSS powered by your JavaScript code. It will also feature a clean and polished user interface and be responsive, ensuring that it adapts to multiple screen sizes.

## User Story

```
AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security

## Methodology

To kick this project off I began declaring my strings. I declared my strings according by storing them by elements. I.e. numbers were stored in the num variable, uppercase letters were stored in uppercase, lowercase letters were stored in lowercase and special characters were stored in 'specialchar'

I than began creating the prompts that would be needed to collect the values. I started with the length of the password (which is the most important) and then asking for confirmations on preference of symbols, uppercase, lowercase and numbers.

Next I wrote true/false conditions that would store those string type into a master password if the client preferred that element in their password.

I created a for loop that will randomly place characters from the unique "MasterPassword" that was an accumlation of the specified password elements and place that into a string and display the password.

Last but not least I created a CSS style sheet to make the application more user friendly.

Link to web applicatoin: https://sheikb08.github.io/PasswordGenerator/
Link to repository: https://github.com/sheikb08/PasswordGenerator
