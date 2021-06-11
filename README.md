# Progressive Web Application - Budget Tracker

## Summary
Update an existing budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online.  The app will be deployed to Heroku with MongoDB Atlas.

## User Story
AS AN avid traveler  
- I WANT to be able to track my withdrawals and deposits with or without a data/internet connection  
- SO THAT my account balance is accurate when I am traveling   

## Acceptance Criteria
- GIVEN a budget tracker without an internet connection  
- WHEN the user inputs an expense or deposit  
- THEN they will receive a notification that they have added an expense or deposit  
- WHEN the user reestablishes an internet connection  
- THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated  

## Design Mock-Up

![](assets/images/19-pwa-homework-demo-01.png)

## Github Repository
All files and changes made are located on github at the following location:

https://github.com/htang2021/budgetTracker-pwa

## Application Live URL on Heroku
https://htang-moneyapp.herokuapp.com/

## Testing Guideline
Note - Chrome is used in the guideline here.
- Go to the deployed [link](https://htang-moneyapp.herokuapp.com/) and input a few transactions to establish a working baseline
- Disable internet connectivity and without refreshing the page, make a few transactions.  Inspect the page and by going to the Application tab 

## Contact
Please feel free to contact [me](mailto:hungtang@hotmail.com) with any questions.

End of README.md - updated by Hung Tang on 6/11/21
