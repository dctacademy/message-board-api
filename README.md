# message-board-api

1. clone the repo `git clone https://github.com/dctacademy/message-board-api.git`
2. from command prompt / terminal go inside the folder 
3. run `npm install`
4. run `node index.js`

| method | url | action | request | response | auth |
|-----|-------|--------|---------|------| ------|
| GET | /messages | lists all messages | - | empty array or array of objects | no | 
| POST | /messages | create a message | { body: 'message body' } | { id: 1243, body: 'message body', createdAt: '2020/02/02' } | no |
| GET | /messages/:id | get a message | - | { id: 1243, body: 'message body', createdAt: '2020/02/02' } | no |
