# AndroidStudio_Capstone

This application performs four differnt tasks to 

1. Run an activity
2. Bind a service
3. Broadcast a receiver
4. Content Managemenet

Fragments are used to define and execute each task and helping toencapsulate the logic and UI interface in one place.

RunActivity
This functionality create an activity to play a music either from a local storage or off an internet location.
The activity runs in the foreground in the main thread and so no other activity can run concurrently. The required permission to run the activity are declared in the the manifest file.

BindService
This functionality creates a service at startup that is bound to the system. Upon user request, the service returns the system time and is displayed on the screen. 
User has the option to unbind the service.

Broadcast Receiver:
This functionality sends intents about the health of the battery and received a broadcast on the status of the battery. 
It displays battery level, voltage, temperature, health, charging status, charging source, The functionality uses dynamic receivers to register the broacast with the Context.registerReceiver() method.


Content Managemenet
This functionality creates a database and a table to hold customer informaion of name, email and mobile number. It can do 4 tasks.
Add:
This task adds a new customer information to the database.
Update:
This task updates customer information in the database.
Delete:
This task removes customer information from database.
List:
This task lists all customer information saved on database.
