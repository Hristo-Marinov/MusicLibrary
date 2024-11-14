# Music Library Web App

The SPA **"Music Library"** is an app for creating a catalog of albums.

- **Technologies:** JavaScript, HTML, CSS, Node.js, Express.js, Mocha, Chai

## Pages and Permissions

### All users 🌐
- **Home** `/home`
- **Dashboard** `/dashboard`
- **Details** `/details/:id`
- **Login** `/login`
- **Register** `/register`

### Authenticated users 🔒
- **Dashboard** `/dashboard`
- **Add Album** `/create`
  - Fields: Singer/Band, Album, Image URL, Release Date, Label, Sales
- **Album Details** `/details/:id`
- **Edit Album** `/edit/:id` (only if user is owner)
  - Fields: Singer/Band, Album, Image URL, Release Date, Label, Sales
- **Delete Album** `/delete/:id` (only if user is owner)

## How to Start the Application?

> ❗ First you must **install all dependencies** included in the `package.json` file by typing `npm install` in a terminal. Then you must **serve the app** by typing `ng serve` in a terminal. After that, Music Library could be accessed on [http://localhost:3000](http://localhost:3000) URL.

![Terminal Installation Screenshot](path/to/installation-screenshot.png)
