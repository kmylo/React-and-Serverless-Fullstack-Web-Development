# React and Serverless - Fullstack Web Development

In this course, you will build a secure and production-ready fullstack typing application from start to finish. Along the way, you will learn core concepts of developing modern web applications like modern React, authentication and authorization, API creation with Serverless Functions, and continuous integration. By then end of this course, you will have the knowledge you need to build amazing applications to share with the world!


Here's what you will learn.

- Modern React using Hooks and the Context API
- Source Control with Git/Github
- CSS in JSS using Styled Components
- Data storage in Airtable
- Build secure applications using Auth0 and JSON Web Tokens
- Build and Deploying Serverless Functions in Netlify
- Creating a Light/Dark Mode
- Deploying to Netlify using Continuous Integration


## 1. Course Overview and Project Setup


### 1. Course Overview and Resources

- welcome to the course
- what we will cover
- links to resources used in the class

### 2. Create Starter React Project


- use `create-react-app` to generate starter project
- remove unnecessary boilerplate code
- create repository in Github
- connect local code to Github repo


### 3. Add routing with React Router

- install React Router
- create page components for Home, Game, Game Over, and High Scores
- create the Navbar component

## 2. Styled Components

### 4. Introduction to Styled Components


- what are styled components
- benefits vs downsides to styled components

### 5. Create Base Styled Components

- create global CSS
- create Main and Container components

### 6. Style the Navbar

- create Styled Copmonents for Navbar
- create LinkButton component
- create Accent component


### 7. Style the Home Page

- create Styled Components for title
- create Styled Component for CTA

### 8. Style the Game Layout

- position Heads Up Display (HUD) for score and timer
- style HUD and random character
- add bold styled in global styled

## 3. Building core Game Functionality with React Hooks

### 9. What and Why of React Hooks

- what are React Hooks
- why are they useful

### 10. Create the Timer Functionality

- use `useEffect` to start timer
- use `setInterval` inside of `useEffect`
- add the logic to update timer
- navigate to GameOver page when timer expires


### 11. Track User Keypress Input

- add event listener for `keyup`
- unregistering event listeners in `useEffect`


### 12. Track User's Score During Game

- use `useState` to track and update user's score as they play the game
- update user's score based on keyboard input
- display random character

## 4. Using the Context API to Share State Between Copmonents


### 13. Introduction to React Context

- what is React Context
- why it's useful/why we need it

### 14. Track User's Score Between Components

- store user's score in a `ScoreContext` after completing a game
- display user's score in Game Over page
- prevent users from navigating directly to Game Over page


## 5. Setup Airtable for Storing High Scores

### 15. Introduction to Airtable

- sign up
- what is Airtable
- why we are using it  here

### 16. Airtable Workspace and API

- create a workspace and base (link an excel doc)
- explore the Airtable API with postman

## 6. Serverless Functions to Interact with Airtable

### 17. Introduction to Serverless Functions

- what are serverless functions
- why we are using them here

### 18. First Lambda function
- netlify configuration for running netlify-dev
- create Hello World GET endpoint

Helpful tools - json viewer in Chrome


### 19. Serverless Function for Retrieving High Scores From Airtable

- create new GET endpoint
- store Airtable API credentials in environment variable
- implement endpoint for retrieving high scores Airtable

### 20. Create Serverless Function for Checking if Score is in the Top 10

- create new GET endpoint
- implement logic to determine whether a score is in the top 10


### 21. Add Post Functionality for Saving High Score

- create new POST endpoint
- implement functionality for saving a score to Airtable

Helpful tools - postman

## 7. Adding Authentication with Auth0

### 22. Introduction to Authentication/Authorization and Auth0
- why do we need authentication/authorization
- what is Auth0 and how does it help

### 23. Sign Up and Create Tenant in Auth0
- sign up for free account
- create tenant and application for our project

### 24. Implement Authentication in React with Auth0

- create React Hook to interact with Auth0 for authentication
- implement login/logout functionality

### Require Username in Account Registration

- make username a required field when registering with Auth0
- what is an Identity Token
- display username in navbar

## 8. Add Authentication to Serverless Function for Saving Score

### Include Access Token in Save Score Requests

- what is an Access Token
- configure Auth0 Client to retrieve Access Token
- update Fetch request to include Access Token

### What Are JSON Web Tokens

- what are JSON Web Tokens
- when are they used and why

### Retrieve and Validate Access Token

- create API application in Auth0
- configure Serverless Function to work with Access Tokens from Auth0
- parse and validate Access Token before saving score

## 9. Create Light/Dark Mode with Context API and Hooks

### Define Dark and Light Theme

- create dark and light theme objects that we will swap between

### Create Theme Context

- create React Context for tracking the user's theme
- add ability to save user's theme in local storage
- create useTheme Hook for accessing them in components

### Toggle Theme 

- add toggle theme button to Navbar
- update them on button press

## 10. Hosting in Netlify

### Create Deployment Configurations

- add Netlify.toml configuration file
- add `prod` script in package.json

### Creat and Deploy Your Netlify Site

- create new website in Netlify
- connect to our Github repo

### Wrap Up

- course summary and what we accomplished
- next steps and ideas for additional features

