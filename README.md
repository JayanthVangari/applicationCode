# Application requirements:
web application is a react-express app. with front end done in react-redux, and nodejs is the back-end server language with mongoDB backend.

make sure you have Nodejs (v9.3.0) ,npm , react (v16.2.0) and mongoDB(v3.2.10) installed on your system

## To run application


firstly, spin up mongodb server with command -> mongod --dbpath=data/db/ ( make sure you already created data/db/ directory )

secondly, Navigate to the application folder with 'package.json' file

and run commands:

1.
	npm install

2.	
	npm run server
	

3. npm start
	
	
and application runs on http://localhost:3000/


-> You can find server logs in err.log and out.log





Folder Structure:

app-submission
|__ public
|	|__favicon.ico
|	|__index.html
|	|__manifest.json
| 	
|__server 				/* contains server code */
|	|__config
|	|	|__database.js
|	|
|	|__models
|	| |__Applicants.js
|	|
|	|__routes
|	|	|___index.js
|	|
|	|__views
|	|	|__index.jade
|	|	|__error.jade
|	|	|__layout.jade	
|	|__app.js
|	|
|____src				/* react front end code */
|	|	|__	actions
|	|	|	|__actionTypes.js
|	|	|	|__adminActions.js
|	|	|	|__code.js
|	| 	|	|__index.js
|	|	|	|__users.js
|	|	|__components
|	|	|	|___Admin
|	|	|	|	|__Results.js	
|	|	|	|	|__Results.css
|	|	|	|___codesubmit
|	|	|	|	|__codeSubmission.js	
|	|	|	|	|__codeSubmission.css
|	|	|	|___Home
|	|	|	|	|__Home.js	
|	|	|	|	|__Home.css
|	|	|__store
|	|	|	|___reducers
|	|	|	|	|__	adminReducer.js
|	|	|	|	|__users.js
|	|	|__App.js
|	|	|__App.css
|	|	|__App.test.js
|	|	|__index.css
|	|	|__index.js
|	|__package.json			/* dependencies */
|	|__package-lock.json
|	|__err.log				/* server logs*/
|	|__out.log
|	|__README.md			/* this file*/



	


