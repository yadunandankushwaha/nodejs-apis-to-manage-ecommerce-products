# nodejs-ecommerce-manage-product-apis
NodeJs api's to manage ecommerce website products. (you can manage fields as per your need) <br><br><br>
Note: Follow below step to install fresh Node js project OR Directly run project using clone of my project.<br><br>
Step 1) Install Node in your system | using npm init and create package.json file<br>
Step 2) Creating Database  OR use my database file from root directory and update the credentials in index.js file<br>
Step 3) Install Dependencies using:   npm install --save express mysql body-parser hbs <br>
step 4) Run node in your system using: node index<br>

#Start using API's<br>
1) Get all Products (Method GET): http://localhost:3000/api/products/<br>
2) Get Single Product using Product Id (Method GET): http://localhost:3000/api/products/1<br>
3) Create Product (Method POST): http://localhost:3000/api/products/ <br>
            Body param: {
                "product_name": "Product 6 Added",
                "product_price": 6000
            }
4) Update Product using Product Id (Method PUT): http://localhost:3000/api/products/2<br>
            Body param: {
                "product_name": "Product 2 Update",
                "product_price": 7000
            }
5)  Delete Product using Product Id (Method DELETE): http://localhost:3000/api/products/6
