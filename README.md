# Property Journal

> Keep a journal for your home. 

*Currently migrating hosting*

![screenshot](/assets/propertyjournal.png)

A helpful tool for homeowners to manage and keep track of their property records. After logging in to the site, users are be able to store information about their home, including details such as pictures, dates, and descriptions of repairs, upgrades, and purchases. This information is organized using category tags, making it easy for users to find what they are looking for. In addition to helping homeowners keep track of their records, this site is also useful for documenting the history and value of a property.

## How It's Made:

**Front end:** HTML, CSS, JavaScript, Bootstrap

**Back end:** Node, Express, MongoDB, Mongoose, Cloudinary, Passport

Compartmentalized build using MVC architecture. Users are authenicated using Passport.js. Images and photes are uploaded to Cloudinary using multer forms and are keyed into the Mongo database. 

## Future Optimizations

* UI/UX Redesign for easier navigation.
  * Building out mobile friendly interface.
* Further refinement of database model and input fields through user testing.
* Managing multiple properties with multiple user access.
* Implement guest/unique demo account with session storage.

## Installation
You will need a Cloudinary and MongoDB account.

```bash
    1. Clone `https://github.com/intelagense/property-journal`
    2. Install `node` and run `npm install` inside the folder.
```
Put these values in a .env file in the config folder:
```JavaScript
PORT = "Your port number" // for local development
DB_STRING = "MongoDB connection string"
CLOUD_NAME = "Cloudinary Name"
API_KEY = "Cloudinary Key"
API_SECRET = "Cloudinary Secret"
```

Use this command in the root directory to start the server
```bash
npm run start
```
