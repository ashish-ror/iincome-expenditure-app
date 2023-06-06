# Ophelos - Technical Exercise

It is a web application that helps a customer to submit an I&E statement and calculates their disposable income and I&E rating.

# Installation Instructions

To get the Rails server running locally:

Clone this repo

bundle install to install all required dependencies

rails db:create to create the database

rails db:migrate to run migrations

rails s to start the local server

# Usage Instructions

Singup with any random email and password to get an account created

Click on 'New Statement' link to Enter Month, Year and multiple Incomes & Expenditures details

You may Edit the Statement anytime (can add or remove any more income and expenditure details)

After saving your Statement, system will automatically calculate 'Disposable Income' and 'I&E Rating'

A user can generate unique pair of month-year statement but can edit or delete it anytime

# Running Tests

bundle exec rspec

RSpec will run the tests, and you should see the output indicating whether the tests passed or failed.

# Corners Cut

Debt payments are not involved as its very similar to Expenditure and similar results can be achieved by adding any category in Expenditure

Instead of using SQLite database, we would typically use more robust databse like MySQL or PostgreSQL

We can add CSS classes for defined styling and could enhance it much better

We can add more comprehensive testing for user logging, error handling or performance testing

We can add more security and authentication measures preventing unauthorized access to the app 

We can add metrics to track/rate-limit statement generation for its fair usage and preventing abuse