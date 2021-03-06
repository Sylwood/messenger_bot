# messenger_bot
Send mass DMs on Facebook Messenger

Having been in a bunch of clubs during my time in college, I've often found myself in the position of having to individually send the same direct message to a large group of club members at once. For example, if I'm organizing a meeting, I want to check in with everybody who hasn't RSVP'd to the event. `messenger_bot` allows me to do this without having to go through the hassle of multiple copy-and-pastes. 

`messenger_bot` uses [`facebook-chat-api`](https://www.npmjs.com/package/facebook-chat-api) to log in, find recipients, and send messages. 

**Disclaiimer:** As of now, using this app will make Facebook think that your Facebook account was hacked. You'll have to generate a new password. But that only takes like 10 seconds compared to the >1 minute you'd have to spend messaging people...right?

## Get Started

Install dependencies:
```
$ cd api && npm install
$ cd ..
$ cd client && npm install
```

Start the backend:
```
$ cd api
$ npm start
```
Start the frontend:
```
$ cd client
$ npm start
```
Navigate your browser to `localhost:3000`.
