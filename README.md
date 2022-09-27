# Todo app challenge

## The challenge

Create a ToDo application having a front-end and back-end part. It should save all necessary data into the PostgreSQL database.

## Table of contents

- [Database structure](#database-structure)
  - [Frontend Mentor challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Built with](#built-with)
- [Installing](#Installing)
- [Links](#Links)
- [Useful resources](#Useful-resources)

## Database structure:

- Create a database named "todo_app"
- Create a new table called “todos” that should contain the following columns (fields): id SERIAL, text TEXT, status TEXT (status should be active or completed);
- Connect the frontend application to the backend using HTTP requests;

---

## For the frontend, I am using the "Frontend Mentor - Todo app" challenge.

### Frontend Mentor - Todo app challenge:

[Frontend Mentor](https://www.frontendmentor.io)

Your challenge is to build out this todo app and get it looking as close to the design as possible.
You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.
Your users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Add new todos to the list
- Mark todos as complete
- Delete todos from the list
- Filter by all/active/complete todos
- Clear all completed todos
- Toggle light and dark mode
- **Bonus**: Drag and drop to reorder items on the list

---

## Screenshot

- 375px:

| Dark                                           | Light                                           |
| ---------------------------------------------- | ----------------------------------------------- |
| <img src="/375px-dark.JPG" width="200"> | <img src="/375px-light.JPG" width="200"> |

## ![1440px](/todogif.gif)

## Built with

- CSS
- React.js
- Node.js, Express.Js
- Postgres

## Installing 🔍

To install this application enter the following into your terminal:
For front-end (React):
```
npm install
npm start
```
For back-end:
```
npm init
npm i express pg cors
npm install -g nodemon
change starting point in package.json (replace "main": "index.js" with "main": "server.js")
```
.
---

## Links

- Solution URL(front-end): [https://teonazav.github.io/subrepo-client/]

## Useful resources

- (https://reactjs.org/docs/getting-started.html)
- [React Beautiful DnD](https://github.com/atlassian/react-beautiful-dnd) - This helped me for Drag and Drop Implementation.
- https://expressjs.com/en/guide/routing.html
