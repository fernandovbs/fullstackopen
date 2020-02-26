title New note SPA

note right of Browser: Form submit triggers onFormSubmit Event \nBrowser pushes new note to notes array \nBrowser redraws notes HTML list
Browser->Server: HTTP POST https://fullstack-exampleapp.herokuapp.com/new_note_spa
Server->Browser: returns 201 {"message":"note created"}
