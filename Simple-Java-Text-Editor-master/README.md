# Simple Java Text Editor

**PH NotePad** is a simple and light **text editor** (notepad) written in Java.

![Programming Java Text Editor](Screenshots/text-editor-writing-icon.svg)


* Search tool (to search text/keywords easily in the code) + highlighting the code found.

* Find/Replace text/code.

* Auto completion for Java and C++ keywords (files need to be saved as *.java*/*.cpp*). It can be easily expanded to support pretty much any number of languages.

* Drag and Drop (drag files into the text area and they get loaded).

* Nice image buttons for better UX.


![Example Java Text Editor](Screenshots/find-replace-word-in-java-text-editor.png)


\
## DEMO

Download the Jar file and double click to run

Or run `java -jar SimpleJavaTextEditor.jar` from the command line

You can also generate easily a new jar file with the following command when you are in *src/* directory `jar cmvf ../manifest.mf ../SimpleJavaTextEditor.jar simplejavatexteditor/*.class`


### Important

**Icons directory and its files must be present on the path when running the application (so you will have to move "*icons/*" into "*src/*" directory)**


## LICENSE

Apache License, Version 2.0 or later; See the license.txt file in the notepad folder.
