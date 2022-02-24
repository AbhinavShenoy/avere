# Avere
Avere is a website where users can view, create and review trekking routes. In order to review or create a route, you must have an account.

This project was created using Node.js, Express.js, MongoDB, Bootstrap, EJS.

Passport was used to handle authentication.

Mapbox was used to locate a campground.


## Features
* Users can create and remove treks.

* Users can review treks once and remove their review.

* User can't review his own trek.

* User profiles include information of the user.

* Added authentication and authorization.

* Added map feature to view location of a campground.

* Sort campgrounds on basis of price, date and reviews.

* Search campgrounds by name.

## Install

For running this project on your local machine:

- [Node.js](https://nodejs.org/en/download/) is required.

- Clone this repo.

- Then execute the following command on your terminal in the project directory:

> NOTE : You should be inside Avere directory 

```
$ npm i
```

- Now run seeds.js file to seed the database 

```
$ node seeds.js
```

- Now run index.js file to start the server

```
$ node index.js
```

> The front-end of show page is not good, so also feel free to contribute in this repo to make it more stylish or if you find any bug.