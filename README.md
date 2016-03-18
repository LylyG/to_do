##To-Do jQuery App


### Normal Mode

For this project, you will be creating a To-do Manager.  This application will be a Rails app deployed on Heroku, and its purpose is for its user to be able to create as many to-dos as he or she wants, mark them as complete, and drag and drop them into the preferred order.

The following are requirements for this application:

* The data structure can be simple.  To-dos need to be stored in a table, but it is up to you whether you create an additional table for categorizing your to-dos (e.g. Family vs Work).
* To-dos have an optional due date.
* On the to-do list page, to-dos can be reordered via dragging and dropping.  This means that some notion of order must be stored in the data table.
* AJAX should be used to save the order immediately when the drag is completed.  The user should not have to hit a button to save the order.
* AJAX should be used to mark a to-do as complete without having to hit a save button or refresh the entire page.
* AJAX need not be used anywhere else.  For instance, you can have a standalone new to-do page that uses a normal request/response if you would like.
