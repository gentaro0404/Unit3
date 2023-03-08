# Unit 3 Project: Japanese Vocab Revision App

## Criteria A: Planning

## Problem definition(Client identification)

My client, Daiichiro, is a student of ISAK. He loves music very much and often listens to music subscription services. And one of the features in the subscription service is that you can register your favorite songs. However, although the favorite songs feature allows you to make a list of your favorite songs, it is difficult to create playlists by genre or by mood you want to listen to. For this reason, we need an application that allows us to create new lists of our favorite songs and listen to them by category. Compared to the analog method of writing in a notebook, the digital method is more efficient because the necessary data is saved each time, and the risk of loss is reduced. Also, with analog, it is easy to write down data, but very labor intensive to correct it. Also, sorting through a list of favorite songs is time-consuming. In contrast, digital data can be added, deleted, and rearranged in a snap. The application also allows you to enter information such as when the song was added, the author, the year it was released, and a link to the song's subscription application.
and log it!
## Proposed Solution

### Design Statement

To meet the needs of my client, Daiichiro, I propose to create an application that will allow him to manage and organize his favorite songs. The application would allow him to create customized playlists based on his genre and mood, and to enter information such as the date the song was added, its author, year of release, and links to subscription services. The proposed solution is designed using Python as the primary programming language, KivyMD for the graphical user interface (GUI), and SQLAlchemy for database management.

### System Overview

The application will be developed in PyCharm version 2022.3.2 (Professional Edition) and will use the macOS Ventura version 13.0.1 operating system on a 2021 MacBook Air M1. It will use Python as the primary programming language and will employ KivyMD to create a user-friendly graphical interface. SQLAlchemy will be used to manipulate and manage the application's database.

### Software Justification

Python

