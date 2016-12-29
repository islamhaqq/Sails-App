# Data Visualization System

## Stack

- SailsJS
- NodeJS
- ExpressJS
- ReactJS
- MySQL

## Mission

Design and build a prototype that will enable a non-tech-savvy employee to easily visualize and explore the data in our database.

## About the Data

The basic business process is simple: first a "submission" is received from a potential client; an Underwriter then reviews it, gives it a rate, and decides if they want to "quote" the client that rate; clients may then accept, reject, or not respond to the quote. If everyone agrees, the submission is turned into a "policy" - that is called "binding."

Because of the business process, different data becomes available at different moments. The data contains submissions and policies at different stages of their lifecycle.

Avoid non-insights: For a submission that hasn't been reviewed, you wouldn't know the quoted_date, because it wouldn't be quoted. However, if you're trying to predict which submissions will get picked by underwriters to get quoted, the quoted_date variable has a really high significance. Please avoid this mistake.

Another example of a flawed insight: It turns out submissions with policy numbers are very likely to be quoted. That's logical, because submissions should be quoted before they become policies.

## Developer

A core competency for team members is the ability to build a front-end experience that streamlines and accelerates the work of internal stakeholders (primarily underwriters) and external clients (brokers and policyholders). Using the data set provided, we are looking to see how you might tackle this challenge.

### Goals

Demonstrate your ability to access, interpret and organize a set of data Create an experience that a non-tech savvy person could use Show your work

### Instructions

Access the data set using the instructions on slides 4-5 in this document Use the data to develop low fidelity (napkin) wireframe sketches Build a working prototype of your application

**HINT**: [Check out a self-service insurance portal](<https://d21buns5ku92am.cloudfront.net/6811/images/148868-Hiscox1-66ad3a-original-1416298049.png>).
