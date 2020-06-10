
---

## Quick Start

```bash

# Install dependencies
cd books-chain && npm install
cd books-chain-Frontend && npm install

```
Create an account in Braintree and create new App. Copy the provided credentials to your app.
Enter following creadentials in .env file.

```
DATABASE=mongodb://localhost/ecommerce
JWT_SECRET=hdfsajkfhlsdkja
BRAINTREE_MERCHANT_ID=YOUR_OWN_ID
BRAINTREE_PUBLIC_KEY=YOUR_OWN_KEY
BRAINTREE_PRIVATE_KEY=YOUR_OWN_ID
```

To run the development server:

```bash
# the development server runs on port 3000
npm start
```

To run production build:

```bash
# create code bundle
npm run build

# run production server
npm run prod
```

## Main Technologies

### Client Side

- [x] **[React](https://github.com/facebook/react)**
- [x] **[Bootstap 4](https://github.com/twbs/bootstrap/tree/v4-dev)**
- [x] **[React-Router-DOM](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**

#### Libraries used in Client-side

- [x] **[query-string](https://github.com/sindresorhus/query-string)**
- [x] **[moment](https://github.com/headzoo/react-moment)**
- [x] **[braintree-web-drop-in-react](https://github.com/braintree/braintree-web)**
- [x] **[braintree-web](https://github.com/braintree/braintree-web)**

### Server Side

- [x] **[Node.js / Express](https://github.com/expressjs/express)**
- [x] **[MongoDB](https://github.com/mongodb/mongo)**
- [x] **[JWT](https://github.com/auth0/node-jsonwebtoken)**
- [x] **[dotenv](https://github.com/motdotla/dotenv)**
- [x] **[cors](https://github.com/expressjs/cors)**
- [x] **[uuid](https://github.com/kelektiv/node-uuid)**

#### Libraries used in Server-side

- [x] **[cookie-parser](https://github.com/expressjs/cookie-parser)**
- [x] **[loadash](https://github.com/lodash/lodash)**
- [x] **[formidable](https://github.com/node-formidable/node-formidable)**
- [x] **[braintree](https://github.com/braintree)**
- [x] **[morgan](https://github.com/expressjs/morgan)**
- [x] **[mongoose](http://mongoosejs.com/)**
- [x] **[jwt-decode](https://github.com/auth0/jwt-decode)**
- [x] **[moment](https://momentjs.com/)**
- [x] **[express-validator](https://github.com/express-validator/express-validator)**