Python will be used as the primary programming language for several reasons. Firstly, Python is a high-level, interpreted programming language with a simple syntax that is easy to understand, making it an excellent choice for beginners. Additionally, Python is one of the fastest-growing programming languages, with a vast online community and a plethora of resources available to aid in its development<sup>[[1]](https://www.datacamp.com/blog/top-programming-languages-for-data-scientists-in-2022)</sup>. Secondly, Python is a language that I am most comfortable coding in, and its object-oriented programming framework is modular and flexible, making it ideal for this project<sup>[[2]](https://www.educba.com/advantages-of-oop/)</sup>.

KivyMD

KivyMD will be used to create the graphical user interface for the application. It is an open-source library that can create beautiful and user-friendly graphical user interfaces. The GUI is essential in enabling the user to interact with the application and perform tasks such as adding, editing, and deleting songs, creating playlists, and sorting songs based on different categories.<sup>[[3]](https://kivy.org/)</sup>

SQLAlchemy

SQLAlchemy will be used to manipulate the database for the following reasons. Firstly, it is a Python SQL toolkit and Object Relational Mapper that provides developers with the full power and flexibility of SQL"<sup>[[4]](https://www.sqlalchemy.org/)</sup>.. As a result, I can take advantage of the SQL programming language, which is commonly used for managing databases<sup>[[5](https://www.w3schools.com/sql/sql_intro.asp)</sup>. Secondly, SQLAlchemy is an ORM, which allows me to manipulate and query data from the database using Python, my native programming language. This is beneficial since it eliminates the need to learn SQL, making development faster and more efficient<sup>[[6]](https://talentopia.global/back-end/orm-vs-plain-sql-which-should-you-choose-and-when)</sup>.

In conclusion, the proposed solution will address Daiichiro's need for a music management application that is more efficient than traditional analog methods. By utilizing Python, KivyMD, and SQLAlchemy, the application will be able to provide a user-friendly interface while allowing the user to organize their favorite songs easily.


**Design statement**  



[^1]: Python Geeks. “Advantages of Python: Disadvantages of Python.” Python Geeks, 26 June 2021, https://pythongeeks.org/advantages-disadvantages-of-python/.



## Success Criteria

1. The application will have login,logout and register system.
2. The application allows the user to enter all attributes (song title, release date, artist name, album name, genre,song link), which are stored in a database through an interface.
3.  The application allows users to search and find songs by all attributes (song title, release date, artist name, album name, genre,song link).
4.  The login information, such as the username, email and password, will be secured and the password will be encrypted through a hash.
5.  The registration page will allow additional users to gain access to use the application.
6.  The application is a GUI and displays a login page, registration page, home page, search page, additional logs, and a list of songs.
# Criteria B: Design

## System Diagram

*Later

**Fig.1** 

## Data Storage



## Wireframe



## Record of Tasks

| Task No | Planned Action                                   | Planned Outcome                                          | Time estimate | Target completion date | Criterion |
| ------- | ------------------------------------------------ | -------------------------------------------------------- | ------------- | ---------------------- | --------- |
| 1       | First Meeting with client               | Start collecting the context of the problem              | 6min          | Feb 7                  | A         |
| 2       |  Defining problem and proposed solution | Start on refining client's requirements and tools needed | 2hr           | Feb 13                 | A         |
| 3      | Initializing codebase                    | To have the base environment of program ready for coding | 1hr           | Feb 14                | C         |
|     | Create login page                        | Program the kivymd and python files for the GUI and functionaliy of the login page.    | 1hr  | feb 14. | B |
|    | Create regisration page.                    | Program the kivymd and python files for the GUI and functionality of the registration page	| 1hr | feb 14 |  B |
|    |  Create wireframe diagram                  | Design the wireframe diagram of the application     | 1hr30mis.     |  Feb 15 |  C  |
|    | Crate system diagram                       | Design the system diagram of the application |  1hr. | Feb 17. | A |
|    | Create ER table and diagram                | Design the ER table and diagram for the application.  |  1hr30mis  | Feb 19  |  A |  
|    | 
## Flow Diagrams

### MVP Program

*Fig.2* **Flow diagram for the MVP program.**

### Main Program

*Fig.3 **Flow diagram for the main program.**

## Test Plan

| Type    | Input | Process | Anticipated Outcome |
| ------- | ----- | ------- | ------------------- |
| *Insert |       |         |                     |
|         |       |         |                     |

# Criteria C: Development

## Existing Tools

| Software/Development Tools | Coding Structure Tools  | Libraries  |
| -------------------------- | ----------------------- | ---------- |
| PyCharm                    | OOP Structures(Classes) | Kivymd.app |
| Python                     | SQL requests            | Passlib    |
| SQLite                     | Databases               | sqlalchemy |
| KivyMD                     | Encryption              |            |
|                            | For Loops               |            |
|                            | If-then-else statements |            |

## List of techniques used

1. 

## Computational Thinking

#### Decomposition

In computational thinking, decomposition refers to breaking a complex problem or system into parts that are easier to conceive,
understand, program, and maintain.

#### Pattern recognition, generalization and abstraction



#### Algorithms



## Development

#### OOP

#### MVP - Minimum Viable Product

In order to validate our concept of creation, we created a MVP as a prototype to make sure our concept is reliable and
achievable. 

## Criteria D: Functionality

### DEvelopment of User interface Using KivyMD

### Screen Manager
```py
ScreenManager:
    LoginScreen:
        name: "LoginScreen"
    SignupScreen:
        name: "SignupScreen"
    HomeScreen:
        name :"HomeScreen"
    SearchScreen:
        name :"SearchScreen"
    AddScreen:
        name :"AddScreen"
    TableScreen:
        name :"TableScreen"
```
My client has created a list of his favorite songs and his goal is to be able to listen to those songs through a URL from that list. Therefore, in developing the user interface, GIU is the best fit for this need because it is easy and intuitive to use.

Kivycode above created the "LoginScreen,SignupScreen,HomeScreen,SearchScreen,AddScreen,TableScreen" screens for these applications. In addition, unique names and IDs were defined in the Screen Manager.

Each screen uses and defines a separate kivy code block that provides the layout and widgets for that screen. As an example, the "SearchScreen" contains a text input field from which you can search for each item. Also, in the "TableScreen," songs added by the user are displayed for each item. Then, by tapping the URL displayed there, the user can jump to that URL and listen to the song.

Defining each screen as a separate widget is possible with ScreenManager. And because it is possible to switch screens on the liverpool and treat each screen as a separate one. As an example, when a user logs in, he/she can switch from "LoginScreen" to "HomeScreen" by pressing a button. This structure of the GUI results in a very organized and intuitive interface that is easy to use for both users and developers.



## Demonstration Video

*To be done
