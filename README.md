# SnippetSource

**SnippetSource** lets you organise your favorite pieces of code, scripts, thoughts, notes or other documents in a user definable tree structure. 
All data is stored in a simple yet powerful **SQLite** database which provides you immediate access to your stored snippets.   

Create new folders and documents, or you can drag and drop one or multiple files into the treeview to create them as snippets in SnippetSource. Nodes can be moved freely by dragging them to another folder. 

It uses the text editor module which was developed for my [Notepas](https://github.com/beNative/Notepas) project, which is in turn based on the SynEdit components used by Lazarus for its source code editor. This has the convenient side effect that the capabillities of the text editor grow as Lazarus evolves.

My intention is to keep the user interface as clean and fast as possible so users can focus more on the content rather than confront them with an overwhelming and bloated user interface.

## Project sources and releases

The sources are maintained on this location, together with all dependencies needed to make a new build:
http://github.com/beNative/lazarus/tree/master/projects/snippetsource

New [builds](https://github.com/beNative/SnippetSource/releases) will be released in this spot.

## Code snippets

![SnippetSource](https://github.com/beNative/lazarus/blob/master/projects/snippetsource/images/SnippetSource2.png)

![SnippetSource](https://github.com/beNative/lazarus/blob/master/projects/snippetsource/images/SnippetSource3.png)

![SnippetSource](https://github.com/beNative/lazarus/blob/master/projects/snippetsource/images/SnippetSource.EditorMenu.png)

## Support for Richtext

Images can be dragged and dropped into both the treeviewer and the Richeditor.

![SnippetSource](https://github.com/beNative/lazarus/blob/master/projects/snippetsource/images/SnippetSource.png)

![SnippetSource](https://github.com/beNative/lazarus/blob/master/projects/snippetsource/images/SnippetSource1.png)

## Execute scripts

Since version 3 the possibility to execute script code was added. Snippets that represent script code can directly be executed. Output is redirected to an interactive ANSI compatible console.

![SnippetSource](https://github.com/beNative/lazarus/blob/master/projects/snippetsource/images/SnippetSource.ConsoleOutput.png)

## SQLite database

Any SQLite database administrator tool like [SQLiteStudio](https://sqlitestudio.pl) or query tool like [DataGrabber](https://github.com/beNative/DataGrabber) can be used to get access to the database.

![ERD](https://github.com/beNative/lazarus/blob/master/projects/snippetsource/documents/snippetsource-snippets.png)
