# SocialNetworkAPI

![MIT-licensed](https://img.shields.io/badge/license-MIT-red)

## Table of Contents
* [Description](#description)
* [Application Demo](#application-demo)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Test Instruction](#tests)
* [Github Link](#github)
* [Reach me for any additional queries](#email)

## Description
This is an API for a social network web application where users can share their thoughts, react to friends' thoughts, and create a friend list. 

## Application Demo
The following video link shows the functionality of the Social Network API:

[Social Network API application demo](https://drive.google.com/file/d/1xOJM7ZHnTr5dT8pFLdCo2KHxb90IMQDc/view)

## Installation
Run the following at the command line
    - npm init
    - npm install express
    - npm install mongoose
    - npm install moment is required

Run 'npm start' to start the server

## Usage
This is an API for a social network web application where users can share their thoughts, react to friends' thoughts, and create a friend list. It uses Express.js for routing, a MongoDB database, the Mongoose ODM, and Moment.js to format timestamps. The seed data is created using Insomnia

## License
![MIT-licensed](https://img.shields.io/badge/license-MIT-red)

## Contributing
 Mahalakshmi Rajendran

## Test Instructions
On Insomnia, the following API routes have been created and used to add, update, or remove users, friends, thoughts, and reactions in the user's database.

📁 USER

Create a new user: POST /api/users

Get all users: GET /api/users

Get a single user by its id: GET /api/users/:userId

Update a user by its id: PUT /api/users/:userId

Delete a user by its id: DELETE /api/user/:userId

📁 FRIEND

Add a new friend to a user's friend list: POST /api/users/:userid/friends/:friendId
Delete a friend from a user's friend list: DELETE /api/users/:userid/friends/:friendId

📁 THOUGHT

Create a new thought: POST /api/thoughts/
Get all thoughts: GET /api/thoughts/
Get a single thought by its id: GET /api/thoughts/:thoughtId
Update a thought by its id: PUT /api/thoughts/:thoughtId
Delete a thought by its id: DELETE /api/thoughts/:thoughtId

📁 REACTION

Create a reaction: POST /api/thoughts/:thoughtId/reactions
Delete a reaction by the reactionId: DEL /api/thoughts/:thoughtId/reactions/:reactionId

## Github
Visit my github profile here: [Maharjn](https://github.com/Maharjn)

## Email
Email me with any questions : maharajendran.89@gmail.com
