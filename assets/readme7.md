# Create To Do List Application with MongoDB

## Instructions

Create a to do list application using Node.js, Express and Express routes, and jQuery's AJAX method and then use MongoDB and Mongoose for persistant data storage. This way if the application exits, the to do list items still exist.

You will need to use Font Awesome for the icons. The font used is Roboto from Google Fonts. You will also need to include jQuery in your application.

You need to meet the following requirements:

1. Use array methods instead of for loops.

2. Make a GET route for getting all todo list items.

3. Make a POST route for adding a new todo list item.

4. Make a DELETE route for deleting a todo list item using the X button next to it.

5. Make a PUT route for updating a todo list item when it is checked or unchecked.

6. Modularize your routes by seperating your Express routes into a seperate route file.

7. No global variables other than functions and state (front-end).

8. Use a single render function to render items to the page (front-end).

9. Use AJAX (part of the jQuery library) to make GET, POST, PUT, and DELETE requests from the front-end.

10. Add a database so that the to do entries will be stored even if the server application is reset.

11. You must use a Mongo database hosted on Heroku using the mLab add-on.

12. You must use the Mongoose Node module to connect with the Mongo database.

13. The to do list items must be stored in Mongo and can not be stored in your Node application.

14. Deploy the final application to Heroku.
