# Frontend interview task - TODO list

Create a TODO list application supporting simple CRUD (Create, Read, Update, Delete) operations. Each user should be able to see their list after launching the application (or start with an empty one after running the app for the first time). To reach this goal, you can use localStorage for storing information. Design is not provided, as we count on your creativity.

### Functional part

- User should always access their latest TODO list upon launching the application if one is available; otherwise, an empty list should be provided  
- User can update the list by adding a new item or removing the existing ones (supporting both clearing the list and deleting entries one by one)  
- User can edit existing entries by changing their status to `DONE/UNDONE` and/or renaming them
 - **Bonus:** User can sort the list using drag-and-drop

### Technical part

Project should be programmed using the following tools:

 - **Node LTS**
 - newest version of **React**
 - applied bundler (for example. **Webpack, Browserify**)
 - All app **routes should be handled** with proper tool (for example **react-router**, native functions of NextJS)
 - addition boilerplate of your choose (for example **NextJS, create-react-app, Vite**)
 - styling of your choose (preferred CSS in JS, for example **styled-components**)
 - **Extra:** **TypeScript**
 - **Extra:** **Express** with **middlewares** to handle server-side with error-handlings for routes

> Project should contain unit test files. We recommend using **Jest** with **Testing Library**

## CRUD

User list should handle all options listed below:

|       |method           |endpoint    |
|-------|-----------------|------------|
|Create |`POST/PUT`       |`/create`   |
|Read   |`GET`            |`/list/$id` |
|Update |`PUT/POST/PATCH` |`/update`   |
|Delete |`DELETE`         |`/delete`   |


# Publication

Finished project should be uploaded to a public repository on your private **GitHub** account. Project should have all needed files and instruction (README.md) how to launch it locally. 

> Application will be tested on all moder browsers, like Chrome, Safari, Firefox and also **IE11**, Edge
