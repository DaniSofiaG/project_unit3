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
2. The client can log in to the application by using the information the previously registered.
3. The registration has an pasword and email policy.
4. The program automatically hashes the users passowrd information.
5. The program can store the information of items sold in tables by cateogories such as type, company, name, id, etc.
6. The user can edit the tables by deleting and adding.
7. The table screens has a button that allows the user to show the information of the table after they added new items.
8. The app uses databases to store information such as users and the data in the MDDataTables.
9. The app has easy to understand labels and interface to make it easier for the client Meisa to implement it at her store.

---
<img width="1136" alt="Screen Shot 2023-03-08 at 17 57 36" src="https://user-images.githubusercontent.com/111941990/223959197-cdfeb104-c252-49ea-b28d-ca950ae8240d.png">

# Criterion B- Planning

## System Diagram
![Project_3 system diagram](https://user-images.githubusercontent.com/111941990/223882562-09e23bb1-13d5-4bc1-994e-e5b2b9038f9b.png)

## Wireframe Diagram
![Wireframe diagram (2)](https://user-images.githubusercontent.com/111941990/223984515-8810b102-adf5-4346-b2be-2421a11579f3.png)



## Test Plan
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
#### Email policy
```.py
# Check email policy
        if "@" not in email:
            self.ids.email.error = True
            self.ids.email.helper_text = "Invalid email"
            return
```

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


---
<img width="1054" alt="Screen Shot 2023-03-09 at 17 07 23" src="https://user-images.githubusercontent.com/111941990/223959565-75731030-1a0a-4136-8079-861c4903a393.png">

# Criterion D
