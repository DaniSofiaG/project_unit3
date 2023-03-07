# project_unit3

![The Wonderful World of Japan’s Incredible Convenience Stores](https://user-images.githubusercontent.com/111941990/218233255-1c0c1ab4-c711-4ab8-b310-7a1c23530967.jpeg)


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
7. The table screens has a button that allows the user to update the information of the table after they added new items.
8. The app uses databases to store information such as users and the data in the MDDataTables.
9. The app has easy to understand labels and interface to make it easier for the client Meisa to implement it at her store.

## System Diagram
![Untitled drawing (2)](https://user-images.githubusercontent.com/111941990/223357612-a1415042-da9f-454f-8bc4-2a2bb066b110.png)


## Test Plan
| Task No |              Planned Action              |                                   Planned Outcome                                   | Time estimate | Target completion date | Criterion |
|:-------:|:----------------------------------------:|:-----------------------------------------------------------------------------------:|:-------------:|:----------------------:|:---------:|
|    1    |             Getting a client             |                  Client described her requiremetns for the project                  |     5 min     |         Feb 10         |     A     |
|    2    | Meeting client to understand the problem |                 Write Success Criteria and Client gives her agreeing                |     7 min     |         Feb 10         |     A     |
|    3    |       Identify the client's problem      |                            Problem definition on git hub                            |     7 min     |         Feb 16         |     A     |
|    4    |          Craft design statement          |             Design statement in git hub and a clearer course of action              |     15 min    |         Feb 18         |     A     |
|    5    |       Getting the client's approval      | Evidence of the clients agreement with the proposed solution  and design sptatement |     10 min    |         Feb 19         |     A     |
