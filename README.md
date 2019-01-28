# ChatBot
This repository contains all of the chatbot files used with Pandorabots to generate the dialogue for Nico (Fall) and Emma (Spring). It also contains two Python files for connecting to the Pandorabots Python API. 

These two files allow you to upload and then talk to a bot using the Pandorabots Python API. You will need to open both files and edit the User Key and App ID. 

The Create_List_Load program allows you to do the following:
* List all the files belonging to a particular bot
* Create a new bot (arg: list bot)
* Compile an existing bot (arg: compile bot)
* Upload a directory of files to a bot (arg: upload bot directory)
* Upload a single file (arg: uploadsingle bot file)
* Delete a bot (arg: delete bot)
* Reset a bot (arg: reset bot)
* Delete a single file (arg: deleteFile bot filename)

IMPORTANT
    For any file upload, the files have to be in the same directory as the program
