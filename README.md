![CF](http://i.imgur.com/7v5ASc8.png) LAB-41
=================================================

## React Native 

### Author: Vanessa

This is an app help you manage your shopping list. You can add items into the shopping list, mark as complete or incomplete. 

### Assignments
Create your first Phone App. What it does and how it looks is up to you. This is an opportunity to play around with whats possible in React Native and to get a feel for how you can get into the various device features.

This is a 2-day assignment, after which you will live-demo your phone app to the class (at the start of class 43)

**Day 1** - Focus on getting your dev system up and operational and getting "proof of life"

**Day 2** - Add in the device features, polish, and prepare for deployments.


### Requirements
* Use 2 screens
* Use and share state between components/screens
* Use at least 1 native device feature (contacts, camera, gps, etc)
### Notes
* You may not alter the functionality of the existing application
* You may only grant access using RBAC
* You may test with your own API server
* You must either deploy that server and configure your React application to use it, or you may use the official API deployment at https://api-js401.herokuapp.com
* The API server has the following user accounts (username:password) that you can use to login as a user with varying permissions
  * admin:ADMIN (create, read, update, delete)
  * editor:EDITOR (create, read, update)
  * user:USER (read)
  
### Setup
#### `.env` requirements
* `npm i` install dependencies

#### Running the app
* `npm start` Start the App

### Components
```
├── Main.js
├── components
│   ├── Button.js
│   ├── Header.js
│   ├── Input.js
│   ├── List.js
│   └── SubTitle.js
└── utils
    └── Colors.js
```
