**To-Do List Bot for Windows Terminal**
This is a simple to-do list bot for the Windows Terminal, created using PowerShell scripting. The bot allows you to manage your tasks by adding, removing, and clearing items from your to-do list.

**Getting Started**
Open the Windows Terminal.
Create a new PowerShell script file with a .ps1 extension, such as todo.ps1.
Open the script file in a text editor and copy the code from the todo.ps1 file in this repository.
Save the file.
Usage
Open the Windows Terminal and navigate to the directory where the todo.ps1 file is saved.
Run the script by entering the following command: .\todo.ps1.
The bot will prompt you to enter a command. Available commands are:
show: Displays the current to-do list.
add: Adds an item to the to-do list.
remove: Removes an item from the to-do list.
clear: Clears the entire to-do list.
exit: Exits the bot.

Follow the on-screen instructions to interact with the bot and manage your tasks.

```
Enter a command (show/add/remove/clear/exit): show
No items in the to-do list.

Enter a command (show/add/remove/clear/exit): add
Enter the item to add: Buy groceries
Item added to the to-do list.

Enter a command (show/add/remove/clear/exit): add
Enter the item to add: Pay bills
Item added to the to-do list.

Enter a command (show/add/remove/clear/exit): show
To-Do List:
1. Buy groceries
2. Pay bills

Enter a command (show/add/remove/clear/exit): remove
Enter the item number to remove: 1
Item removed from the to-do list.

Enter a command (show/add/remove/clear/exit): show
To-Do List:
1. Pay bills

Enter a command (show/add/remove/clear/exit): clear
To-do list cleared.

Enter a command (show/add/remove/clear/exit): show
No items in the to-do list.

Enter a command (show/add/remove/clear/exit): exit
Goodbye!
```

**Customization**
You can customize and expand the script to add more functionality or modify the behavior of the bot. Feel free to adapt the code to fit your specific needs.
