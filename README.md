# worktime-tracker
A sample .NET web app to track work time and location, for easier filling of tax declaration related to working from home.

## Motivation
In Germany we have couple of deductables as employees for our yearly tax declaration.

Traditionally, you can declare a dedicated office for working from home. This allows the highest possible deducation, but also has the highest requirements, e.g. dedicated lockable, not used for other purposes etc.

With the COVID pandemic, we got a working from home (Home Office) tax allowance of 5.00 €/day. Initially capped at 120 days per year, meanwhile not limited.

Traveling to the work office, is also relevant for deductables. As such, tracking when I was in the home office, when in the office and also, how many vacation and sick days I had, a typical spreadsheet was used.

As a software developer at heart, this get's now coded into a little web app.

## Goals
To have all information together, I want to record:

- vacation days: taken and available
- sick days: when and total number
- work days: when and where, with dedicated total numbers. Numbers of worked hours is also nice to see.

## Technlogy
With my .NET background, the web app will be build with Razor pages and a MS SQL Server database.
