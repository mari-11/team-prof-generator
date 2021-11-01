# Team-Profile-Generator
object oriented programming

## Description: 
 This is a software engineering team generator. The application will prompt the user for information about the employee to build html file for the team. The user can input any number of team members, and they may be a mix of manager, engineers and interns.  When the user has completed building the team, the application will create an HTML file that displays a nicely formatted team roster based on the information provided by the user.
 The Team Profile Generator is a command-line-input application run in Node that requests information from the user about members of an engineering team and generates an HTML file displaying that information. Before running the application the user must perform an npm install to install all required dependencies.

Upon launching the app, the user is asked to describe the first member of their team. The user enters the team member's name, selects that member's role from a list (options include "Engineer," "Intern," and "Manager), enters the member's ID (any string), enters the member's email address, and then must enter another piece of information that will differ depending on what role was selected. If "Engineer" was selected, the app asks the user for the team member's GitHub username; if "Intern" was selected, the member's school is requested; and if "Manager" was chosen, the user is prompted for the team member's phone number.

For "intern" you will need to submit:

name
id
email
school


For "manager" :

name
id
email
offce number


For "engineer" :

name
id
email
github
The github account name will be a clicklable link in the generated html team profile


# Technologies used
NPM module, jest, inquirer, javascript, node.js

## Screenshot
[![image.jpg](https://i.postimg.cc/Wz96s7FN/image.jpg)](https://postimg.cc/XBCy8dkm)
