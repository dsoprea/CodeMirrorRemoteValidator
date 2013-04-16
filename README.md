An asynchronous CodeMirror lint plugin that will receive code, send it to a 
callback (that can send it somewhere via Ajax, etc..), and apply any discovered 
errors on return. It's meant to be convenient, not complicated.

Just drop a copy of CodeMirror into a directory named "codemirror", and the 
example should work. Although the error shown does correspond to the code, this
example simply, statically, submits the same, single error to CodeMirror, 
every time, no matter what the code says.

![alt text](https://github.com/dsoprea/CodeMirrorRemoteValidator/raw/master/screenshot.png "Screenshot")

