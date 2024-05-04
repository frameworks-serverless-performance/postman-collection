# Postman collection for testing

This repository contains a Postman collection for testing the endpoints of the API specification used in the thesis *Performance and price comparison of three popular backend frameworks and the AWS serverless stack*.

## Importing and using the collection
Follow these steps to test your implementation of the endpoints:
1. Download the `postman_api_collection.json` file from the repository
1. Install [Postman](https://www.postman.com/) and open it
1. Select *File > Import*  and select the file
1. The collection should now be available
1. Replace the itemId of the `/getPrice` endpoint with the id in your database
1. Replace the initialPrimaryKey of the `/query` enpoint with your initial primary key
1. Click on the collection and go to the *Runs* tab, then click "Run Collection" and select all endpoints.
1. Check that all tests succeeded
1. Done! Now you can start performance testing your implementation!
