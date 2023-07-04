# JP-Morgan-Virtual-Program
This repo contains my report on JP Morgan Chase's Software Development Virtual Program.
<br>
<a href="https://www.theforage.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/JP-Morgan-Banking-Technology-Virtual-Program?ref=S279cE8nM9YdrprXi" target="_blank">Forage Link</a>

## Task 1

When you’re in a work environment, you’ll usually receive tasks in the form of engineering tickets. Here is an example of what this task looks like in the form of an engineering ticket

Purpose
> We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.

Acceptance Criteria
- getDataPoint function should return correct tuple of stock name, bid_price, ask_price and price. Note: price of a stock = average of bid and ask
- getRatio function should return the ratio of the two stock prices
- main function should output correct stock info, prices and ratio

Step-by-step Guide has been provided to walk you through completion of the task.
<a href="https://cdn.theforage.com/vinternships/companyassets/Sj7temL583QAYpHXD/JiwEkbBq8pFwMRYLc/1678289036167/Task%201%20Guide.pdf" target="_blank">Task 1</a>

## Task 2

In this task you'll focus on the following: 

- Set up your local dev environment by downloading the necessary files, tools and dependencies.
- Fix the broken typescript files in repository to make the web application output correctly
- Generate a patch file of the changes you made.
- Submit your work

Just like in the last task, you need to get your local development environment up and running. Given that you completed task 1, you should already have python installed and be familiar with git.

First, fork and clone the project repo: https://github.com/theforage/forage-jpmc-swe-task-2
Remember to uncheck the “Copy the main branch only” box in the fork dialog on GitHub. A model answer has been provided in a separate branch from main.
Create a new virtual environment in the project root. Pycharm can do this automatically for you using the “configure python interpreter” option in settings.
Install all project python  dependencies. These are listed in the requirements.txt file.
 
In this task, we will be working with javascript in addition to python. Javascript has a handy package manager called npm, which handles package tracking, discovery, installation, and removal. We will be using it to install a series of javascript dependencies to your machine. If you already have access to npm on your system, you can skip this step. Otherwise, you will need to acquire it by following the instructions here (npm comes bundled with nodejs): https://nodejs.dev/en/learn/how-to-install-nodejs/
For this project to work, you must have node 18.10.0 installed on your machine. Ensure you have the correct version by running “node -v” in your terminal. If you do not, consider using nvm to install the correct version for you.
 
Install the necessary dependencies by running `npm install` from the project repo
 
Start the python server by running server3.py from the project repo like so: python datafeed/server3.py (note it’s important you run it from the root of the project repo)
 
Start the client by running `npm start` from the project repo
 
Click next once you're ready, and we'll start making some changes!

When you’re in a work environment, you’ll usually receive tasks in the form of engineering tickets. Here is an example of what this task looks like in the form of an engineering ticket.

Purpose:

The objective of this task will be for you to fix the client-side web application so that it displays a graph that automatically updates as it gets data from the server application (see Before and After images below). Currently, the web application only gets data every time you click on the 'Start Streaming Data' button and does not aggregate duplicated data.

Acceptance Criteria:

This ticket is done when the graph displayed in the client-side web application is a continuously updating line graph whose y-axis is the stock’s top_ask_price and the x-axis is the timestamp of the stock. The continuous updates to the graph should be the result of continuous requests and responses to and from the server for the stock data.
This ticket is done when the graph is also able to aggregate duplicated data retrieved from the server

To make the requisite changes, follow this step-by-step guide below.

Just like in the last task, you need to get your local development environment up and running. Given that you completed task 2, you should already have python and node installed and have at least a marginal familiarity with git

First, fork and clone the project repo: https://github.com/theforage/forage-jpmc-swe-task-3
Remember to uncheck the “Copy the main branch only” box in the fork dialog on github. A model answer has been provided in a separate branch from main.
Create a new virtual environment in the project root. Pycharm can do this automatically for you using the “configure python interpreter” option in settings.
Install all project python dependencies. These are listed in the requirements.txt file.
 
Install the necessary dependencies by running `npm install` from the project repo
 
Recall that you must have node 18.10.0 installed for this step to work correctly
 
Start the python server by running server3.py from the project repo like so: python datafeed/server3.py (note it’s important you run it from the root of the project repo) 
 
Start the client by running `npm start` from the project repo

When you're ready - move onto the next step!

## Task 3

In this task you'll accomplish the following:

- Set up your system by downloading the necessary files, tools and dependencies.
- Modify the typescript files in the project repo to make the web application behave in the expected manner
- Generate a patch file of the changes you made.
- Submit your work

When you’re in a work environment, you’ll usually receive tasks in the form of engineering tickets.
Here is an example of what this task looks like in the form of an engineering ticket.

Purpose
You will use perspective to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor.

Recall that the purpose of this graph is to monitor and determine when a trading opportunity may arise as a result of the temporary weakening of a correlation between two stock prices. Given this graph, the trader should be able to quickly and easily notice when the ratio moves too far from the average historical correlation. In the first instance, we'll assume that threshold is +/-10% of the 12-month historical average ratio.

Acceptance Criteria

This ticket is done when the numbers from the python script render properly in the live perspective graph. That means the ratio between the two stock prices is tracked and displayed, the upper and lower bounds are shown on the graph, and an alert is shown whenever the bounds are crossed.
Instructions for completing the task are included in the Task 3 - Step-by-step Guide below.

## Task 4 *(optional)*

This is a bonus task - separate from the previous tasks and entirely optional. If you do not want to participate, simply enter N/A in the text field below to complete the program.

The open source community depends upon talented developers around the globe making contributions to the backlogs of particular projects as well as building improvements to advance their code bases. This is an opportunity to look further into either Perspective or another open source project of interest to you, and make a contribution.

We'd be very interested to hear about your contributions, so feel free to submit pull requests with improvements to a core app, tackle an open issue, or even help improve the documentation of a project. Link any pull requests in the submission area below. Alternatively, simply tell us about any plans or ideas for future contributions.


