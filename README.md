# Bookshop-with-Python-and-Tkinter

22-08-2020 || Nida Sardar

---

## Description.

Bookshop application is able to reterive all the existing books from database. With that, it also give you capability to add, search, delete or update the book information into database.

## Tkinter.

Application is developed by using "Tkinter" - The tkinter package (“Tk interface”) is the standard Python interface to the Tk GUI toolkit. Tkinter is Python's de-facto standard GUI (Graphical User Interface) package. It is a thin object-oriented layer on top of Tcl/Tk.
Tkinter is not the only GuiProgramming toolkit for Python. It is however the most commonly used one.

## SQLite3.

SQLite is a relational database management system (RDBMS) contained in a C library. In contrast to many other database management systems, SQLite is not a client–server database engine. Rather, it is embedded into the end program. File extension is " .db ".

The SQLite library is linked in and thus becomes an integral part of the application program. Linking may be static or dynamic. The application program uses SQLite's functionality through simple function calls, which reduce latency in database access: function calls within a single process are more efficient than inter-process communication.

## Application Design.

The design of application is very generic. Front end of application is created using Tkinter GUI, SQLite3 is used as databse.

Application contains 3 files:
- frontend.py
- backend.py
- books.db

## Create standalone executable version of Program.

For the development purpose, developers execute .py file but for user;s perspective it would be difficult fo rthem to execute .py file. 

## pyinstaller

PyInstaller bundles a Python application and all its dependencies into a single package. The user can run the packaged app without installing a Python interpreter or any modules.

1. Install pyinstaller
    
    - pip install pyinstaller

2. Create executable file.

    - pyinstaller frontend.py

    This command will creare executable file with many other files. This approach is suitable and helpful in case of troublesooting anny errors in future.

    - pyinstaller --onefile windowed frontend.py

    This command will create one executable file.

---


