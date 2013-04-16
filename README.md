A simple CodeMirror asynchronous lint plugin of convenience that will receive 
code, send it to a callback (that can send it somewhere via Ajax, etc..), and 
apply any discovered errors on return.

Just drop a copy of CodeMirror into a directory named "codemirror", and the 
example should work. Although the error shown does correspond to the code, this
example simply, statically, submits the same, single error to CodeMirror, 
every time, no matter what the code says.

![alt text](https://github.com/dsoprea/CodeMirrorRemoteValidator/raw/master/screenshot.png "Screenshot")

