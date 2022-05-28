# CS569 Workshop 01
* Create an Angular application which shows two buttons on top to switch the following components: **List of Todos, Add new Todo**.  
* Each Todo item has the following structure: `{ id: uuid.v4(), text: string, done: boolean }` which should be declared as an interface.  When you add a new Todo item, you only need to read the `text` property, generate `id`, and mark `done: false` by default, and switch to the `List of Todos` component.
* **Custom Directive**: When users double-click on the Todo item, it toggles `done` property. Todos that are done are marked with line-through.  
* **Custom Pipe**: Todo's text is displayed with a limit of 50 chars, three dots must be added to the end of the string if it was longer than 50 chars.

*Note: Please submit your code before 11:00 AM*
