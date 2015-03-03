# Definations
NODE.js:
its is a platform build on chrome's javascript runtime for easily buliding network applications.
example.js
var http = require('http');

http.createServer(function (request, response) {
  response.writeHead(200, {'Content-Type': 'text/plain'});
  response.end('Hello World\n');
}).listen(8124);

console.log('Server running at http://127.0.0.1:8124/');
output : Hello World

nodejs is used to build scalable network application.
scalability stand for an application which can be used even after their is a change in its size volume etc.
A Network application is any application running on one host and provides a communication to another application running on a different host, the application may use an existing application layer protocols such as: HTTP(e.g. the Browser and web server), SMTP(e.g. the email-client).
for every framework their must be few pacakage manager


npm init is used to avoid every time usage of npm install and to download all 20 dependencies.It creates package.json file with all dependecies.
when we delete node modules, we can create it again by simply using npm install, where itsearches for all packages required for a project from package.json file and create a node module directory.
