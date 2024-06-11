# chat-application
Any user can use their email id to chat and discuss about the current affairs. React JS is used for frontend and NodeJS and Express along with MongoDB Database is used as Backend. Firebase is used for Google Authentication.




# frontend -dependencies:
"dependencies": {

"@emotion/react": "^11.10.5",
"@emotion/styled": "^11.10.5",
"@material-ui/core": "^4.12.4",
"@material-ui/icons": "^4.11.3",
"@mui/icons-material": "^5.10.9",
"@mui/material": "^5.10.12",
"@testing-library/jest-dom": "^5.16.5",
"@testing-library/react": "^13.4.0",
"@testing-library/user-event": "^13.5.0",
"emoji-picker-react": "^3.5.1",
"firebase": "^9.13.0",
"react": "^18.2.0",
"react-dom": "^18.2.0",
"react-scripts": "5.0.1",
"web-vitals": "^2.1.4"
},



 # Components used:
Public Chat Functionality
Sending Text Messages
Sending Images
Sending Emoji Messages
Deleting Sent Messages
Editing Sent Messages
Adding New Chats
Editing Chats Info
Deleting Chats
Feedback Contact Form



# hosted link
https://messenger-c4890.web.app/
 backend -dependencies:

 "devDependencies": {

"nodemon": "^2.0.22"
},

 "dependencies": {

"cors": "^2.8.5",
"dotenv": "^16.0.3",
"express": "^4.18.2",
"mongodb": "^5.2.0"
}

# API-Endpoints:
Chats:
GET /chat
POST /chat
PUT /chat/:id
DELETE /chat/:id


# Messages:
GET /chat/:id/messages
POST /chat/:id/messages
PUT /chat/:id/messages/:msgId
DELETE /chat/:id/messages/:msgId


# Demo:
https://www.kapwing.com/videos/6372f2b0bfdfd30011d528df



