This can be used to expose HTTP GET service with a JSOn response to be used in angular-part05 lab
##Step 01: Install json-server
    npm -install json-server 
##Step 02: 
	Use students.json in this folder to start ng-server with a port 4444
       json-server students.json --port=4444
##Step 03: Access the GET service
	You can access the service using the url
        Resources:  http://localhost:4444/students
        Home:  http://localhost:4444