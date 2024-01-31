Features
1. Product and Product Variant CRUD Operations
Endpoints:
Create Product: POST /api/products

Create a new product with a name, description, price, and optional variants.
Update Product: PUT /api/products/{id}

Update an existing product's details.
Delete Product: DELETE /api/products/{id}

Delete a product and its associated variants.
Retrieve Product: GET /api/products/{id}

Retrieve details of a specific product, including its variants.
Product Structure:
A product has at least:
Name
Description
Price
A product can have multiple variants.


A variant has:
Name
SKU
Additional cost
Stock count
2. Search Functionality
Endpoint:
Search Products: GET /api/products/search?q={query}
Search products by product name, description, or variant name.
3. Test Driven Development (TDD)
Unit tests have been implemented for models to ensure correct data storage and retrieval.
Endpoint tests have been created to validate the functionality of each API endpoint.
Search functionality is covered by tests to ensure accurate and expected results.


Setup
Clone the repository: git clone https://github.com/abhishek369369/E_Commerce_API.git
Install dependencies: npm install
Configure your environment variables.
Run the tests: npm run test
