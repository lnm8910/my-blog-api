# my-blog-api
Proof of concept of an api built on Node JS and deployed on Firebase. 

### Steps:

1. `npm install -g firebase-tools`
   
2. Create new Project in Firebase

3. Once your project is created, open it in the console and click Cloud Firestore

4. npm install -g firebase-tools

5. Create your directory: `mkdir my-blog-api` and 

6. `firebase login --no-localhost`

7. Run `firebase init` to initialize the firebase project

8. `cd functions`

9. `npm i express`

10. `npm i cors`

11. run `firebase deploy` to deploy the app to firebase

### Running Application
Run the below command to start the application.

`npm run serve`

### API Reference: 
#### Create
POST http://localhost:5001/fir-api-c098e/us-east1/app/api/create

Payload: 
`{
"id": 1,
"item": "Item Name"
}`

#### Get All
GET http://localhost:5001/fir-api-c098e/us-east1/app/api/read

#### Update
PUT http://localhost:5001/fir-api-c098e/us-east1/app/api/update/1

Payload:
`{
"id": 1,
"item": "Modified Item Name"
}`

#### Delete
DELETE http://localhost:5001/fir-api-c098e/us-east1/app/api/delete/1
