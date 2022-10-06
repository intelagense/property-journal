# Property Journal
Keep a journal for your home. Users log in to enter pictures, details, and tags for everything they want to track in their home. 

**Link to project:** https://property-journal-production.up.railway.app/

![screenshot](/assets/propertyjournal.png)

## How It's Made:

**Tech used:** Mongoose, Express, Bootstrap, Node

* MVC architecture

## Future Optimizations

* UI/UX Redesign for easier navigation.
* Building out a mobile interface using React Native.
* Further refinement of database model and input fields through user testing.
* Sharing and managing multiple properties.


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