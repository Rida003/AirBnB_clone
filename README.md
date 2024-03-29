## AirBnB clone - The console
![AirBnB clone - The console](https://i.imgur.com/xfKIjxR.png)
## Description
The name of this project is AirBnB clone. We will write all stages of the application ourselves. Briefly, we will manage everything from HTML/CSS templating, database storage, API, frontend integration... using the Python cmd module from the console. The first step of the project is to write this console...

### How to use command interpreter
The command interpreter is a tool to manage the whole application. It can be used to create, update, destroy, show and count objects. The command interpreter is used to manage the objects of the application:
- Create a new object
- Retrieve an object from a file, a database etc...
- Do operations on objects
- Update attributes of an object
- Destroy an object.

### How to start the console
The console is a command line interpreter. To start the console, you need to run the following command:
```sh
./console.py
```
### How to use the console
The console works in interactive mode and non-interactive mode. In interactive mode  the console displays a prompt and waits for the user to type a command. A command is a single line of text that the user types in the command line. Each command is composed of a command name and a list of arguments  all separated by a space. For non-interactive mode  the console can be used to execute a command from a file. The command interpreter can be executed in non-interactive mode by calling the command interpreter with a command file as an argument. The command interpreter will read the file and execute the commands inside it.

### Commands usage: 


| *Command*  | *Usage* |
| -------- | -------- |
|*create*  | ***create*** <class_name>|
|*show*    | ***show*** <class_name> <object_id> **;** <class_name>.***show***(<object_id>)()|
|*destroy* | ***destroy*** <class_name> <object_id **;** <class_name>.***destroy***(<object_id>)()|
| *all*    | **all** <class_name> **;** <class_name>.**all**()|
| *update* | ***update*** <class_name> <object_id> <attribute name> "<attribute value>" **;** <class name>.***update***(<object_id>, <attribute name>, <attribute value>) **;** <class name>.***update***(<object_id>, <dictionary representation>)|
| *help*   | ***help*** **;** ***help*** <command_name>|
| *quit*   | ***quit*** |
| *EOF*    | ***EOF*** **;** (ctrl + d)|

## AUTHORS✒️
---

* [Rida Essahi](https://github.com/Rida003)  - LinkedIn profile (https://www.linkedin.com/in/rida-e-75a574257/)

## Feel free to explore and contribute to the project!

