# Node.js & MSSQL Promises using Express with MVC and using async -> await 
This is a very basic example of CRUD in Node.js and MSSQL with Model View Controller and async await.
## Installation
*for newbies : Clone or download zip to your machine then hit this :

	npm install

## Configuration (database)
util/db.js

     const dbConfig = {
   	"server": "REMY\\ZKTECO", //dbname
    	"user": "sa", //dbusername
    	"password": "password", //password
    	connectionLimit: 10,
    	options: {
       	 trustedConnection: true
   	 }
    };


	
You're gonna need to create a DB named 'nodejs'

## NOTES
This repo use Express 4.x.

## Open your Browser
And type: localhost:3000
