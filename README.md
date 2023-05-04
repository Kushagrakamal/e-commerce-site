
# E-Commerce Site

This is a e-commerce site built using [React](https://reactjs.org/) and [Node.js](https://nodejs.org/en/). The site allows users to browse and purchase products.

## Features

- User authentication
- Product browsing and search functionality
- Shopping cart with the ability to add and remove items
- Checkout and payment processing with [Stripe](https://stripe.com/)
- Admin dashboard for managing products and orders

## Installation

1. Clone the repository: `git clone https://github.com/Kushagrakamal/e-commerce-site.git`
2. Navigate to the project directory: `cd e-commerce-site`
3. Install dependencies: `npm install`

## Usage

1. Start the server: `npm run server`
2. Start the client: `npm run client`
3. Open your browser and go to `http://localhost:3000` to view the site

## Configuration

You will need to set up a few configuration variables in order to use the site:

- Create a `.env` file in the root of the project directory
- Add the following variables:
  - `MONGO_URI` - the connection string for your MongoDB database
  - `JWT_SECRET` - a secret string used for encrypting user authentication tokens
  - `STRIPE_SECRET_KEY` - your secret Stripe API key
  - `STRIPE_PUBLISHABLE_KEY` - your publishable Stripe API key


