# Envirinmental_Variable
## Understanding Environment Variables and Infrastructure environment


In today's technological world, Environment Variable and Infrastructure Environment are two important concepts that often come to the fore when talking about code and its deployment.They play distinct roles in scripting and software development.
Infrastructure environment refers to all the settings where software applications are developed, tested and deployed while Environment variables are key value pairs used in codes or scripts to manage configuration values and control software behaviour dynamically.
If we have an application and the application needs to connect to a database to fetch financial data, however, the details of the database connection, like the URL, username and password differ between our development, Testing and Production environments. We can develop a shell script that can be resused accross the different environments that can dynamically fetch correct values and connect to those environments.
Hard coding values into scripts is considered as poor practice, therefore we aim for flexibility by allowing scipts to accept input dynamically. This is called Positional parameters in shell scripting. A capability that allows passing arguements to scripts in runtime and then places the arguement with the parameter inside the script.

