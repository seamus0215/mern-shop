### Amazon Clone Build

1. Website Template
   1. create shop directory
   2. create template folder
   3. create index files, add default HTML code, link file to css, and create site structure.

2. Create React App
    1. npx create-react-app frontend
    2. npm start
    3. remove unused files
    4. copy index.html content to App.js
    5. copy style.css content to index.css
    6. replace class with className.

3. Build Product Screen
   1. Install react-router-dom
   2. Use BrowserRouter and Router for the Home Screen
   3. Create HomeScreen.js
   4. Add product list code
   5. Create ProductScreen.js
   6. Add new Route from product detail to App.js
   7. Create 3 columns for product image, info and action

4. Create Node.js Server
   1. run npm init in root folder
   2. Update package.json set type: module
   3. Add .js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server.js
   7. require express
   8. create route for / in the backend
   9. move products.js to backend
   10. create route for /api/products
   11. return products
   12. run npm start

5. Load Products From Backend
   1. edit HomeScreen.js
   2. define products, loading and error
   3. create useEffect
   4. define async fetchData and call it
   5. install axios
   6. get data from /api/products
   7. show them in the list
   8. create Loading Component
   9. create Message Box Component
   10. use them in HomeScreen