# Project Objectives<br><br>

AirBnB_Clone (Part 1 of 4)<br><br>

The goal of the project is to deploy a simple copy of the AirBnB website.<br>

All the features won't be implemented; only enough to cover all fundamental concepts of the higher level programming track. The application will be built step by step. Each step will link to a concept. The first step is:<b><br>

The console<br>

* create your data model<br>
* manage (create, update, destroy, etc) objects via a console / command interpreter<br>
* store and persist objects to a file (JSON file)<br>

The first piece is to manipulate a powerful storage system. This storage engine will give us an abstraction between “My object” and “How they are stored and persisted”. This means: from your console code (the command interpreter itself) and from the front-end and RestAPI you will build later, you won’t have to pay attention (take care) of how your objects are stored. This abstraction will also allow you to change the type of storage easily without updating all of your codebase.The console will be a tool to validate this storage engine

