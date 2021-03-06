#### ChaiHttp with Mocha & Javascript

The mini-project I created to practice API testing. I used chaiHttp because it was easy to follow and understand. ChaiHttp tests HTTP apps or external services and provides chai expect and should interfaces.

For me, I believe this is a straight forward process. Install the Mocha framework followed by installing chaiHttp and start automating API request and responses. 

The next step is to test API request & responses. Online there are tons of information and helpful websites which you can explore but I decided to set up my JSON server so I can get my own full fake REST API.

Useful websites which you may want visit to get test data:

[Random User](https://randomuser.me/)

**Packages in this repo**

- Chai
- Chaihttp
- Json-server
- Mocha

Once you download the repository. Go to the project directory

Script to run: `npm install`

To run the JSON server, run the following script

script to run: `json-server --watch db.json`

This will listen to the db.json file

Go to the Test directory to run all the tests

Script to run:  `npm test`

**I have covered Get,Post,Put,Delete Requests**