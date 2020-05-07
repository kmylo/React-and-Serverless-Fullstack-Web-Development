# React and Serverless - Fullstack Web Development

> Tired of building Todo apps? Want to know what it's like to build a real-world application from start to finish?

In this course, you will build a secure and production-ready fullstack typing application from start to finish. Along the way, you will learn core concepts of developing modern web applications like modern React, authentication and authorization, API creation with Serverless Functions, and continuous integration. By then end of this course, you will have the knowledge you need to build amazing applications to share with the world!

Here's what you will learn.

-   Modern React including Hooks and the Context API
-   Source Control with Git/Github
-   CSS in JSS using Styled Components
-   Store Data using the Airtable API
-   Secure applications using JSON Web Tokens
-   Build and Deploy Serverless Functions in Netlify
-   Create a Light/Dark Mode
-   Deploy to Netlify using Continuous Integration

## 1. Course Overview and Project Setup

### Course Overview and Resources

-   welcome to the course
-   what we will cover
-   links to resources used in the class

### Create Starter React Project

-   use `create-react-app` to generate starter project
-   remove unnecessary boilerplate code
-   create repository in Github
-   connect local code to Github repo

### Add routing with React Router

-   install React Router
-   create page components for Home, Game, Game Over, and High Scores

### Create the Navbar

-   create the Navbar component

## 2. Styled Components

### Introduction to Styled Components

-   what are styled components
-   benefits vs downsides to styled components

### Create Base Styled Components

-   create global CSS
-   create Main and Container components

### Style the Navbar

-   create Styled Copmonents for Navbar
-   create StyledLink component
-   create Accent component

### Style the Home Page

-   create Styled Components for title
-   create Styled Component for CTA

### Style the Game Layout

-   position Heads Up Display (HUD) for score and timer
-   style HUD and random character
-   add bold styled in global styled

## 3. Game Functionality with React Hooks

### Introduction to React Hooks

-   what are React Hooks
-   why are they useful

### Track Score with Your First React Hook

-   use `useState` to track the user's score
-   use `setInterval` to tsimulate increase in score

### Create Timer Functionality

-   use `useEffect` to start timer
-   use `setInterval` inside of `useEffect`
-   add the logic to update timer
-   navigate to GameOver page when timer expires

### Track User Input on Keypress

-   add event listener for `keyup`
-   unregistering event listeners in `useEffect`

### Update User Score Based on Input

-   use `useState` to track and update user's score as they play the game
-   update user's score based on keyboard input
-   display random character

## 4. React Context API to Share State Between Copmonents

### Introduction to React Context

-   what is React Context
-   why it's useful/why we need it

### Track User's Score Between Components

-   store user's score in a `ScoreContext` after completing a game
-   display user's score in Game Over page
-   prevent users from navigating directly to Game Over page

## 5. Airtable API and Setup

### Introduction to Airtable

-   sign up
-   what is Airtable
-   why we are using it here

### Airtable Workspace and API

-   create a workspace and base (link an excel doc)
-   explore the Airtable API with postman

## 6. Netlify and Serverless Functions

### Introduction to Serverless Functions

-   what are serverless functions
-   why we are using them here

## Netlify Init and Setup

-   create a new website in Netlify connected to your repository
-   create local netlify.toml file for configuration
-   explore the netlify dashboard

### Creating Your First Serverless Function

-   install `netlify dev` to run site and functions locally
-   create Hello World GET endpoint

Helpful tools - json viewer in Chrome

### Retrieving High Scores From Airtable

-   create new GET endpoint
-   implement endpoint for retrieving high scores Airtable

### Setup Environment Variables

-   use `dotenv` package to store private credentials
-   store Airtable credentials in environment variables

### Display High Scores in High Scores Page

-   create fetch Data hook
-   call serverless function for high score data

### Create Save High Score Serverless Function

-   create new POST endpoint
-   implement functionality for saving a score to Airtable

Helpful tools - postman

## 7. Add Authentication with Auth0

### Introduction to Authentication/Authorization and Auth0

-   why do we need authentication/authorization
-   what is Auth0 and how does it help

### Sign Up and Create Tenant in Auth0

-   sign up for free account
-   create tenant and application for our project

### Add Authentication in React with Auth0

-   create React Hook to interact with Auth0 for authentication
-   implement login/logout functionality
-   create ButtonLink component

### Require Username in Account Registration

-   make username a required field when registering with Auth0
-   what is an Identity Token
-   display username in navbar (where to put it)

## 8. Add Security Serverless Functions

### What Are JSON Web Tokens

-   what are JSON Web Tokens
-   when are they used and why

### What Are Access Tokens

### Include Access Token in Save Score Requests

-   what is an Access Token
-   configure Auth0 Client to retrieve Access Token
-   update Fetch request to include Access Token

### Retrieve and Validate Access Token

-   create API application in Auth0
-   configure Serverless Function to work with Access Tokens from Auth0
-   parse and validate Access Token before saving score

## 9. Create Light/Dark Mode with Context API and Hooks

### Define Dark and Light Theme

-   create dark and light theme objects that we will swap between

### Create Theme Context

-   create React Context for tracking the user's theme
-   add ability to save user's theme in local storage
-   create useTheme Hook for accessing them in components

### Implement Toggle Theme Functionality

-   add toggle theme button to Navbar
-   update them on button press

## 10. Hosting in Netlify

### What is Continuous Integration

### Create Deployment Configurations

-   add Netlify.toml configuration file
-   add `prod` script in package.json

### Creat and Deploy Site to Netlify

-   create new website in Netlify
-   connect to our Github repo

### 11. Wrap Up

### What Next

-   next steps and ideas for additional features

### Wrap Up

-   course summary and what we accomplished
