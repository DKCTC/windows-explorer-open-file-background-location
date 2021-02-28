# windows-explorer-open-file-background-location
Windows Registry files for adding Explorer context-menu options for opening new Explorer windows at either a file's location or by using the Explorer window background, such as in a File->Open or File->Save dialogs that do not allow the user to select the path.

For example, in a File->Open or File->Save dialog where the user cannot select the path, after loading these registry entries, you will be able to right-click on the dialog background, and select **Open this folder in new window**, which will open a new Explorer window at that location.

Similarly, you can right-click on a file, and select **Open file location in new window**, which will open a new Explorer window at the selected file's location.

It is pretty simple, actually. I was annoyed by File->Open/File->Save and other similar dialogs that do not allow the user to select the path. This happens when I am saving files to a location, and the program that I'm using remembers the location, but won't let me copy the path. Problem solved!

If something goes wrong and it isn't working for you, please create an Issue.
