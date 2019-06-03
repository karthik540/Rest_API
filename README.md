# Rest_API

A locally hosted Rest API for feeding / testing the SMEF Website.

### Get Started

To host the Rest API locally just run the following command in the Rest_API directory.

**Command:**  
`>json-server --watch db.json`

**Output:**
```
\{^_^}/ hi!
Loading db.json
Done

Resources
http://localhost:3000/message
http://localhost:3000/company
http://localhost:3000/shareholders

Home
http://localhost:3000
```
Once the hosting is successful then u can **GET/POST/PUT/DELETE** to the http://localhost:3000/<field name>/<id></br>  
**Note**: ID for a field is necessary for PUT & DELETE to work properly.
