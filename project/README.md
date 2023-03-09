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
| ChatGPT                           | For Loops               |            |
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

### OOP

#### Object Oriented Programming

The Apprication was constructed using Object-Oriented Programming (OOP) principles to improve its modularity, reliability, and maintainability. OOP is a programming paradigm that emphasizes the creation of objects, which are instances of classes that encapsulate both data and behavior. By using classes, the code is organized into reusable and modular components that can be easily extended or modified.

In this app, each component of the application, such as the GUI, database, and user inputs, is encapsulated in its own class. This allows for easier debugging and troubleshooting since each class can be tested independently of the others. Moreover, changes and updates to the application can be made without affecting other parts of the code.

Additionally, OOP allows for the use of abstraction and polymorphism, which make the code more flexible and adaptable. Abstraction refers to the ability to hide implementation details and focus on the essential features of an object, while polymorphism allows objects of different classes to be used interchangeably.

Overall, the use of OOP in the Vocabulary App improves its overall design, making it more organized, modular, and flexible. It also makes it easier for future developers to maintain and extend the application with new features.


```.py
class database_worker:
    def __init__(self, name):
        self.connection = sqlite3.connect(name)
        self.cursor = self.connection.cursor()

    def search(self, query):
        result = self.cursor.execute(query).fetchall()
        return result

    def run_save(self, query):
        self.cursor.execute(query)
        self.connection.commit()

    def close(self):
        self.connection.close()
```
In this way, each action is contained under a function for each screen class, making it very easy to understand.


#### ORM

Object-Relational Mapping (ORM) is a programming technique that allows developers to manipulate relational databases using an object-oriented programming paradigm. A relational database is a database that stores structured data organized in tables and columns. In traditional programming, developers need to write SQL code to interact with the database using SQL statements to retrieve, update, and delete records in the database. With an ORM, however, developers can interact with the database using an object-oriented approach; the ORM framework provides a layer of abstraction between the application and the database. This eliminates the need for developers to write SQL code to deal with the database.

The ORM framework maps database tables to application classes and columns to class properties. This allows developers to manipulate the database by simply manipulating the classes, without the need to write SQL code to interact with the database. For example, consider the following Python code.

```,py
SELECT *
FROM users
WHERE name = "Gentaro"
```
This is a normal SQL statement that can be executed in python through running a query with the sqlite3 library. This is a language with a low level of abstraction.


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

## General Application Screen for Kivy

### SignupScreen
```.py
<SignupScreen>:
     size: 500,500
        FitImage:
            source:"main_image.jpeg"
        MDCard:
            size_hint: .8, .9
            elevation: 2
            orientation: "vertical"
            pos_hint: {"center_x": .5, "center_y":.5}
            padding: dp(50)      
        
 ```
 
MDcard is a component of the KivyMD library and represents a rectangular card with rounded corners, within which other widgets can be placed. the MDcard is drawn as a percentage of the MDcard that is tightened on the screen, and also this MDcard is drawn perpendicular to the screen The MDcard is drawn perpendicular to the screen. It also depicts the spacing of this MDcard relative to the screen and what percentage of the center of the screen this MDcard will be located. This information is entered and drawn as a visual layout. This kivy code block was adopted as the basic configuration for each screen. All screens have the same setup and background screen.


### MDLabel
```.py
MDLabel:
            text: "WELCOME YOUR MUSIC"
            font_style: "H5"
            size_hint: 1, .1
            font_size:90
            halign: "center"
            pos_hint: {"center_x": .5, "center_y": .5}
```

The MDLabel is a customizable on-screen text label that is widely used in modern applications to convey important information to users. It is an essential UI element that serves as an indicator to guide the user and provide context to the content being displayed on the screen.

In this particular case, the MDLabel is being utilized as the title of the home page screen, making it the first thing the user sees when they enter the home screen. The label's role is to provide the user with a clear understanding of where they are within the application, which is crucial for a seamless user experience.

This MDLabel can be customized in terms of its text color, font, size, and style to align with the overall theme of the application. The label's flexibility makes it an essential component of any application, allowing developers to design visually appealing screens with a clear and concise message. Ultimately, the MDLabel serves as an essential tool for designers and developers alike to enhance the user's experience and create a successful application.

### MDFillRoundFlatIconButton
```.py
MDFillRoundFlatIconButton:
                icon: "music-circle-outline"
                text: "Add your songs"
                font_size: 30
                on_release: app.root.current = 'AddScreen'
                md_bg_color: "f6bd60"
                pos_hint: {"center_x": .5, "center_y": .5}
```


The KV code above shows the implementation of the MDFillRoundFlatIconButton, a multifunctional button often used in modern UI design to create visually appealing and user-friendly interfaces. The button is designed with a circular, flat icon and is often used for interactive elements that need to be quickly accessed, such as home screen buttons and navigation menus.

