# Note Manager App
for many clients using meteor.js

## Installation
Install/Update NodeJS, NPM, Meteor, Mongodb. Navigate to directory containing meteorNoteManager.

In your command prompt/shell do:
    meteor create meteorNoteManager

Then cd into meteorNoteManager and install dependencies:
    meteor add accounts-ui accounts-password materialize:materialize

Then run server:
    meteor

## Install Notes
- If you get mongodb errors along the way try resetting and rebuilding:
    meteor reset
    meteor

## Features
-   add new notes to the list
-   Check and uncheck existing notes / todos
-   make notes visible and invisible for other users
-   delete existing notes
-   notes re sorted by timestamp of creation
-   only owners of a note can make it visible / invisible or delete the note
