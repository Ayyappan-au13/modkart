# ModKart ECommerce Website


Welcome to my React and Node tutorial to build an e-commerce website. 
Created e-commerce website using MERN stack (MongoDB, ExpressJS, React and Node.JS).

## Demo Website



## Technology Used in this Project

- HTML5 and CSS3
- React: Components, Props, Events, Hooks, Router, Axios
- Redux: Store, Reducers, Actions
- Node & Express: Web API, Body Parser, File Upload, JWT
- MongoDB: Mongoose, Aggregation
- Development: ESLint, Babel, Git, Github,
- Deployment: Heroku


## Run Locally

### 1. Clone repo

```
$ git clone 
$ cd modkart
```

### 2. Setup MongoDB

- Local MongoDB
  - Install it using the link (https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/modkart 

### 3. Run Backend

```
$ npm install
$ npm start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Seed Users and Products

- Run this on chrome: http://localhost:5000/api/users/seed
- It returns admin email and password
- Run this on chrome: http://localhost:5000/api/products/seed
- It creates sample products

### 6. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin

