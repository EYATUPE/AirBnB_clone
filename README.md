AirBnB Clone - The Console

The console is the first segment of the AirBnB project at ALX that will collectively cover fundamental concepts of higher level programming. The goal of AirBnB project is to eventually deploy our server a simple copy of the AirBnB Website(HBnB). A command interpreter is created in this segment to manage objects for the AirBnB(HBnB) website.


Functionalities of this command interpreter:
Create a new object (ex: a new User or a new Place)
    * Retrieve an object from a file, a database etc...
    * Do operations on objects (count, compute stats, etc...)
    * Update attributes of an object
    * Destroy an object

Environment
This project is interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)

The command interpreter:
console.py - the console contains the entry point of the command interpreter. List of commands this console current supports:

  * EOF - exits console

  * quit - exits console

  * <emptyline> - overwrites default emptyline method and does nothing

  * Create - Creates a new instance ofBaseModel, saves it (to the JSON file) and prints the id

  * Destroy - Deletes an instance based on the class name and id (save the change into the JSON file).

  * Show - Prints the string representation of an instance based on the class name and id.

  * All - Prints all string representation of all instances based or not on the class name.
  * update - Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file).

1.)  models/ directory contains classes used for this project:
 base_model.py - The BaseModel class from which future classes will be derived

  * def __init__(self, *args, **kwargs) - Initialization of the base model
  * def __str__(self) - String representation of the BaseModel class
  * def save(self) - Updates the attribute updated_at with the current datetime
  * def to_dict(self) - returns a dictionary containing all keys/values of the instance

2.) Classes inherited from Base Model:
  * amenity.py
  * city.py
  * place.py
  * review.py
  * state.py
  * user.py


AUTHURS 
1.) EYATU PHILIP ESAMU <eyatuphilipesamu@gmail.com>
2.) WAISWA KENNETH <>
