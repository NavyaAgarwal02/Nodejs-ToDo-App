# To-do list - [view live](https://node-js-to-do-list-dnqhs2f41-navya-agarwal-projects.vercel.app/)

Project made for The Odin Project curriculum, in this project users can create, update, and delete tasks or projects.

## Credits

* No tasks message img by [unDraw.](https://undraw.co/)

## Features

1. Create, edit and delete tasks.
2. Organize tasks by projects.
3. Each task can have its own "details" section to store important information about it.
4. Users can label tasks by priority (represented with colors).
5. Tasks can be sorted by date (ascendant or descendant).
6. Users can delete projects and edit their names.
7. There are 2 special "projects" to sort today and this week's tasks.
8. Each project has its own "completed tasks" section, so the user can concentrate on the uncompleted tasks without remembering the ones already completed.
9. Tasks and projects are managed with `localStorage`.

## Specifications

1. Your ‘todos’ are going to be objects that you’ll want to dynamically create, which means either using factories or constructors/classes to generate them.
2. Brainstorm what kind of properties your todo-items are going to have. At a minimum they should have a title, description, dueDate and priority. You might also want to include notes or even a checklist.
3. Your todo list should have projects or separate lists of todos. When a user first opens the app, there should be some sort of ‘default’ project to which all of their todos are put. Users should be able to create new projects and choose which project their todos go into.
4. You should separate your application logic (i.e. creating new todos, setting todos as complete, changing todo priority etc.) from the DOM-related stuff, so keep all of those things in separate modules.
5. The look of the User Interface is up to you, but it should be able to do the following:
    5.1 view all projects
    5.2 view all todos in each project (probably just the title and duedate… perhaps changing color for different priorities)
    5.3 expand a single todo to see/edit its details
    5.4 delete a todo
6. Since you are probably already using webpack, adding external libraries from npm is a cinch! You might want to consider using the following useful library in your code:
    6.1 date-fns gives you a bunch of handy functions for formatting and manipulating dates and times.
7. We haven’t learned any techniques for actually storing our data anywhere, so when the user refreshes the page, all of their todos will disappear! You should add some persistence to this todo app using the Web Storage API. 

