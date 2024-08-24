# ✅ Todo CLI Application: Master Your Tasks, One Command at a Time! 🖥️

Welcome to the Todo CLI application, your new best friend for keeping track of all those pesky tasks that life throws at you. Whether you're planning world domination or just trying to remember to buy milk, this app's got your back! 💪

## 🎯 Use Cases: What Can You Do With This App? 🤔

- **Create a todo list** 📝: Got a bunch of things to do? Create a list to keep them all in one place.
- **Show all the todo lists** 👀: Can’t remember how many lists you’ve started? No worries—this command’s got you covered.
- **Add, edit, delete, mark as complete/incomplete** ✍️: Manage your tasks like a boss. Add new items, update them, cross them off, or bring them back from the dead.
- **Show all the todo items in a particular list** 📋: Focus in on a specific list and see everything that needs doing. One list at a time, people!

## 🛠️ Commands to Use the CLI App: Your Toolbox 🧰

Here’s how you get things done with a few simple commands. Pro tip: You’ll feel like a coding wizard, even if you're just making a grocery list. 🧙‍♂️

### 🗒️ List Commands (Prefix: `list`)
- **`list show`**: Display all the todo lists you’ve created. Because it's nice to see the fruits of your organizational labor. 🌱
- **`list create list_name`**: Create a new list with `list_name`. It's like giving birth to a brand-new universe of tasks! 🌌
- **`list use list_name`**: Select a particular todo list to work on. Think of it as entering a new dimension of productivity. 🚪

### 📝 Todo Commands (Prefix: `todo`)
- **`todo add todo_title`**: Add a todo item to the selected list. The first step to conquering the world—or just your weekend chores. 🌍
- **`todo all`**: Show all the todo items in the selected list. Like laying all your cards on the table. ♠️♥️
- **`todo edit item_id new_title`**: Edit the todo item with the ID `item_id` and give it a fresh new title. Sometimes even tasks need a makeover! 💅
- **`todo remove item_id`**: Remove the todo item with the ID `item_id`. Out with the old, in with the new. 🗑️
- **`todo complete item_id`**: Mark the todo item with the ID `item_id` as complete. Crossing off tasks never felt so satisfying. ✔️
- **`todo incomplete item_id`**: Mark the todo item with the ID `item_id` as incomplete. Oops, maybe you weren’t done with that one after all. 😅

### 🆘 Utility Commands
- **`help`**: Print all the commands available in this application. Because even pros need a little guidance sometimes. 🧭
- **`quit`**: Exit the application. Say goodbye... but only until next time! 👋

## 💾 Data Storage: Keeping Your Todos Safe & Sound 🗃️

All your lists and tasks are carefully stored in `lists.json`. It's like the vault where all your productivity secrets are kept. 🤫

### 🔐 `lists.json`
- Stores the list of todo lists as a dictionary. Imagine a neat little package where each todo list is safely tucked away.
- Each list is stored as a dictionary of todos—each with a `title` and a `created_at` timestamp. It’s like your very own time capsule of tasks! ⏳

---

So go ahead—get organized, stay on top of your game, and most importantly, have fun while you're at it! 🎉
