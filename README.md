# task-manager-app-api

A REST API for a task manager app implemented in Node.js/Express.js.

The API consists of two resources: users and tasks. Each user can perform CRUD operations on their profile and tasks. [MongoDB](https://www.mongodb.com/) is used as database. Endpoint testing is implemented with [Jest](https://jestjs.io/). The API and database were deployed to [Heroku](https://devcenter.heroku.com/) and [Atlas](https://www.mongodb.com/cloud/atlas), respectively.

## Technologies
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/), [Mongoose](https://mongoosejs.com/)
- [Jest](https://jestjs.io/)
- [Sendgrid](https://www.npmjs.com/package/@sendgrid/mail) (email service) 
- [Multer](https://www.npmjs.com/package/multer) (file upload)


## Local setup
- Clone the repo: `git clone https://github.com/TulioMolina/task-manager-app-api.git`
- Install dependencies: `npm install`
- Run locally on port 3000: `npm run dev`

Deployed API at this [link](https://tm-task-manager.herokuapp.com/)