# StudentApp
MVCStudentAPp
Marcus Russell 12th July 2020
Assignment
.Net MVC Task
This project includes the ability to perform CRUD (create, read, update and delete) operations on two tables that are stored in an SQL database. The tables have been linked in such a way that when a user updates a student record by registering him/her on a course, the number of available slots on that course is decreased in the second table, while the number of students attending that course is incremented. When a student record is deleted from the database, the reverse happens – the course slots are increased and the number of students attending is decreased. 

Design Patterns
The business logic has been separated out from the front end into a different project, so as to give separation of concerns. You will notice there are two models for each table, one in the business logic project, and the other in the MVC project. All the SQL commands are placed in the DataLibrary project. When we are fetching the model from the database and bringing it into the MVC part to be displayed, we have to convert it into the MVC model first, which is compatible with the view. 

The banner at the top of the page provides links for all the SQL reports required in task 2. Each subtask in task 2 has its own sql string which is built out in the processor files in the DataLibrary project. 

The sign up link is used to register a new student.

Note: The banner can block the diplay a litte at the top if you are using a narrow screen.

