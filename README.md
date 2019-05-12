# Laravel
Laravel Apps &amp; Projects
LARAVEL CAR LOAN APP v1.0

The Car Loan App is a simple Laravel framework app for inserting the necessary data for a car loan, saving this data on a database and performing the necessary math calculations for obtaining the PMT - Monthly Payment for the desired car.

More specifically the loan form requires the following fields:

Name - The name of the owner
Surname - The last name of the owner
Model - Car brand, model and year of production
Price - The price of the car
Number of Periods - Monthly number of periods for 
Advance - Advance money given before the purchase of the car loan

After the user enters the required fields the app computes the PMT - (Monthly Payment)for this particular car loan. We use a rate of 1% monthly compounded rate hard coded for testing purposes, which is equal to 12% yearly nominal rate. In the next revision of the app we are going to have a select menu for selecting the appropriate  loan rate.

The business math formula used for the calculation is:

 // Please view the readme.rtf to see the loan formula

which can be founded in most Business Mathematics textbooks.

The user can enter many different rows of loan data in the database and the PMT is calculated automatically for every record. The user can also view all the records together or delete the database rows that she wishes.
