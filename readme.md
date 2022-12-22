Library Management System
What is Library Management System?
As the name suggest the Library Management System is a software which handles the entire data of library. It makes the work of librarian very easy instead of writing data in a notebook. In past the librarians were using notebooks to write the data of books along with students name who borrowed that book. So it was very difficult to keep track on each and every book.
If librarian want’s to search for a particular book then that task was very time consuming. So to make this task easy the programming languages were developed and C++ language is one of them.
Features of Library Management System Project in C++
We have created separate logins for students and the librarian, in which the librarian is password protected.
In this project, the librarian can add, update, delete and create books and can also assign the books to the students.
The students can also view the list of the books available in the entire library database.
The entire rights are given to the librarian to adding books, issuing books, and modify the book.
This project uses file handling to store the data of books in a project.
A Librarian can also be able to change the password.
Reissuing and returning the books are the main features of this project.
The student can also be able to see which student has already borrowed the book.
Modules of Library Management System
Add Book.
Modify Book.
Delete Book.
Search Book.
Issue Book.
Return Book.
 
Working of Project
Main Screen:
When you run the project from any compiler or directly clicking on the executable .exe file you’ll see the following screen shown in the picture.

We have displayed the menu of Student, Librarian and close the application. If you’re a student then your choice will be 1 and if you are a librarian then your choice will be 2.
Now we’ll discuss each and every menu in details.
1. Student
The student will not require additional sign in, he or she will be able to access the software directly.
When the student enter the choice as 1 then following screen will be appeared:

We have displayed the menu of Student, Librarian and close the application. If you’re a student then your choice will be 1 and if you are a librarian then your choice will be 2.
Now we’ll discuss each and every menu in details.
1. Student
The student will not require additional sign in, he or she will be able to access the software directly.
When the student enter the choice as 1 then following screen will be appeared:

1. View Booklist:
In this menu option all the students according to their branches will be able to view the books present in the database along with their details.
2. Search For a Book:
We have given access to the students to search for a particular book. The student can search book either by book name or by book id. Both the options are available in the project.
3. Go to Main Menu:
When the user has done the required operations and if he want to again move to the main menu, then pressing 3 as choice he’ll moved to the main menu.
4. Close Application:
By pressing the choice as 4 the application will be closed.
2. Librarian:
To access the features of the librarian menu, He will require to sign in using the password which is “learnprogramo“. We’ve also given the facility to change the password in the Librarian menu. Only Librarian has rights to change the password.
When the user press the choice as 2. then the software will ask you to enter the correct password as shown in the following image:

If the password is incorrect the application will show the error of wrong password. And if the password is correct then the librarian menu will be visible to the user where he or she can do the operations displayed in the menu.
The following menu will be visible to the Librarian:


1. View Booklist:
Same as students view booklist, librarians will also able to see the books available in the library database.
2. Search For a Book:
The Librarian can search book either by book name or by book id. Both the options are available in the project.
3. Modify/Add Book:
In this menu option Librarian can do three main operations i.e. Adding a Book, Deleting a Book and Modifying the existing Book.

As we are using the file handling methods in this project, Every time new file is generated to store the details of the books. i.e. Booksdata.txt.
4. Issue Book:
Due to this option The 70% of the work is been reduced. In this option Librarian can do the following operations:
Issue a Book.
View Issued Books.
He can also search the students who issued the books.
Librarian can also reissue the book to the same student.
Return the Book.

To store the student details the separate file name Student.txt is been created.

Summary:
In this way, we’ve created and executed the Library Management System Project in C++. 

