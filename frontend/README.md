# 1

1. create react app
2. create header section
3. create github repo and commit the first changes

# 5. List Products

1. create product array
2. add product images
3. render products
4. style products

# 6

1. npm i react-router-dom
2. create route for home screen
3. create route for product screen

# 7 Create nodejs server

1. run npm init in the root folder
2. Update package.json set type: module
3. Add .jsto imports
4. npm install express
5. create server.js
6. add start command as node backend/server.js
7. require express
8. create route for / return backend is ready
9. move products.js from frontend to backend
10. create routes for /api/products
11. return products
12. run npm start

# 8 Fetch products from backend

1. set proxy in package.json
2. npm install axios
3. useState hook
4. useEffect hook
5. useReducer hook

# 9 Manage state by useReducer hook

1. define reducer
2. update fetch data
3. get state from useReducer

# 10. Add Bootstrap to UI framework

1. npm install bootstrap bootstrap
2. update app.js

# 11. Create Rating and Product Component

1.  Create Rating Component
2.  Create Product Component
3.  Use Rating Component in Product Component

# 12. Create Product details screen

1. Fetch Products from backend
2. create three columns for image, info, and action

# 13. Create loading and message component

1. create loading component
2. use spinner component
3. create message component
4. create utils.js to define getError function

# 14. Implement add to cart

1. Create React Context
2. define reducer
3. create store Provider
4. implement add to cart button click handler

# 15. Complete add to cart functionality

1. check exist item in the cart
2. check count in stock in backend

# 16. Create Cart Screen

1. create 2 columns
2. display items list
3. create action column

# 17. Complete cart screen

1. click handler for dec/inc button
2. click handler for remove item
3. click handler for checkout

# 18. Create Signin Screen

1. create signin form
2. add email and password
3. add signin button

# 19 Connect to Mongodb database

1. create atlas mongodb database
2. install local Mongodb database
3. npm install mongoose
4. connect to Mongodb database

# 20 Seed sample data to mongodb database

1. create product model
2. create user model
3. create seed route
4. use seed route in server.js
5. seed sample products

# 21. Seed sample users

1. create user models
2. seed sample users
3. create user routes

# 22. Create Signin Backend API

1. create signin api
2. npm install jsonwebtoken
3. define generate token

# 23. Complete Signin screen

1. handle submit action
2. save token in store and local storage
3. show user name in header

# 24. Create Shipping Screen

1. create form inputs
2. handle save shipping address
3. add checkout wizard bar

# 25 Create Signup Screen

1. create input forms
2. handle submit
3. create backend api

# 26 Implement select payment method screen

1. create input forms
2. handle submit

# 27. Create placeorder screen

1. show cart items, payment and address
2. handle place order action
3. create place order api

# 28 Implement place order action

1. handle place order action
2. create order create api

# 29 Create Order Screen

1. create backend api for order/:id
2. fetch order api in frontend
3. show order information in 2 columns

# 30 Pay Order by PayPal

1. generate paypal client id
2. create api to return client id
3. install react-paypal-js
4. use PayPalScriptProvider in index.js
5. use usePaypalScriptReducer in Order Screen
6. implement loadPayPalScript function
7. render PayPal button
8. implement onAprove payment function
9. create pay order api in backend

# 31 Display Order History

1. create order screen
2. create order history api
3. use api in frontend

# 32 Profile Screen
1. get user info fron context
2. show user information
3. create user update api
4. update user info