# E-Commerce Back-End

To run this app on your computer you need to run this commends in your terminal:
you can use `npm install` or `yarn add` about me I used `yarn`

- `yarn add cros crypto-js dotenv express jsonwebtoken mongoose nodemon stripe`
  OR
- `npm install cros crypto-js dotenv express jsonwebtoken mongoose nodemon stripe`

After that you need to create .env file and add some variables:

- `PORT` = 5000
- `PASS_SEC` = some password secret key
- `JWT_SEC` = some json web token secret key
- `MONGO_URL` = the URL of your mongoDB connection

### Note:
  To add Stipe payment method to your application you need :
  - Go to stripe site and register there and get Stipe key and add it in `.env` file as: `STRIPE_KEY` = Stripe key