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

## Deploy Your Project
This instruction below assumes that a project and repo were created early on and that they are already linked.
1. Login to github and go to the project repo (https://github.com/htang2021/weather-dashboard).

2. Click on "Settings" in the repo menu.

3. Scroll down to the GitHub Pages section and select branch where the site will be built from, will either be "master" or "main" and with folder in /root.  Click on "Save" button next to it.

4. Wait for a minute or two, GitHub will return a live site URL:
https://htang2021.github.io/weather-dashboard/

End of README.md - updated by Hung Tang on 3/13/21
