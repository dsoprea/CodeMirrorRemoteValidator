An asynchronous CodeMirror lint plugin that will receive code, send it to a 
callback (that can send it somewhere via Ajax, etc..), and apply any discovered 
errors on return. It's meant to be convenient and uncomplicated.

This example simply, statically, submits the same, single error to CodeMirror, 
every time, no matter what the code says. There is also an example of a 
"warning"-type decoration.

![alt text](https://github.com/dsoprea/CodeMirrorRemoteValidator/raw/master/screenshot1.png "Screenshot 1")

![alt text](https://github.com/dsoprea/CodeMirrorRemoteValidator/raw/master/screenshot2.png "Screenshot 2")

![alt text](https://github.com/dsoprea/CodeMirrorRemoteValidator/raw/master/screenshot3.png "Screenshot 3")

