### Define CRUD.

CRUD is a list of functions that should be able to execute on data within your databases through your application. It stands for:

- Create
- Read
- Update
- Destroy
### Why do we use set method_override: true?

To enable our forms within the web application to use methods outside of get and post.

### Explain the difference between value and name in this line: `<input type='text' name='task[title]' value="<%= @task.title %>"/>`.

The name is the label that the inputted data will carry once the form is submitted. The value is the value displayed in the form by default when the user loads it.

### What are params? Where do they come from?

Params are a series of arguments from the HTTP request. They are generated from both form submissions, and any elements that are denoted as a named parameter or wildcard in a route.

### Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?

We need a route to serve the page that allows the user to input the information that will be used to generate or edit the task, as well as a route that allows for the submission of that information to the server to handle the actual gemeration or updating of the task.
