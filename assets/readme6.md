# Create Inventory Master

## Phase 1: Inventory App Models

### Instructions

The goal for this phase is to write three API routes and your inventory mongoose model. First, create your inventory mongoose model.

Your model must include one field called itemName. It needs to be a string, it must be unique, and it must be required and have an error message if it is not included.

Your model must include another field called itemCount. It needs to be a string, and it must be required and have an error message if it is not included.

Your model must include another field called itemID. It needs to be a string, it must be unique, and it must be required and have an error message if it is not included.


## Phase 2: Inventory App Routes

### Instructions

Next you need to write the following into the api-routes.js file:

A GET route to /api/inventory that will find everything from the Mongo database and return it to the client using res.json.

A POST route to /api/inventory that will create a new document in the inventory Mongo collection from whatever is given by the client and return the response to the client using res.json.

A PUT route to /api/inventory that will update an existing document by its itemID field and set the value of itemCount to the incoming itemCount. Then return whatever the response is using res.json.


## Phase 3: Inventory App Tests

### Instructions

Test your routes and model using Postman. Your data should be formatted like so:

POST request should include itemCount, itemID, and itemName.

PUT request should include itemCount and itemID.


## Phase 4: Inventory App AJAX

### Instructions

For this phase, open the app.js file in the public folder and add the three AJAX methods to make a GET request, POST request, and PUT request. Follow the directions inside the app.js file.

All the HTML is written. You only need to fill in the JavaScript for the AJAX methods and what goes inside of them.

Write one method at a time and then test it before moving on to the next.


## Phase 5: Inventory App Deploy

### Instructions

Upload this app to a Github repo and then deploy this app to Heroku.
