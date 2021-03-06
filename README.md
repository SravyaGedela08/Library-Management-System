
# Library Management System

Object-oriented programming principles are used in the C++ language to construct this library management system. This solution runs on a command-line interface and asks the user for input to display the results for the selected choice.

#### Execution

-> The user can execute by typing ``` g++ lms.cpp ``` in terminal inside the directory the file is present. This will compile the code.

-> Next, user can run the executable file by typing ``` ./a.out ``` in the terminal.

-> Furthur the user can go through the functionalities as listed at different levels.

The first screen shown would be:

```
  Welcome to IITH Library

1. Login with credentials
2. Exit
```

The user can choose the option just by typing ``` 1 ``` or ``` 2 ``` in terminal and hitting enter key.

Likewise, if user chooses ``` 1 ``` then furthur he gets:
```
Please enter your credentials to login.
enter your id:
```
Once the credentials are given, it will prompt to ask for password followed by a dashborad type in the terminal according to the role of the user (professor, student or librarian).

For example, this is the one for a professor listing out the functionalities he/she can perform:
```
Welcome Z
Select an option -
1. See all books
2. list of the books issued by you
3. check availability of any book
4. calculate fine for any issued book
5. clear fine amount
6. Issue a book
7. Return a book
8. Reset your password
9. Logout
|
```
Functionalities that ``` professor ``` can perform: see all the books, see list of books she/he has,check if book is available for issue or not, issue infinite number of books for 60 days with fine 5 rupees/day after due date, clear fine amout for any book, return a book with no dues and reset his/her password.

The same will be for ``` student ``` with issue at max 5 booksfor 30 days and fine 2 rupees/day after due date.

Following is the dasboard for ``` libraran ``` listing out the functionalities he/she can perform:

```
Select an option -
1. See all books
2. list of users
3. modify book database
4. modify user database
5. get issued book list by any user
6. Details of any book
7. Reset your Password
8. exit
|
```

``` libraran ``` can add/update/delete user or book by modifying the respective database, can get list down all books/users, can check which book is issued to which user along with its issue and due date, can check list of books issued to any user and reset their password.

#### Everytime the option is chosen by typing the repective option number and hitting enter, it will direct to furthur options the user has or can perform.

The database of user contains the details as-

``` user id,user password,user role ```

The database of book contains the details as-

``` Book Title,Book Author,Book ISBN,Book Publication,Avability,Id of user issued,issued date (in yyyymmdd) ```

While adding new User, his/her password is set to ``` iith ``` by default which can be furthur changed by respective user upon log and enter this password.

While adding new Book, its avaibility is set to ``` yes ``` by default as it is yet to be issued with issued date and id set to ``` na ```.