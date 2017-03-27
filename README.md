
<h2> Mean JS Boiler Plate </h2>

#######  To Build  ########
$ grunt build 

#######  Build and run the server in development mode #######  
$ grunt debug
or
$ gulp debug

#######  Build and run the server in production mode #######  
$ grunt prod

#######  Run server alone in dev/prod mode #######    

Dev mode:
$ set NODE_ENV=dev&& node server.js
(or)
$ grunt env:dev concurrent:default

Prod Mode:
$ set NODE_ENV=prod&& node server.js
(or)
$ grunt env:prod concurrent:default

#######  Debug (server and client) the application in chrome using dev tools ######

Run below command only once
$ npm install -g devtool

To debug: 
$ devtool server.js

You can set break points and then reload the debugger (Cmd/Ctrl + R), 
or you can set an initial breakpoint with the --break flag.
$ devtool app.js --break

For more detail to debug visit
https://mattdesl.svbtle.com/debugging-nodejs-in-chrome-devtools 




