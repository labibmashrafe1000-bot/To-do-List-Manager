# To-Do List Manager (CLI)

---

## Overview
This is a simple **Python command-line To-Do List Manager** that allows users to manage tasks directly from the terminal. Users can add tasks, mark tasks as completed, and view task status in an interactive menu-driven system.

The project demonstrates core Python programming concepts and basic input validation for a more stable user experience.

---

## Features
- Add new tasks
- Mark tasks as completed
- View all tasks with status (Pending / Done)
- Input validation for task selection
- Continuous menu loop until exit

---

## How to Run
1. Open `todo_list_manager.py` in a Python environment that supports input and print (e.g., Pyto, Carnets, VS Code, or any desktop Python IDE).
2. Run the script:

```bash
python todo_list_manager.py
```
## Example Interaction                
```
1. Add task
2. Mark task done
3. View tasks
4. Exit
Enter choice: 1
Enter task name: Study Python
Task 'Study Python' added!

1. Add task
2. Mark task done
3. View tasks
4. Exit
Enter choice: 3
1. Study Python - Pending

1. Add task
2. Mark task done
3. View tasks
4. Exit
Enter choice: 2
1. Study Python - Pending
Enter task number to mark done: 1
Task 'Study Python' marked as done!

1. Add task
2. Mark task done
3. View tasks
4. Exit
Enter choice: 3
1. Study Python - Done
```
## Skills Demonstrated                  
   - Python fundamentals (lists, dictionaries, loops, conditionals)
   - Menu-driven CLI application design
   - User input handling and validation
   - Exception handling using try / except
   - Dynamic data management

## License                            
     This project is licensed under the MIT License
