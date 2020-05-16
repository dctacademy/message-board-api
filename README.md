# message-board-api

1. clone the repo `git clone https://github.com/dctacademy/message-board-api.git`
2. from command prompt / terminal go inside the folder 
3. run `npm install`
4. run `node index.js`

## REST API's

| method | url | action | request | response | auth |
|-----|-------|--------|---------|------| ------|
| GET | /messages | lists all messages | - | empty array or array of objects | no | 
| POST | /messages | create a message | body - string | id - number, body - string, createdAt - date | no |
| GET | /messages/:id | get a message | body - string | id - number, body - string, createdAt - date | no |
| PUT | /messages/:id | update a message | body - string | id - number, body - string, createdAt - date | no |
| DELETE | /messages/:id | delete a message | id - number | - | no |
