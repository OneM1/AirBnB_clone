README FILE :

Description of project: 
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
create the first abstracted storage engine of the project: File storage.
create all unittests to validate all our classes and storage engine


description of the command interpreter:

a command interpreter , first step towards building  first full web application: the AirBnB clone.
the Goal of this Command interpreter is to be able to to manage objects of the projec, more specifically:

--Create a new object (ex: a new User or a new Place)
--Retrieve an object from a file, a database etc…
--Do operations on objects (count, compute stats, etc…)
--Update attributes of an object
--Destroy an object

How to start it:

--To start the command interpreter, execute the `console.py` script in your terminal.

How to use it :

How to Use
Once the shell is running, you can enter commands to perform various operations on AirBnB objects. Here are some example commands:

--help: Display help information about available commands.
--create <object>: Create a new instance of the specified object.
--show <object> <id>: Show details of a specific object.
--update <object> <id> <attribute> <value>: Update attributes of an object.
--destroy <object> <id>: Delete an object.
--all [<object>]: List all objects or objects of a specific type.

Examples :
`
In interactive Mode:
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$

In Non-Interactive Mode:

$ echo "help" | ./console.py
(hbnb)`
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$



