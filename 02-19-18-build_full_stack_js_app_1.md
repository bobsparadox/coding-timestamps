### Stream 1

* [2:34] Setup client folder
  * [2:38] index.html
  * [2:55] Add bootswatch CDN
  * [5:33] Create index.js
  * [6:09] git init
* [6:31] Create a server folder
  * [6:52] Generate Express App
  * [7:38] git init
* [8:03] Convert Express App to JSON API
  * [9:05] Remove view rendering/views folder
  * [9:35] Remove routes folder
  * [10:01] Remove static serve and public folder
  * [10:37] Update error handler
  * [10:42] Add GET / endpoint
* [13:00] Client: Try to make a request
  * [14:13] See the CORS error and remember this moment
  * [15:53] Add CORS to the API
* [18:19] Create database
* [19:02] Initialize knex project
  * [19:02] Install knex and pg
  * [19:24] Create knexfile.js
* [20:58] Create product table migration
* [25:43] Seed product table with sample data
* [28:43] Add api folder and create/mount router
* [32:54] Connect to the database
  * [33:11] Create database connection file
  * [35:53] Create a queries file
* [36:55] List all records with GET /api/v1/products
  * [37:36] Create query
  * [38:09] Create route
* [39:36] List all records in /index.html
  * [39:51] AJAX Request to GET /products
  * [40:28] Append to DOM
  * [46:32] Each product links to /product.html?id=:id
  * [47:31] Display a link to /create.html
* [50:37] Show one record with GET /api/v1/products/:id
  * [51:16] Validate id
  * [52:51] Create query
  * [53:25] Create route
* [55:27] Show one record in /product.html?id=:id
  * [55:54] Parse query string to get id
  * [58:41] AJAX Request to GET /products/:id
  * [1:00:53] Append to DOM
  * [1:03:30] Display link to /edit.html?id=:id
