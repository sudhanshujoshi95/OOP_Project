# OOP_Project
Student Management System: Using Object Oriented Programming Language CPP

We can create the Student.
Enter all the Details of Students.
Once, Student Record has been Created, we can make it Display to the Screen.
We can Search the Student Record by the RollNo. that  we have assigned to the Particular Student.
We can Delete the Student record  by Entering the Specific RollNo. of that Student.

In the Program I have made the Class named Student, in which we have different variables like rollno, name of student,
and marks of student in different subjects.

I have made several functions: void getdata(), void showdata() const, void calculate(), int retrollno() const;

getdata() --> It will get the data Eneteres from the User.
showdata() --> It will show the Data of the Student entered by the user.
calculate() --> It will calculate the GRADE of Student based on the Percentage of Marks obtained by the Student.
retrollno() --> It will retrive the rollno.

There are More Functions which We have made, that will Save the data Entered by the user to the File by using the File Streams Library's Function.
void create_student(): here we have used ofstream, that will write to the file and then read thst content of the file.
void display_sp(int): here we have used ifstream which will display particular record of the student with specific rollno.
void display_all(): display all records using ifstream.
void delete_student(int): delete particular record of the student with specific rollno.

There are many New things Which I Learned while making this Project, like the usage of cin.ignore(), cin.getline().
Some important and frequently used functions of FileStreams: 

ofstreaam();
ifstream();
.open();
.close();
.write();
.read();

Some Input-Output Stream Prefix, which I used for the First Time ever: 
ios::in -->	This ios prefix is used to open a file to read input from the user.
ios::out --> This ios prefix is used to open a file to write the output from the user.
ios::app --> This ios prefix is used to open a file and append it to the end.
ios::binary --> This ios prefix is used to treat the given file as a binary format.

This is One of those Projects, from which I have Learned many new and interesting things of C++.
I have Learned the Concept of "File Handling" which is very important and useful in making such Projects.
As C++ is Object-Oriented Programming Language, it makes the Solution of the Problem much more easier by breaking it to the objects and classes.


