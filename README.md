AirBnB Clone - The Console

File Descriptions
console.py - the console contains the entry point of the command interpreter. List of commands this console current supports:

EOF - exits console
quit - exits console
<emptyline> - overwrites default emptyline method and does nothing
create - Creates a new instance ofBaseModel, saves it (to the JSON file) and prints the id
destroy - Deletes an instance based on the class name and id (save the change into the JSON file).
show - Prints the string representation of an instance based on the class name and id.
all - Prints all string representation of all instances based or not on the class name.
update - Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file).

Classes inherited from Base Model:

amenity.py
city.py
place.py
review.py
state.py
user.py


