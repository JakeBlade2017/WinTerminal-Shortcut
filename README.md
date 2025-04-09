# Windows-Terminal-Context-Menu
Regedit file that adds "Open in Terminal" into context menu

Before we continue please place the `wt.ico` into Windows Terminal directory

Don't know where is? No problem! in CMD just type `where wt` and it will print the directory

## What are the differences between the reg files?

Well as the name says
- `wt-all-users` Adds the button on the context menu for **all users** that are in your computer
- `wt-single-user` Adds the button on the context menu only for the **current user** in your computer

## What can be costumizable?
Context menu text can be costumizable, on both files are in the _**line 4**_ and _**line 5**_

`@="Open in Terminal"` ---> Costumizable text

`"Icon"="%LocalAppdata%\\Microsoft\\WindowsApps\\wt.ico"` ---> Set the path of custom icon (must be in _.ico_ format)

## Preview

![image](https://github.com/user-attachments/assets/ac5b6d2f-332e-4a96-b4bc-7de7de6b8f67)