The MDFillRoundFlatIconButton provides a clean, professional aesthetic that is in line with client needs. The shape and style of this button provides a modern, sleek design that enhances the overall user experience. Additionally, the circular shape of the button adds a unique touch to the interface and helps distinguish it from other standard rectangular buttons.

This button is a popular choice among designers and developers because it can be easily customized to fit the design requirements of any application. MDFillRoundFlatIconButton can be adjusted to match the application's color scheme, text size, font style MDFillRoundFlatIconButton can be adjusted to match your application's color scheme, text size, and font style, resulting in a consistent and cohesive interface.



### MDRaisedButton
```.py
MDRaisedButton:
            id : addsongs
            text:"Add Songs"
            size_hint: 3,1
            md_bg_color: "#a8dadc"
            on_press:
                root.manager.current = "AddScreen"
                root.manager.transition.direction = "left"
```

MDRaisedButton is a rectangular button. It features a 3D-like visual effect and has a raised or slightly elevated appearance. It is often used for more important or attention-grabbing actions within an application. unlike the MDFillRoundFlatIconButton, the MDRaisedButton is not circular in shape and can be customized to include text or an icon.

Both buttons can be customized to meet the design requirements of the application, but which one to use depends on the specific use case and the desired look and feel of the interface. In general, MDFillRoundFlatIconButton is better suited for home screen buttons and navigation menus, while MDRaisedButton is better suited for actions that require a more prominent or attention-grabbing appearance.


### MDTextField
```.py
 MDTextField:
                id: search
                hint_text: "Search"
                size_hint: 1, .17
                required: True
```

MDTextField is a fundamental component of the modern user interface that allows users to enter information through the keyboard. This type of text field is an essential element of applications that require data entry by the user, such as account registration, data entry forms, and search boxes.

When programming MDTextFields, it is important to consider the possibility of user error during data entry. To address this issue, designers and developers can use helper text and error messages to guide users through the data entry process. As shown in the figure above, helper text is displayed to prompt the user to enter information if he or she forgets to do so. Additionally, if an error occurs during data entry, the error message is displayed in red to alert the user.

An important aspect of designing MDTextFields is the size hint property, which specifies the size of the text field. The size hint can be set to a specific value, such as "1,.17" to ensure that the text field is large enough for the user to enter information without problems. If the size hint is set to a value that is too small, the user may have difficulty entering text properly, leading to errors and frustration.


## Development of Application Using Python

### Database configuration

```.py
class database_worker:
    def __init__(self, name):
        self.connection = sqlite3.connect(name)
        self.cursor = self.connection.cursor()

    def search(self, query):
        result = self.cursor.execute(query).fetchall()
        return result

    def run_save(self, query):
        self.cursor.execute(query)
        self.connection.commit()

    def close(self):
        self.connection.close()
```
This code defines a Python class called database_worker. This class has a __init__ method that takes one argument, name, which specifies the name of the SQLite database. This method initializes a connection to the specified database in the connection attribute and a cursor object that can be used to execute SQL statements on the database in the cursor attribute.

The class also has a search method that takes one argument, a query, which is an SQL query to be executed on the database. This method executes the query using the cursor object and fetches all results using the fetchall method. The method then returns the results as a list of tuples.

The class also has a run_save method that takes one argument, a query, which is an SQL query to be executed on the database. This method executes the query using a cursor object and commits the changes to the database.

Finally, the class has a close method that closes the connection to the database.


### Registration System


#### Password Match Confirmation
```.py
    def try_register(self):
        uname = self.ids.uname.text
        email = self.ids.emails.text
        passwd = self.ids.passwd.text
        passwd2 = self.ids.passwd2.text
```
This code defines a method called try_register that is used to register a new user in a system. It retrieves the user's input for their desired username, email, password, and password confirmation from the corresponding text input widgets in the GUI using self.ids.

The input is stored in the variables uname, email, passwd, and passwd2, respectively. uname is short for username, email refers to the email address the user enters, passwd is short for password, and passwd2 is used to confirm that the user has entered the correct password.

After retrieving the input values, the method proceeds to validate the input by checking if the password and password confirmation fields match. The registration process cannot proceed if the passwords do not match.

This method is commonly used in user registration systems to capture user input and validate that the information entered is accurate before proceeding with account creation.

#### Insert user information into the database
```.py
        if passwd != passwd2:
            self.ids.passwd.error = True
            self.ids.passwd2.error = True
        else:
            hash = encrypt_password(passwd)
            db = database_worker("project3_db.db")
            query = f"INSERT into users (email, password, username) values('{email}','{hash}','{uname}')"
            db.run_save(query)
            db.close()
            print("Registration complete")
            self.parent.current = "LoginScreen"
```
When a user is trying to create a new account, this code validates the information entered and processes it to insert the user information into the database.

