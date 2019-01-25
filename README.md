# login-system
An interface which allows users or an admin to log into a basic menu.


Currently the program is very basic: a user is simply able to view their account details and login history or change their password, while the admin can create users, remove users, and view the information of other users in the system. However, the code can be easily modified and added to in order to introduce new functions that may be needed for a specific task.

When the program is opened for the first time, it is assumed the administrator of the system is logging in to initialize the system, admin then sets their password

Whenever a user (or the admin) logs out, the program utlizes Serialization to save the data to an external file. This way, when the program is quit and opened up again, all the data remains, so one can safely quit the app without fear of losing data
