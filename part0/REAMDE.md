# Diagrams


## 0.4: new note
~~~
title User creates a new note

User->Text Field: write something into the text field
Text Field->Text Field: the input listen the event of pressing keys
Text Field->Text Field: the listener collects characters
User->Submit Button: the user hit Submit button
Submit Button->Server: all the characters are sent to the server
Server->Server: data is processed
Server->List: data response is sent to List hanlder
List->List: data is received and displayed
~~~


## 0.5: Single page app
~~~
title user goes to the single page app 

User->Browser: introduce URL
Browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa
server->Browser: return files from resource
Browser->Browser: Browser loads and read files to render DOM CSSOM tree
Browser->User: Browser Prints the page in the screen
~~~


## 0.6: New note
~~~
title the user creates a new note using the single page version of the app.

User->Browser: introduce URL
Browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa
server->Browser: return files from resource
Browser->Browser: Browser loads and read files to render DOM CSSOM tree
Browser->User: Browser Prints the page in the screen
User->Text Field: write something into the text field
Text Field->Text Field: the input listen the event of pressing keys
Text Field->Text Field: the listener collects characters
User->Submit Button: the user hit Submit button
Submit Button->Server: all the characters are sent to the server
Server->Server: data is processed
Server->List: data response is sent to List hanlder
List->List: data is received and displayed
~~~