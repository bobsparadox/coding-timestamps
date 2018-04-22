### Stream 2

* [4:09] Create a record with POST /api/v1/products
  * Create route
  * Validate product!
  * Create query
* [19:45] Create a record in /new.html
  * Display a form with input boxes for all fields
  * Display a button to submit the creation of the resource
    * Validate all inputs
    * POST /products
    * Successful creation should redirect to /product.html?id=:id
* [47:25] Update a record with PUT /api/v1/products/:id
  * Create route
  * Validate id
  * Validate updates
  * Create query
* [1:01:10] Update one record in /product.html?id=:id
  * Display a form with input boxes for all fields
  * Display a button to submit the update of the resource
    * Validate all inputs
    * PUT /products/:id
    * Successful update should redirect to /product.html?id=:id
* [1:17:36] Delete a record with DELETE /api/v1/products/:id
  * Create route
  * Validate id
  * Create query
* [1:20:23] Delete a record
  * Add a delete button to the /product.html page
    * DELETE /products/:id
    * Successful deletion should redirect to index.html
* [1:25:32] Deploy server to Heroku
  * Signup and login to heroku
  * Install the heroku CLI
  * Create a heroku app
  * Push to heroku
  * View heroku logs
* [1:28:22] Add Postgres DB to Heroku
  * Add postgres addon
  * Add production connection to knex
  * Run migrations on production DB
  * Run seeds on production DB
* [1:29:50] Deploy client to firebase
  * Signup and login to firebase
  * Install the firebase CLI
  * Create a firebase app
  * Push to firebase
