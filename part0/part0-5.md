title Single page App

Browser->Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/spa
Server->Browser: HTML Code
Browser->Server: https://fullstack-exampleapp.herokuapp.com/main.css
Server->Browser: main.css
Browser->Server: https://fullstack-exampleapp.herokuapp.com/spa.js
Server->Browser: spa.js
note right of Browser: Browser executes javascript
Browser->Server: https://fullstack-exampleapp.herokuapp.com/data.json
Server->Browser: [{"content":"HTML is easy","date":"2019-05-23T17:30:31.098Z"},...]
note right of Browser: Browser executes event handler \nBrowser draws notes HTML list
