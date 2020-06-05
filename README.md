# Bird Sightings Full Stack App

Bird Sightings is a full stack application with an Node.js Express server and MongoDB database for the back end and a Vue.js JavaScript framework for the front end.


## Objectives
* Carry out paired programming
* Understand the data flow through a full stack app
* Demonstrate the ability to make a post request from a front end application and persist the date in a database

## The app performs the following
* Allows a user to submit a form for their bird sighting which is then persisted on a database
* The webpage displays a list of all saved bird sightings.
* Allows the user to delete a bird sighting


## Getting Started

These instructions should get you a copy of the project up and running on your local machine for development purposes.

### Server

Install server dependencies:

```
cd server
npm install
```

Seed the database:

```
npm run seeds
```

Run express:

```
npm run server:dev
```

### Client

```
cd ../client
npm install
npm run serve
```
