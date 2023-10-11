## Getting started
1. The first step you need to do is clone this repository. 

2. To run the server, locate your operating system and run the associated command in your terminal at the root of the project.

| Your OS               | Command to start the API                                  |
| --------------------- | --------------------------------------------------------- |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-osx`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux` |


#### WINDOWS USERS -- Setting Environment Variables
If you are using a windows machine:
1. `cd` into the root of the project containing data.json 
2. Run the following command to add the environment variable:
```set DATA_FILE=./data.json```

Note that this process will use your terminal tab, so you will have to open a new tab and navigate back to the project root to start the front end.

2. Top start the frontend, open another terminal tab and being at the root of this project, install the dependencies by running `npm install && npm start`. So, you should be able to access http://localhost:3000.






