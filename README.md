# Todo CLI application

# Use cases 
- Create a todo list
- show all the todo list 
- add, edit, delete, mark as complete, incomplete etc
- show all the todo items in a particular items

# Commands to use the CLI app

=> prefixes for the commands: todo, list
- list show => show all the todo list we have created
- list create list_name => create a list with list_name
- list use list_name => select a particular todo item
- todo add todo_title => add a todo item it the list
- todo all => show all the todo's in the selected list
- todo edit item_id new_title => edit the item with id = item_id
- todo remove item_id => remove the item with the id = item_id
- todo complete item_id => marks the todo item with the id = item_id as complete
- todo incomplete item_id => marks the todo item with the id = item_id as incomplete

- help =>print all the commands we will be using in this application
- quit =>exit the application

## Data Storage

### lists.json
- stores the list of todo lists 

- store it as dict of todo(dict => title and created_at)