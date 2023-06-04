
# 📖 NatureTours

This project is about building a website for reserving nature-tours.

## 🛠 Built With

* [Express](https://expressjs.com/) - The node.js framework used
* [MongoDB](https://www.mongodb.com/docs/) - The database used
* [Mongoose](https://mongoosejs.com/docs/documents.html) - The database framework used

## 💻 Getting Started
To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

* Node.js

  https://nodejs.org/en/download

* MongoDB

  https://www.mongodb.com/try/download/community

* Postman

  https://www.postman.com/downloads/

### Setup

1) Clone this repository to your desired folder.
```
git clone https://github.com/sjjdfrz/NatureTours.git
```

2) Create **config.env** file.

3) Copy content of **config-example.env** file and paste in **config.env** file.
4) Fill variables with your own data.


### Install
Run this command to install dependencies:
```
npm install
```

### Usage

To run the server, execute this command:
```
npm start
```

After that import **Natours.postman_collection.json** file in postman and do http requests.

for this routes you must login as admin or lead-guide role:
```
  * http://127.0.0.1:3000/api/v1/tours/{ID} [DELETE]
  
```

for this routes you must just login:

```
  * http://127.0.0.1:3000/api/v1/tours/ [GET]
  
```

## Concepts:

* Authentication, Authorization and Security (with JWT Token)
* CRUD operations
* Error handling
* Data Modelling
* Relationship
* Filtering
* Sorting
* Pagination
* Aggregation Pipeline
* Middlewares
* Data Validation
* MVC Architecture
* Routing
* Upload Images
* Using MongoDB with Mongoose
* Server-Side Rendering with Pug Templates
* etc