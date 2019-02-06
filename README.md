# Note-Taker---Node-and-Express-Servers

### Overview

In this activity you'll build a Node, Express, and MySQL powered note-taking application. The user will have the ability to create, read, and delete notes from a MySQL database.

You will use Express to handle routing and server HTML as well as JSON. MySQL to store notes, and jQuery for AJAX requests and handling other front-end logic.

* Check out these demo versions of the site:

* [Harder Version](https://note-taker-fsf.herokuapp.com/)
* The user can save, view, and delete notes without having to refresh or navigate to a different page to see the changes.
 
 * The backend for both these applications is _exactly_ the same. Whichever version of the application you choose to work on, complete the server-side code first and verify your API routes work properly with Postman.
 
 ### Instructions

1. Create the backend for the application first. Start by using the provided `schema.sql` and `seeds.sql` file create a database and seed some starter data.

2. Create a `server.js` file that starts a basic express server.

3. Require the `connection.js` file provided and add API routes for:

  * Retrieving all notes from the database and returning them to the user as JSON.

  * Saving a new note to the database using the data passed on `req.body`.

  * Deleting a note from the database using `req.params.id`.

4. Test that all your API routes work properly using Postman.

5. Add a `/` route for serving an `index.html` file (the welcome page).

6. Add a `/notes` route for serving a `notes.html` file (the page for viewing, saving, deleting notes).

7. Style the `index.html` page and add a description of the application.

8. Decide whether you'd like to attempt the easier or more difficult assignment. If you're unsure, attempt the easier version first.

9. Code the front-end logic for displaying the list of notes.

10. Code the front-end logic for submitting a new note.

11. Code the front-end logic for deleting a note from the database.

12. Deploy the assignment on Heroku using the [MySQLHerokuDeploymentProcess.md](../03-Supplemental/MySQLHerokuDeploymentProcess.md) guide.

### Minimum Requirements

Attempt to complete homework assignment as described in instructions. If unable to complete certain portions, please pseudocode these portions to describe what remains to be completed. Adding a README.md as well as adding this homework to your portfolio are required as well and more information can be found below.

- - -

### Hosting on Heroku

Now that we have a backend to our applications, we use Heroku for hosting. Please note that while **Heroku is free**, it will request credit card information if you have more than 5 applications at a time or are adding a database.

Please see [Heroku’s Account Verification Information](https://devcenter.heroku.com/articles/account-verification) for more details.

