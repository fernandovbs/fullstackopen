title Creates a new note

Browser->Server: HTTP POST https://fullstack-exampleapp.herokuapp.com/new_note
note right of Server: Server creates a new note
Server->Browser: Server returns 302 code
note right of Browser: Browser redirects to /notes
Browser->Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/notes
Server->Browser: HTML code
Browser->Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/main.css
Server->Browser: main.css
Browser->Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/main.js
Server->Browser: main.js
note right of Browser: Browser executes javascript
Browser->Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/data.json
Server->Browser: [{"content":"HTML is easy","date":"2019-05-23T17:30:31.098Z"},...]
note right of Browser: Browser executes event handler and draws notes HTML list
