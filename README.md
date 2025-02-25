# Shopping Cart Application with Redux Toolkit

## Overview
This project is a simple shopping cart application built using **React, Redux Toolkit, and Tailwind CSS**. It fetches product data from a fake store API, allows users to add/remove items from the cart, and calculates the total price dynamically.

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `Install Tailwind CSS`
Install tailwindcss via npm, and create your tailwind.config.js file.
- npm install -D tailwindcss@3
- npx tailwindcss init
Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.
- @tailwind base;
- @tailwind components;
- @tailwind utilities;

### `Install redux toolkit`
- npm i @reduxjs/toolkit react-redux react-icons react-router-dom react-loader-spinner --legacy-peer-deps



## Features
- Fetch products from a fake store API
- Display product listings with title and price
- Add/remove items from the cart
- Show total cart value
- Maintain global state using Redux Toolkit
- Styled using Tailwind CSS

## Technologies Used
- **React**: Frontend framework
- **Redux Toolkit**: State management
- **React Router**: Navigation