First, it checks if the passwords entered match. If it does not match, an error is displayed in the password entry field.

If it matches, the password is hashed and the new user information is inserted into the database. To do so, it generates an SQL query containing the user name, email address, and hashed password, and queries the database using the database_worker class. Then close the database connection.

Finally, it displays a message indicating that the new user was successfully created and returns to the login screen.

### Login System

#### passward reset
```.py
    def cancel(self):
        self.ids.passwd.text = ""
        self.ids.passwd2.text = ""
        self.parent.current = "LoginScreen"
```
This code provides the ability to reset the password on the user registration screen and return to the login screen. cancel method empties the text in the password entry field and changes the application's current screen to LoginScreen. This allows the user to re-enter the password and cancel the registration.


### Registration System

#### Pulling user information from the database
```.py
    def try_login(self):
        print("User trying to login")
        uname = self.ids.uname.text
        passwd = self.ids.passwd.text
        query = f"SELECT * from users WHERE username = '{uname}'"
        db = database_worker("project3_db.db")
        result = db.search(query=query)
        db.close()
        print(result)
 ```       

The code attempts to log in a user by checking if the username entered exists in the database and if the password entered matches the password stored in the database under that username.

#### User Credential Verification
```.py
        if len(result)==1:
            pass
            hashed = result[0][2]
            if check_password(user_password=passwd, Hashed_password=hashed):
                print("Login successful")
                self.parent.current = "HomeScreen"
```
The code checks whether the length of the result returned from the database is equal to 1, indicating that a user with the entered username exists in the database. If so, the hashed password associated with that user name is retrieved from the database and the "check_password" function is used to check whether the entered password matches the stored hashed password. If the password matches, the user is logged in and the screen switches to the home screen.


#### passward reset
```.py
    def cancel(self):
        self.ids.passwd.text = ""
        self.ids.passwd2.text = ""
        self.parent.current = "LoginScreen"
```
This code provides the ability to reset the password on the user registration screen and return to the login screen. cancel method empties the text in the password entry field and changes the application's current screen to LoginScreen. This allows the user to re-enter the password and cancel the registration.


### Adding System


```.py
    def Addsongs(self):
        song_title = self.ids.song_title.text
        release_date = self.ids.release_date.text
        artist_name = self.ids.artist_name.text
        genre = self.ids.genre.text
        song_link = self.ids.song_link.text
```
#### Variable Definitions
This code defines a function called "Addsongs" that extracts input data for a new song from various text input fields using their corresponding ids. The input data includes the song title, release date, artist name, genre, and song link. These variables are used to construct an SQL query for inserting the new song into a database table.


##### Insert Query
```.py 
    def Addsongs(self):
        song_title = self.ids.song_title.text
        release_date = self.ids.release_date.text
        artist_name = self.ids.artist_name.text
        genre = self.ids.genre.text
        song_link = self.ids.song_link.text

        db = database_worker("project3_db.db")
        query = f"INSERT into songs (song_title, release_date,artist_name,genre,song_link) values('{song_title}','{release_date}','{artist_name}','{genre}','{song_link}')"
        db.run_save(query)
        db.close()
        print("Song added")
```

This code inserts flight information provided by variables flight_number, destination, date, flight_schedule, terminal, gate_number, and status into a database table called "allflights" using an SQL query constructed using the query variable, executed using the run_save method of the database connection created with the database_worker function, and saved to the database file "unit3project.db". The close method is used to close the database connection after the query has been executed, and a message is printed to indicate that the flight has been added to the database.

### Table of songs 

#### Data Table

```.py
self.data_table = MDDataTable(
            size_hint=(0.9, 0.7),
            pos_hint={"center_x": 0.5, "center_y": 0.5},
            use_pagination=True,
            check=True,
            column_data=[
                ("ID", 50),
                ("Song title", 40),
                ("Release date", 40),
                ("Artist name", 40),
                ("Genre", 40),
                ("Song link", 160)
            ],
            row_data=[]
        )
        self.add_widget(self.data_table)
        self.data_table.bind(on_row_press=self.on_row_press)
        self.update()
```
This code is designed to display a table on the screen that contains data, with the aim of allowing the user to view and interact with the data in a clear and organized way. In order to provide the client with the ability to listen to a song from their own list of favorite songs, this code uses the "self.data_table.bind(on_row_press=self.on_row_press)" method to enable the user to click on a specific song URL displayed on the table, which will trigger the "on_row_press" function to execute and redirect the user to the corresponding URL. This functionality is essential for providing a smooth and seamless user experience and ensures that the client can easily navigate to the song they want to listen to from their list of favorite songs.



