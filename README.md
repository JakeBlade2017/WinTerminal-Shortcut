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

<p align="center">
  <img src="https://i.postimg.cc/g0nV01vL/431626750-ac5b6d2f-332e-4a96-b4bc-7de7de6b8f67.png">
</p>

## That's all!

Something simple but effective when Windows Terminal app doesn't add you the context menu button ;3

<p align="center">
  <a href="https://reigentei.booth.pm/items/2425521"><img height=400px width=400px src="https://i.postimg.cc/HsGq4gPt/gawr-konosuba-alpha-200x200.gif"></a>
</p>

> Gawr Gura GIF made by INABATAKE

