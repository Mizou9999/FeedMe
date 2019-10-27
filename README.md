<h1 align="center"> Feed Me Platform </h1>
# About the project
Create a platform that make a relation between the users and an external API by letting them contribute to the website with their own reviews and suggesting restaurant additions

# О проэкт

Создание платформы, обеспечивающей связь между пользователями и внешним API, позволяющую им вносить свой вклад в сайт с собственными отзывами и дополнять ресторанами.

## User Stories

- [x] As a user I can see all restaurants around my position
- [x] As a user I can read information about specefic restaurant just by clicking on the map marker
- [x] As a user I can add new restaurants to the map
- [x] As a user I can see the same list of the restaurants showed on the map in the left site of the App
- [x] As a user I can click on a button to show more informations about the restaurant clicked
- [x] As a user I can add a review and a rating about the restaurant clicked
- [x] As a user I can see the average restaurant rating based on real data
- [x] As a user I can select from a range slider to display X to Z stars to filter the restaurants displayed
- [x] As a user I can see my comment and rating after review submiting
- [x] As a user I can get back to the main page after submiting a review or clicking on a restaurant informations

# Getting started

Prepare the project,

- Clone this repository.
- `cd` into the directory where you have cloned this repository.
- Run `npm install`

# Entry Point

```
/src/app.js
```

# How to start the dev server?

To start the dev server with auto reload feature run this command,

```
npm run server
```

Then go to `http://localhost:9300/`. Each time you make some changes in the JS files in the `/src/` directory the dev server will first make a dev build and the reload the page in your web browser.

# How to make a `production` build?

To make a production build run this command,

```
npm run build
```

This will replace the old bundle with a new one in the `/dist` directory.

### Modify proxy

```
/webpack.config.js
```

Change `target` path

More info @ https://webpack.js.org/configuration/dev-server/#devserverproxy
