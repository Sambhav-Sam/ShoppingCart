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
- **React Icons**: UI enhancement
- **React Loader Spinner**: Display loading states
- **Tailwind CSS**: Styling

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/shopping-cart-redux.git
   cd shopping-cart-redux
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```

## Folder Structure
```
shopping-cart/
│── src/
│   │── components/
│   │   ├── Header.js
│   │   ├── ProductTile.js
│   │   ├── CartTile.js
│   │── pages/
│   │   ├── Home.js
│   │   ├── Cart.js
│   │── store/
│   │   ├── cartSlice.js
│   │   ├── store.js
│   │── App.js
│   │── index.js
│── public/
│── package.json
│── README.md
```

## Usage
- Navigate to the home page to see product listings.
- Click "Add to Cart" to add products.
- Click "Remove from Cart" to remove items.
- Go to the "Cart" page to view all added products and the total price.

## Future Enhancements
- Add authentication for user sessions.
- Implement checkout functionality.
- Improve UI with animations.


### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

## License
This project is open-source and available under the MIT License.

## Contact
For any issues or improvements, feel free to create an issue or reach out at rdrahul264@gmail.com.

