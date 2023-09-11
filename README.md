### Airbnb Clone Project

### Description

This is the first step towards building our first full web application: the AirBnB clone. This first step is very important because we will use what we build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help us to:

    put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of our future instances
    create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
    create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
    create the first abstracted storage engine of the project: File storage.
    create all unittests to validate all our classes and storage engine

### Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

    How to create a Python package
    How to create a command interpreter in Python using the cmd module
    What is Unit testing and how to implement it in a large project
    How to serialize and deserialize a Class
    How to write and read a JSON file
    How to manage datetime
    What is an UUID
    What is *args and how to use it
    What is **kwargs and how to use it
    How to handle named arguments in a function

### Requirements

Python Scripts
Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 14.04 LTS using python3 (version 3.4.3)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the PEP 8 style (version 1.7 or more)
All your files must be executable
The length of your files will be tested using wc
All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')