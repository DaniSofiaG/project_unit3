# project_unit3

![The Wonderful World of Japan’s Incredible Convenience Stores](https://user-images.githubusercontent.com/111941990/218233255-1c0c1ab4-c711-4ab8-b310-7a1c23530967.jpeg)

---
<img width="1101" alt="Screen Shot 2023-03-09 at 17 04 02" src="https://user-images.githubusercontent.com/111941990/223959239-731557bc-bb27-48c0-97d9-38f2f58d5b0e.png">

# Criteria A: Planning


## Problem definition
Meisa is the manager of a convenience store. Last year while doing the end of year report for the store in Decedmber she realized how tiering and disorganized was the process. It took her nearly 2 weeks to collect all the data she needed from excels document, receipts, memory and paper inverntories. Its also come to her attention that a lot of her staff struggles to put record the data properly because of the amount of different methods they have to learn and becuase of how tideous it is. This year she wants things to be different, that's why she's asked for a program that allows her to store and manage all the important data like product, supplier, aisles and staff information. She also has to be able to add or change data as the year goes on. The program has to be simple to use and choherent so that all staff is able to use it.



## Proposed Solution
To create the program, I will use Python and KivyMD to build a user interface that allows Meisa to manage the data for her store. I will use an object-oriented approach (OPP) to create classes for the various data entities like products, suppliers, aisles, and staff, and use methods within each class to manage the data.

I will use a SQL database to store and manage the data for the store. The database will be designed with MDDataTables for each of the data entities. I will use the SQLite database management system, which is simple and compatible with Python.

To create the user interface, I will use the KivyMD framework, which is built on top of Kivy and provides a set of ready-to-use GUI components and styles. I will design the user interface with a focus on simplicity and ease of use, ensuring that Meisa can quickly and easily access and manage the data she needs.

Throughout the development process, I will conduct regular testing and debugging to ensure the program is functional and free of errors. I will also conduct user testing with Meisa to gather feedback, incorporating her suggestions and addressing any issues that arise. To ensure the program remains relevant and useful throughout the year, I will design it to allow Meisa to add or change data as needed. This will involve designing forms and input fields that allow Meisa to input new data and update existing data.

Overall, this solution will provide Meisa with an efficient, user-friendly program to manage the data for her convenience store. The use of Python, KivyMD, and a SQL database will ensure the program is fast, reliable, and scalable, while the human-centered design approach will ensure it is easy to use and meets Meisa's needs.



## Design statement
I will design and develop a user-friendly program to help Meisa manage the data of her convenience store. The program will allow Meisa to store and manage all the essential information related to products, suppliers, aisle, and staff in a centralized database, eliminating the disorganization and tediousness of the previous process. The program will be designed with a human-centered approach, making it simple and easy to use for everyone working at the store.

The program will be developed using the Python programming language and the KivyMD user interface framework. The program will be designed using an object-oriented approach with classes to manage the data entities of aisles and staff. The program will be developed using a SQL database, which will enable efficient data storage, retrieval, and management. The database will be designed with tables for each of the data entities.

To ensure the program is user-friendly, I will conduct user testing throughout the development process, soliciting feedback from Meisa to identify any areas for improvement. I will also evaluate the program against Criteria A, B, C, and D to ensure it meets Meisa's requirements and is effective in managing the store's data.

The development process will take approximately 4 weeks, after which I will conduct a final round of testing and client meeting before finalizing the program for Meisa's store. The program will be designed to allow Meisa to add or delete data as the year progresses, ensuring the program remains relevant and useful throughout the year.



## Success Criteria

1. The client can register a new account
2. The client can log in to the application by using the information they previously registered.
3. The registration has an pasword and email policy.
4. The program automatically hashes the user's password information.
5. The program can store the information of items sold in tables by cateogories such as type, company, name, id, etc.
6. The user can edit the tables by deleting and adding.
7. The table screens has a button that allows the user to show the information of the table after they added new items.
8. The program contains a table where all items are stored, so that Meisa can check the complete inventory without having to visit all aisles.
9. The app uses databases to store information such as users and the data in the MDDataTables.
10. The app has easy to understand labels and interface to make it easier for the client, Meisa to implement it at her store.

---
<img width="1136" alt="Screen Shot 2023-03-08 at 17 57 36" src="https://user-images.githubusercontent.com/111941990/223959197-cdfeb104-c252-49ea-b28d-ca950ae8240d.png">

# Criterion B- Planning

## System Diagram
![Project_3 system diagram](https://user-images.githubusercontent.com/111941990/223882562-09e23bb1-13d5-4bc1-994e-e5b2b9038f9b.png)

## Wireframe Diagram
![Wireframe diagram (2)](https://user-images.githubusercontent.com/111941990/223984515-8810b102-adf5-4346-b2be-2421a11579f3.png)

## UML Diagram
![UML_diagram](https://user-images.githubusercontent.com/111941990/223997898-93b6cbc5-725e-4c71-839f-b31b7b34972e.png)



## Test Plan

## Tasks
| Task No |              Planned Action              |                                   Planned Outcome                                   | Time estimate | Target completion date | Criterion |
|:-------:|:----------------------------------------:|:-----------------------------------------------------------------------------------:|:-------------:|:----------------------:|:---------:|
|    1    |             Getting a client             |                  Client described her requiremetns for the project                  |     5 min     |         Feb 10         |     A     |
|    2    | Meeting client to understand the problem |                 Write Success Criteria and Client gives her agreeing                |     7 min     |         Feb 10         |     A     |
|    3    |       Identify the client's problem      |                            Problem definition on git hub                            |     7 min     |         Feb 16         |     A     |
|    4    |          Craft design statement          |             Design statement in git hub and a clearer course of action              |     15 min    |         Feb 18         |     A     |
|    5    |       Getting the client's approval      | Evidence of the clients agreement with the proposed solution  and design sptatement |     10 min    |         Feb 19         |     A     |


## Evidence
<img width="1067" alt="Screen Shot 2023-03-09 at 9 03 36" src="https://user-images.githubusercontent.com/111941990/223880914-0af17701-eef8-40fa-94d8-4d15886c84ab.png">

---
<img width="1108" alt="Screen Shot 2023-03-09 at 17 04 23" src="https://user-images.githubusercontent.com/111941990/223959341-1fd88518-b2d1-42e1-bdee-cfa5b9f58872.png">


# Criterion C- Development
## SQL Database & Tables
As part of my progrma I created a database to store the particular data in the program such as users and items. I did it using SQLite and creating tables in side my ```.py db_login.db``` database. To do so I connected my python file to my SQLlite databese and used a query to create the MDDatatabel, the I exectued th equery, commited it to the app and closed the connection with the database. 


```.py
connection = sqlite3.connect("db_login.db")
cursor = connection.cursor()

query = f"""CREATE TABLE if not exists users(
    id INTEGER PRIMARY KEY,
    email text NOT NULL unique,
    password text NOT NULL,
    username text not null
)
"""

cursor.execute(query)
connection.commit()
connection.close()
```

## Secure password
```.py
# secure_password.py
from passlib.hash import sha256_crypt

#Create an object of the class CryptContext
hasher= sha256_crypt.using(rounds=30000)

#this function receives the unsafe password
# and returns the hashed password
def encrypt_password(user_password):
    return hasher.hash(user_password)

def check_password(hashed_password, user_password):
    return hasher.verify(user_password, hashed_password)
```

One of the success criteria that the client wanted in its programs is that “The program automatically hashes the user's password information”. In order for this to happen I created a set of functions during class, in the file  ``` secure_password.py ```  that uses the ``` passlib ``` library to hash passwords securely. The code defines two functions: ```encrypt_password```  and ```check_password```.

The ``` encrypt_password``` function takes an unsafe plain-text password as an argument and returns a hashed version of it using the SHA-256 cryptographic hash function. The hashed password is created using the CryptContext object, which is instantiated from the sha256_crypt class with a parameter 'rounds=30000'. The higher the number of rounds, the more secure the hash function becomes.

The "check_password" function takes a hashed password and a plain-text password as arguments. It then verifies whether the plain-text password matches the hashed password using the verify method provided by the sha256_crypt object. The verify method returns a Boolean value indicating whether the password is a match or not.




## Login
```.py
class LoginScreen(MDScreen):
    def try_login(self):
        print("User tried to login")
        # Get the input username and password and print it
        uname = self.ids.uname.text
        passwd = self.ids.passwd.text
        query = f"SELECT * from users WHERE username='{uname}'"
        db = database_worker("db_login.db")
        result = db.search(query=query)
        db.close()

        if len(result) == 1:
            id, email, hashed, uname = result[0]
            if check_password(user_password=passwd, hashed_password=hashed):
                self.parent.current = "MenuScreen"
                self.ids.uname.text = ""
                self.ids.passwd.text = ""
            else:
                self.parent.current = "LoginScreen"
                print("Passwords don't match")

```
This is a Python code for a login screen class that extends from the MDScreen class. The code defines a ```try_login()``` function that is called when the user tries to log in.The function starts by retrieving the username and password entered by the user from the respective text input fields. I then have the SQL query to search for the user in the database using the username. With the ```database_worker()``` I connect to my SQLite database named ```db_login.db```.

The result of the query is stored in the 'result' variable, and the connection to the database is closed. The code then retrieves the hashed password from the query result and uses the ```check_password()``` function to compare it with the user’s input. If the passwords match, the user is redirected to the ```MenuScreen```, and the text input fields are cleared. Otherwise, an error message is printed and the user stays on the login screen. The ```loginScreen``` is the first thing that appears in my program and I constantly re-use it to send the user back, for example when login out or after registration.


## Registration
```.py
class RegistrationScreen(MDScreen):
    def try_register(self):
        print("this is the registration")
        uname = self.ids.uname.text
        email = self.ids.email.text
        passwd = self.ids.passwd.text
        passwd_check = self.ids.passwd_check.text
```
In the program, the  ```try_register()``` function is called when the user clicks on the ```Register``` button. The function starts by retrieving the input data from the respective text input fields. Then it stores the username in the ```uname``` variable, the email in the ```email``` variable, and the password and password confirmation in ```passwd``` and ```passwd_check``` variables.

#### Password policy
```.py
# Check password policy
        if len(passwd) < 6 or " " in passwd or passwd != passwd_check:
            if len(passwd) < 6:
                self.ids.passwd.error = True
                self.ids.passwd.helper_text = "Password must be at least 6 characters"
            if " " in passwd:
                self.ids.passwd.error = True
                self.ids.passwd.helper_text = "Password cannot contain spaces"
            if passwd != passwd_check:
                self.ids.passwd_confirm.error = True
                self.ids.passwd_confirm.helper_text = "Passwords do not match"
            return
```
My password policy for the client checks the input password based on password length, spaces, and that the password and the password confirmation match.

The code starts by checking the length of the input password. If the password length is less than 6 characters, an error message is displayed to the user. The input field will also be marked with an error flag to draw the user's attention.

The next check ensures that there are no spaces in the password. If a space is detected, the error message will be displayed, and the input field marked with an error flag.

Finally, the code checks to see if the input password matches the confirmation password. If they do not match, the error message will be displayed, and the input field for the confirmation password will be marked with an error flag.

If any of the checks fail, the function will return, preventing the registration process from proceeding. If all the checks pass, the user will be redirected to the ```loginScreen```.


#### Email policy
```.py
# Check email policy
        if "@" not in email:
            self.ids.email.error = True
            self.ids.email.helper_text = "Invalid email"
            return
```
This section of the code is like the password policy, but for the email input. It is a validation check that verifies whether a given email address contains the "@" symbol.

```.py
# All policies, proceed with registration
        hash = encrypt_password(passwd)
        db = database_worker("db_login.db")
        query = f"INSERT into users (email, password, username) values('{email}', '{hash}','{uname}')"
        db.run_save(query)
        db.close()

        print("Registration completed")
        MDSpinner(
            size_hint=(None, None),
            size=(dp(46), dp(46)),
            pos_hint={'center_x': .5, 'center_y': .5},
            active=True,
            palette=[
                [0.28627450980392155, 0.8431372549019608, 0.596078431372549, 1],
                [0.3568627450980392, 0.3215686274509804, 0.8666666666666667, 1],
                [0.8862745098039215, 0.36470588235294116, 0.592156862745098, 1],
                [0.8784313725490196, 0.9058823529411765, 0.40784313725490196, 1],
            ]
        )
        self.parent.current = "LoginScreen"

    def cancel(self):
        self.parent.current = "LoginScreen"
```
And finally, this part finalizes the registration and saves it into ```users``` table.

## MDDataTables

```.py
    def __init__(self, **kwargs):
        MDScreen.__init__(self, **kwargs)

        # Define columns and rows for the MDDataTable
        self.data_table = MDDataTable(
            size_hint=(0.9, 0.7),
            pos_hint={"center_x": 0.5, "center_y": 0.5},
            check=True,
            use_pagination=True,
            column_data=[
                ("id", dp(30)),
                ("Item", dp(30)),
                ("Aisle", dp(30)),
                ("Shelve", dp(30)),
                ("Amount", dp(20)),
                ("Company", dp(30))
            ],
            row_data=[
                ("Item 1", "1", "2", "3", "Company A"),
                ("Item 2", "4", "5", "6", "Company B")
            ]
        )

        # add table
        self.data_table.bind(on_row_press=self.row_pressed)
        self.data_table.bind(on_check_press=self.check_pressed)
        self.add_widget(self.data_table)
        self.update()

    def row_pressed(self, table, row):
        print("a row was pressed", row.text)
        row.md_bg_color = "#EFCB68"

    def check_pressed(self, table, current_row):
        print("a row was checked", current_row)

```
I used this code several times, to create the datatables of each one of the aisles, although I think that the end results were great, I do think that I could have done it in an easier way, probably by creating a loop. The code defines a class that creates and displays a data table using the KivyMD library. The data table is used to display a list of items, with columns for the item ID, name, aisle, shelve, amount, and company.

The ```__init__ ``` method initializes the class and creates a new ```MDDataTable```. The ```size_hint``` and ```pos_hint``` arguments set the size and position of the table. The check and ```use_pagination``` arguments enable row selection and pagination.

The ```column_data``` argument defines the table columns, with each column represented as a tuple that contains the column name and its width. The ```row_data``` enables the selection of the item information in a row. The ```row_pressed method``` is called when a row in the table is pressed. The method takes two arguments, table and row, and sets the background color of the pressed row to a different color so that the program is as user-friendly as possible. The ```check_pressed``` method is called when a row in the table is checked. The method takes two arguments, table and current_row, and prints a message indicating that a row was checked.

## Use of Relational database
```.py
class Inventory:
    def __init__(self, db_name):
        self.db_name = db_name
        self.db = database_worker(db_name)

    def get_all_data(self):
        tables = ['aisle37', 'aisle_2', 'aisle_3', 'aisle_4', 'fridges']
        all_data = []
        for table in tables:
            query = f"SELECT * from {table}"
            result = self.db.search(query=query)
            all_data += result
        return all_data

    def save_to_complete_inventory(self, data):
        self.db.run_save("DROP TABLE IF EXISTS complete_inventory")
        self.db.run_save("""CREATE TABLE complete_inventory(
            id INTEGER PRIMARY KEY,
            item TEXT NOT NULL,
            aisle TEXT NOT NULL,
            shelve TEXT NOT NULL,
            amount TEXT NOT NULL,
            company TEXT NOT NULL
        )""")
        for item in data:
            query = f"""INSERT INTO complete_inventory(item, aisle, shelve, amount, company)
            VALUES('{item[1]}', '{item[2]}', '{item[3]}', '{item[4]}', '{item[5]}')"""
            self.db.run_save(query)

    def close(self):
        self.db.close()
```
Unlike the other aisle classes, this is the ```Inventory``` which takes all data from the rest of the aisle tables and relates it all by saving it into the same table and shows it all in one MDDataTable. The class has several methods that interact with a database. The constructor of the class takes a parameter db_name, which is the name of the database to be used by the class.

The method ```get_all_data``` returns all the data from five different tables in the database. The data is retrieved using a ```SELECT``` statement on each table and appends it to the ```all_data``` list. Finally, the ```all_data``` list is returned.

The method ```save_to_complete_inventory``` creates a new table named ```complete_inventory``` in the database and inserts data into it. The method first drops the complete_inventory table if it already exists. Then, it creates the ```complete_inventory``` table with five columns: id, item, aisle, shelve, amount, and company. Finally, the method loops through each item in the parameter and inserts it into the ```complete_inventory``` table using an ```INSERT``` statement.

Finally, the ```close``` method closes the connection to the database by calling the ```close``` method on the ```database_worker```.

## KivyMD File
This is my complete ```kivyMD``` file where I strudctured my entire program, creating layouts to stucture approcirate text and labels, buttons and a bottom menu that allows the client and any user of the progam to navigate the app.

```.py
#login.kv
ScreenManager:
    LoginScreen:
        name: "LoginScreen"

    RegistrationScreen:
        name: "RegistrationScreen"

    HomeScreen:
        name: "HomeScreen"

    PersonalScreen:
        name: "PersonalScreen"

    MenuScreen:
        name: "MenuScreen"

    AddItemScreen:
        name: "new_item"
    AddItemScreen_2:
        name: "new_item_2"
    AddItemScreen_3:
        name: "new_item_3"
    AddItemScreen_4:
        name: "new_item_4"
    AddItemScreen_5:
        name: "new_item_f"

    SnacksScreen:
        name: "SnacksScreen"

    BakeryScreen:
        name: "BakeryScreen"

    MealsScreen:
        name: "MealsScreen"

    FridgesScreen:
        name: "FridgesScreen"

    InventoryScreen:
        name: "InventoryScreen"

<HomeScreen>:
    FitImage:
        source:"kon.jpg"

    MDCard:
        size_hint: .6, .8
        pos_hint: {"center_x":.5, "center_y":.54}
        orientation: "vertical"

        MDLabel:
            size_hint: 1,.3
            font_style: "H2"
            text: "Welcome!"
            pos_hint: {"center_x":.5, "center_y":.9}
            halign: "center"

    MDRaisedButton:
        text: "Log Out"
        size_hint_x: 0.5
        pos_hint: {"center_x":.5, "center_y":.4}
        on_press: app.root.current = "LoginScreen"
        md_bg_color: "pink"


    MDRaisedButton:
        text: "Aisles"
        size_hint_x: 0.5
        pos_hint: {"center_x":.5, "center_y":.3}
        on_press: app.root.current = "MenuScreen"
        md_bg_color: "lightblue"




<LoginScreen>:
    FitImage:
        source:"kon.jpg"
    MDCard:
        size_hint: .6, .8
        pos_hint: {"center_x":.5, "center_y":.54}
        orientation: "vertical"

        MDLabel:
            size_hint: 1,.3
            font_style: "H2"
            text: "Login"
            halign: "center"

        MDTextField:
            id: uname
            hint_text: "Username"
            size_hint: .8, .1
            pos_hint: {"center_x":.5}

        MDTextField:
            id:passwd
            hint_text: "Password"
            password: True
            size_hint: .8, .1
            pos_hint: {"center_x":.5}

        MDBoxLayout:
            size_hint: 1,.1

            MDRaisedButton:
                id: login
                text: "Login"
                md_bg_color: "#FFC857"
                on_press: root.try_login()
                size_hint: .5, 1

            MDRaisedButton:
                text: "Register"
                md_bg_color: "#e63946"
                on_press: root.parent.current = "RegistrationScreen"
                size_hint: .5, 1



<RegistrationScreen>:
    FitImage:
        source: "kon.jpg"
    MDSpinner:
        size_hint: None, None
        size: dp(27), dp(27)
        pos_hint: {'center_x': .5, 'center_y': .1}
        determinate: True

    MDCard:
        size_hint: .6, .8
        pos_hint: {"center_x":.5, "center_y":.54}
        orientation: "vertical"

        MDLabel:
            size_hint: 1,.1
            font_style: "H4"
            text: "Register"
            halign: "center"

        MDTextField:
            id: uname
            hint_text: "Username "
            size_hint: .8, .1
            pos_hint: {"center_x":.5}

        MDTextField:
            id: email
            size_hint: .8, .1
            pos_hint: {"center_x":.5}
            hint_text: "Email"
            helper_text_mode: "on_error"
            helper_text: "Invalid email"
            icon_right: "email"
            icon_right_color: app.theme_cls.primary_color
            required: True
            line_color_normal: app.theme_cls.primary_color
            color_active: app.theme_cls.primary_color

        MDTextField:
            id:passwd
            hint_text: "Password"
            password: True
            size_hint: .8, .1
            pos_hint: {"center_x":.5}
            helper_text_mode: "on_error"

        MDTextField:
            id:passwd_check
            hint_text: "Confirm password"
            password: True
            size_hint: .8, .1
            pos_hint: {"center_x":.5}
            helper_text_mode: "on_error"


        MDBoxLayout:
            size_hint: 1,.1

            MDRaisedButton:
                id: login
                text: "Back"
                md_bg_color: "#FFC857"
                on_press: root.manager.current = "LoginScreen"
                size_hint: .5, 1

            MDRaisedButton:
                text: "Register"
                md_bg_color: "#e63946"
                on_press: root.try_register()
                size_hint: .5, 1




<MenuScreen>:
    FitImage:
        source:"kon.jpg"
    MDBottomNavigation:
        id: bottom_navigation
        selected_color_background: "lightgrey"
        text_color_active: "lightgrey"
        text_color_active: "pink"

        MDBottomNavigationItem:
            md_bg_color: "#FFE381"
            name: 'HomeScreen'
            text: 'LogOut'
            icon: 'home'
            text_color_active: 0, 0, 0, 1
            on_tab_press: root.manager.current="HomeScreen"

            MDCard:
                size_hint: .6, .8
                pos_hint: {"center_x":.5, "center_y":.54}
                orientation: "vertical"
                FitImage:
                    source:"kon.jpg"

                MDLabel:
                    size_hint: 1,.3
                    font_style: "H2"
                    text: "LogOut"
                    halign: "center"

                MDRaisedButton:
                    text: "Log Out"
                    size_hint_x: 0.9
                    pos_hint: {"center_x":.5, "center_y":.3}
                    on_press: app.root.current = "LoginScreen"
                    md_bg_color: "pink"

        MDBottomNavigationItem:
            name: 'PersonalScreen'
            text: 'Personals'
            icon: 'hanger'
            text_color_active: 0, 0, 0, 1
            on_tab_press: root.manager.current="PersonalScreen"

            FitImage:
                source:"toothpaste.jpeg"



        MDBottomNavigationItem:
            name: 'SnacksScreen'
            text: 'Snacks'
            icon: 'candy'
            text_color_active: 0, 0, 0, 1
            on_tab_press: root.manager.current="SnacksScreen"

            FitImage:
                source:"doritos.png"



        MDBottomNavigationItem:
            name: 'BakeryScreen'
            text: 'Bakery'
            icon: 'food-croissant'
            text_color_active: 0, 0, 0, 1
            on_tab_press: root.manager.current="BakeryScreen"

            FitImage:
                source:"Anime Foodie.jpeg"



        MDBottomNavigationItem:
            name: 'MealsScreen'
            text: 'Meals'
            icon: 'food-turkey'
            text_color_active: 0, 0, 0, 1
            on_tab_press: root.manager.current="MealsScreen"

            FitImage:
                source: "noodles.jpeg"


        MDBottomNavigationItem:
            name: 'FridgesScreen'
            text: 'Fridges'
            icon: 'fridge'
            text_color_active: 0, 0, 0, 1
            on_tab_press: root.manager.current="FridgesScreen"

            FitImage:
                source:"olipop.jpeg"

        MDBottomNavigationItem:
            name: 'InventoryScreen'
            text: 'Inventory'
            icon: 'clipboard-list'
            text_color_active: 0, 0, 0, 1
            on_tab_press: root.manager.current="InventoryScreen"

            FitImage:
                source:"kon.jpg"



<PersonalScreen>:
    MDBoxLayout:
        orientation: "vertical"

        MDCard:
            md_bg_color: "#F2AFFF"
            size_hint: .6, .1
            pos_hint: {"center_x":.5, "center_y":.5}
            orientation: "vertical"

            MDLabel:
                size_hint: 1,.1
                font_style: "H3"
                text: "Aisle 1"
                halign: "center"

        MDBoxLayout:
            orientation: "horizontal"

            MDFillRoundFlatIconButton:
                text: "Back"
                icon: "arrow-left"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: app.root.current = "MenuScreen"

            MDRaisedButton:
                text: "Delete"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: root.delete()
            MDRaisedButton:
                text: "Add"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: app.root.current = "new_item"
            MDFillRoundFlatIconButton:
                text: "Update"
                icon: "content-save"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: root.update()

<AddItemScreen>:
    FitImage:
        source: "purple.jpeg"

    MDLabel:
        size_hint: 1,.1
        pos_hint: {"center_x":.5, "center_y":.8}
        font_style: "H2"
        text: "New Item"
        halign: "center"

    MDBoxLayout:
        orientation: "vertical"
        spacing: dp(10)
        padding: dp(20)

        MDTextField:
            id: Item  # Fixed id name
            hint_text: "Item"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "barcode-scan"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Aisle
            hint_text: "Aisle"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "arrow-right"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Shelve
            hint_text: "Shelve"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "arrow-right"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Amount
            hint_text: "Amount"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "numeric"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Company
            hint_text: "Company"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "office-building"
            icon_right_color: app.theme_cls.primary_color

        MDFillRoundFlatIconButton:
            text: "Save"
            icon: "content-save"
            pos_hint: {"center_x": 0.5}
            on_release: root.new_item()

        MDFillRoundFlatIconButton:
            text: "Cancel"
            icon: "cancel"
            pos_hint: {"center_x": 0.5}
            on_release: app.root.current = "PersonalScreen"

#Snacks
<SnacksScreen>:
    MDBoxLayout:
        orientation: "vertical"
        MDCard:
            md_bg_color: "#FE7F2D"
            size_hint: .6, .1
            pos_hint: {"center_x":.5, "center_y":.5}
            orientation: "vertical"

            MDLabel:
                size_hint: 1,.1
                font_style: "H3"
                text: "Aisle 2"
                halign: "center"

        MDBoxLayout:
            orientation: "horizontal"

            MDFillRoundFlatIconButton:
                text: "Back"
                icon: "arrow-left"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: app.root.current = "MenuScreen"

            MDRaisedButton:
                text: "Delete"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: root.delete()
            MDRaisedButton:
                text: "Add"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: app.root.current = "new_item_2"
            MDFillRoundFlatIconButton:
                text: "Update"
                icon: "content-save"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: root.update()

<AddItemScreen_2>:
    MDBoxLayout:
        orientation: "vertical"
        spacing: dp(10)
        padding: dp(20)

        MDTextField:
            id: Item  # Fixed id name
            hint_text: "Item"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "barcode-scan"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Aisle
            hint_text: "Aisle"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "arrow-right"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Shelve
            hint_text: "Shelve"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "arrow-right"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Amount
            hint_text: "Amount"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "numeric"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Company
            hint_text: "Company"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "office-building"
            icon_right_color: app.theme_cls.primary_color

        MDFillRoundFlatIconButton:
            text: "Save"
            icon: "content-save"
            pos_hint: {"center_x": 0.5}
            on_release: root.new_item_2()

        MDFillRoundFlatIconButton:
            text: "Cancel"
            icon: "cancel"
            pos_hint: {"center_x": 0.5}
            on_release: app.root.current = "SnacksScreen"


#Bakery
<BakeryScreen>:
    MDBoxLayout:
        orientation: "vertical"
        MDCard:
            md_bg_color: "#FFE381"
            size_hint: .6, .1
            pos_hint: {"center_x":.5, "center_y":.5}
            orientation: "vertical"

            MDLabel:
                size_hint: 1,.1
                font_style: "H3"
                text: "Aisle 3"
                halign: "center"


        MDBoxLayout:
            orientation: "horizontal"

            MDFillRoundFlatIconButton:
                text: "Back"
                icon: "arrow-left"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: app.root.current = "MenuScreen"

            MDRaisedButton:
                text: "Delete"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: root.delete()
            MDRaisedButton:
                text: "Add"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: app.root.current = "new_item_3"
            MDFillRoundFlatIconButton:
                text: "Update"
                icon: "content-save"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: root.update()

<AddItemScreen_3>:
    MDBoxLayout:
        orientation: "vertical"
        spacing: dp(10)
        padding: dp(20)

        MDTextField:
            id: Item  # Fixed id name
            hint_text: "Item"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "barcode-scan"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Aisle
            hint_text: "Aisle"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "arrow-right"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Shelve
            hint_text: "Shelve"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "arrow-right"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Amount
            hint_text: "Amount"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "numeric"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Company
            hint_text: "Company"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "office-building"
            icon_right_color: app.theme_cls.primary_color

        MDFillRoundFlatIconButton:
            text: "Save"
            icon: "content-save"
            pos_hint: {"center_x": 0.5}
            on_release: root.new_item_3()

        MDFillRoundFlatIconButton:
            text: "Cancel"
            icon: "cancel"
            pos_hint: {"center_x": 0.5}
            on_release: app.root.current = "BakeryScreen"

#MEALSSCREEN AISLE 4
<MealsScreen>:
    MDBoxLayout:
        orientation: "vertical"
        MDCard:
            md_bg_color: "#EB4511"
            size_hint: .6, .1
            pos_hint: {"center_x":.5, "center_y":.5}
            orientation: "vertical"

            MDLabel:
                size_hint: 1,.1
                font_style: "H3"
                text: "Aisle 4"
                halign: "center"


        MDBoxLayout:
            orientation: "horizontal"

            MDFillRoundFlatIconButton:
                text: "Back"
                icon: "arrow-left"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: app.root.current = "MenuScreen"

            MDRaisedButton:
                text: "Delete"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: root.delete()
            MDRaisedButton:
                text: "Add"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: app.root.current = "new_item_4"
            MDFillRoundFlatIconButton:
                text: "Update"
                icon: "content-save"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: root.update()

<AddItemScreen_4>:
    MDBoxLayout:
        orientation: "vertical"
        spacing: dp(10)
        padding: dp(20)

        MDTextField:
            id: Item  # Fixed id name
            hint_text: "Item"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "barcode-scan"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Aisle
            hint_text: "Aisle"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "arrow-right"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Shelve
            hint_text: "Shelve"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "arrow-right"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Amount
            hint_text: "Amount"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "numeric"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Company
            hint_text: "Company"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "office-building"
            icon_right_color: app.theme_cls.primary_color

        MDFillRoundFlatIconButton:
            text: "Save"
            icon: "content-save"
            pos_hint: {"center_x": 0.5}
            on_release: root.new_item_4()

        MDFillRoundFlatIconButton:
            text: "Cancel"
            icon: "cancel"
            pos_hint: {"center_x": 0.5}
            on_release: app.root.current = "MealsScreen"

#FRIDGESSCREEN AISLE 5
<FridgesScreen>:
    MDBoxLayout:
        orientation: "vertical"
        MDCard:
            md_bg_color: "#C5FFFD"
            size_hint: .6, .1
            pos_hint: {"center_x":.5, "center_y":.5}
            orientation: "vertical"

            MDLabel:
                size_hint: 1,.1
                font_style: "H3"
                text: "Fridges"
                halign: "center"

        MDBoxLayout:
            orientation: "horizontal"

            MDFillRoundFlatIconButton:
                text: "Back"
                icon: "arrow-left"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: app.root.current = "MenuScreen"

            MDRaisedButton:
                text: "Delete"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: root.delete()
            MDRaisedButton:
                text: "Add"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: app.root.current = "new_item_f"
            MDFillRoundFlatIconButton:
                text: "Update"
                icon: "content-save"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: root.update()

<AddItemScreen_5>:
    MDBoxLayout:
        orientation: "vertical"
        spacing: dp(10)
        padding: dp(20)

        MDTextField:
            id: Item  # Fixed id name
            hint_text: "Item"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "barcode-scan"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Fridge
            hint_text: "Fridge"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "arrow-right"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Shelve
            hint_text: "Shelve"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "arrow-right"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Amount
            hint_text: "Amount"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "numeric"
            icon_right_color: app.theme_cls.primary_color

        MDTextField:
            id: Company
            hint_text: "Company"
            mode: "fill"
            fill_color: 1, 1, 1, 0.8
            icon_right: "office-building"
            icon_right_color: app.theme_cls.primary_color

        MDFillRoundFlatIconButton:
            text: "Save"
            icon: "content-save"
            pos_hint: {"center_x": 0.5}
            on_release: root.new_item_f()

        MDFillRoundFlatIconButton:
            text: "Cancel"
            icon: "cancel"
            pos_hint: {"center_x": 0.5}
            on_release: app.root.current = "FridgesScreen"


#Inventory
<InventoryScreen>:
    MDBoxLayout:
        orientation: "vertical"
        MDCard:
            md_bg_color: "#EB4511"
            size_hint: .6, .1
            pos_hint: {"center_x":.5, "center_y":.5}
            orientation: "vertical"

            MDLabel:
                size_hint: 1,.1
                font_style: "H3"
                text: "Inventory"
                halign: "center"


        MDBoxLayout:
            orientation: "horizontal"

            MDFillRoundFlatIconButton:
                text: "Back"
                icon: "arrow-left"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: app.root.current = "MenuScreen"

            MDRaisedButton:
                text: "Delete"
                size_hint_x: .1
                pos_hint: {"center_x":.5, "center_y":.1}
                on_press: root.delete()

            MDFillRoundFlatIconButton:
                text: "Update"
                icon: "content-save"
                pos_hint: {"center_x": .5, "center_y":.1}
                on_release: root.update()
```

---
<img width="1054" alt="Screen Shot 2023-03-09 at 17 07 23" src="https://user-images.githubusercontent.com/111941990/223959565-75731030-1a0a-4136-8079-861c4903a393.png">

# Criterion D
## Video link
https://drive.google.com/file/d/1SVK2XTKwq2TzD0mghma51RkyDYSUDXH2/view?usp=sharing

