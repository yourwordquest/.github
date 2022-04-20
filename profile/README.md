# [YourWord.Quest](https://yourword.quest)

This organization holds the code running https://yourword.quest
It's split as follows:

### [yourwordquest/data](https://github.com/yourwordquest/data)
This is the repo to go to for all the data needs, it sets up schemas, indices and queries for various databases. It's also used to load data to the databases.

### [yourwordquest/public-api](https://github.com/yourwordquest/public-api)
This repo is the backend, make sure you've done the necessary setup under `yourwordquest/data` before trying to run the API

### [yourwordquest/webapp](https://github.com/yourwordquest/webapp)
The main UI. Make sure that you have a working API before running this UI
