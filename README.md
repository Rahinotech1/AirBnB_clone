0x00. AirBnB clone - The console

The console is the first segment of the AirBnB project at Holberton School that will collectively cover fundamental concepts of higher level programming. The goal of AirBnB project is to eventually deploy our server a simple copy of the AirBnB Website(HBnB). A command interpreter is created in this segment to manage objects for the AirBnB(HBnB) website.

🏃 Getting Started
 
 Ubuntu 14.04 LTS - Operating system reqd.
 
 GCC 4.8.4 - Compiler used
 
 ⚠️ Prerequisites
 
 Must have git installed

Must have repository cloned

Must have python installed

$ sudo apt-get install git

$ sudo apt-get install python3-pep8

To run the command interpreter:

$ ./console.py

Example

Interactive mode:

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  create  destroy  help  quit  show  update

(hbnb)
(hbnb) help EOF
EOF command to exit the program
(hbnb)
(hbnb) help all
Prints list of strings of all instances, regardless of class
(hbnb)
(hbnb) help create
Create command to create and store objects
(hbnb)
(hbnb) help destroy
Destroy command to delete an instance
(hbnb)
(hbnb) help help
List available commands with "help" or detailed help with "help cmd".
(hbnb)
(hbnb) help quit
Quit command to exit the program
(hbnb)
(hbnb) help show
Show command to print string representation of an instance
(hbnb)
(hbnb) help update
Update instance based on cls name & id by adding or updating attr
(hbnb) 
(hbnb)
(hbnb) quit
$
Non-interactive mode

$ echo "help" | ./console.py
(hbnb)


Documented commands (type help <topic>):
========================================
EOF  all  create  destroy  help  quit  show  update
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  all  create  destroy  help  quit  show  update
(hbnb) 
$