#### Press an item in a table
```.py
@staticmethod
    def on_row_press(table, row):
        print(f"Row was pressed. Data is: {row.text}")
        if row.text.find("http") == -1:
            temp = f"https://{row.text}"
        else:
            temp = row.text
        result = urlparse(temp)
        print(result)
        print(all([result.scheme, result.netloc, result.path]))
        if all([result.scheme, result.netloc, result.path]) is True:
            webbrowser.open(temp)
            print("reached")
        else:
            pass

    @staticmethod
    def on_check_press(table, current_row):
        print(f"Row {current_row} was checked")
```

This code defines methods for manipulating tables using Kivy, a Python GUI framework. Specifically, it defines the on_row_press method, which is called when a table row is selected, and the on_check_press method, which is called when a table row is checked.

The on_row_press method performs a specific operation on the table and row passed as arguments. This method retrieves the data for the selected row, checks to see if it is a URL, and if so, parses the URL to open it in a web browser and calls webbrowser.open. This method is declared as a static method, so it can be called directly without creating an instance of the class.

The on_check_press method performs specific processing on the table and current_row passed as arguments. This method retrieves information about the checked row and outputs a message to confirm that it has been selected. This method is also declared as a static method, so it can be called directly without creating an instance of the class.

### Deleting Table

```.py
    def delete(self):
        rows_checked = self.data_table.get_row_checks()
        print("Trying to delete")
        print(rows_checked)
        db = database_worker("project3_db.db")
        for r in rows_checked:
            id = r[0]
            query = f"delete from songs where id = {id}"
            db.run_save(query)
        db.close()
        self.update()
```
This code implements the function of deleting data from the database: the delete() method retrieves the data for the rows checked by the user and deletes those rows from the database. First, it uses the get_row_checks() method of the data_table object to obtain a list of checked rows. Then, using the IDs of the retrieved rows, we create an SQL query to delete the corresponding rows from the songs table and send it to the database using the database_worker class. Finally, the update() method is used to update the data and display the latest data.

Specifically, it stores the list of rows checked by the user in rows_checked. It then connects to the database and executes a delete query on each row in the rows_checked list using a for loop. Using the ID of the deleted row, the SQL query deletes the corresponding row in the songs table. To reflect the changes to the database, we close the database with the db.close() method and finally update the GUI data to the latest state using the self.update() method.

#### Delete from Database

```.py
 def delete_songs(self):
        checked = self.data_table.get_row_checks()
        Logger.info("Deleting vocabulary from database...")
        try:
            for row in checked:
                vocab_id = int(row[0])
                query = f"DELETE FROM songs WHERE id = {vocab_id}"
                db = database_worker("project3_db.db")
                db.run_save(query)
                db.close()
            self.update()
            deletedialog = MDDialog(
                title="Success",
                text="Song deleted successfully",
                size_hint=(0.8, 0.3),
                buttons=[
                    MDFlatButton(
                        text="OK",
                        on_press=lambda x: deletedialog.dismiss()
                    )
                ]
            )
            deletedialog.open()
        except Exception as e:
            Logger.error(f"Error deleting song: {e}")  
```
This program provides a function to remove from the database the songs selected by the user in the data table.

First, it uses the get_row_checks() function to identify the rows selected by the user and obtains a list of the rows selected in the data table. Then, a for loop is used to obtain the ID of the row for each selected row, and an SQL query is generated to remove the selected rows from the database.

The database operation is performed using the database_worker class. Then, after the deletion, the table is updated so that the deleted rows disappear from the data table. If the deletion is successful, a dialog box is displayed using the MDDialog widget to notify the user that the deletion was successful. If an error occurs, an error message is output to the log.

### SearchScreen
```.py
    def search_songs(self):
        search = self.ids.search.text
        db = database_worker("project3_db.db")
        query = "SELECT * from songs where song_title like '%"+search+"%' or artist_name like '%"+search+"%' or genre like '%"+search+"%'"
        result = db.search(query)
        db.close()
        self.data_table.update_row_data(None, result)
  ```
 This code defines a function called "search_songs" that extracts a search query string from a text input field using its corresponding id. The search query string is then used to construct an SQL query for selecting all songs from a database table that contain the search query string in the song title, artist name, or genre fields. The resulting data is fetched from the database using the "db.search" method and saved in the "result" variable. The database connection is then closed using the "db.close" method. Finally, the data table is updated using the "self.data_table.update_row_data(None, result)" method to display the filtered search results. This functionality enables the user to search for and view specific songs based on their song title, artist name, or genre, making it easier to navigate and manage a large database of songs.
 
 
## Demonstration Video

*To be done
