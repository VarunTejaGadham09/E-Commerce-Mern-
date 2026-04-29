# E-Commerce (Mern)

> Full-stack e-commerce platform built with the MERN stack.

## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

## Usage

### Install Dependencies (root, frontend, & backend)

```bash
npm install
cd frontend
npm install
cd ../backend
npm install
```

### Run

```bash
# Run frontend only (:3000) & backend (:5000)
npm run dev
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data.

```bash
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

### Environment Variables

Copy `.env.example` to `.env` and fill in your values.

## License

MIT

