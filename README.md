# JavaBookShop
  Course Assignment Project in Singapore Polytechnic.
  
  A virtual bookshop java applet.
  
  <img src="https://user-images.githubusercontent.com/5699978/192547529-0ed1eff8-9064-4b59-9b4a-8c5fb0be11fd.png" width="400">
  
# Features
1. 3 Category filter - Programming, Networking & Multimedia Books
2. Book selection via Picture or Title,Author,Price List 
3. System Login for Admin and Student
<details>
  <summary>4. Allow UI Color Customization</summary>
  
  ```
  [Student & Admin]
  - Change Bookshop Title Colour

  [Admin Customizable]
  - [Add Book]
  - Change BookSelected Colour
  - Change BookHighlighted Colour
  - Change BookTitle Text Colour
  - Change BookAuthor Text Colour
  - Change BookPrice Text Colour
  ```
  
</details>

5. Book search using partical text search on Books' Title,Author,Price and "Tags"
6. Add new book
7. Keyboard Hotkey shortcuts for certain tasks
7. Looped Music - Yesterday midi - beatles
  
# Install
1. Git Clone
2. Install [Java Runtime Environment](https://github.com/KhiewJianBin/JavaBookShop/blob/main/Redist/jre-8u341-windows-i586.exe) in Redist

## Usage
1. Run [BookShop.jar](https://github.com/KhiewJianBin/JavaBookShop/blob/main/BookShop.jar) using JRE

## Instructions

### Keyboard Hotkeys
```
Alt+F1 - Login/Logout
Alt+F2 - Previous Book
Alt+F3 - Next Book
Alt+F4 - Quit
```

### Login details
```
[Admin]
Username : admin
Password : 12345

[Student]
Username : student
Password : password
```

### Add new Book
```
1. Add a book picture inside JAR within pic folder
2. Login using admin
3. From Menu Bar, Goto: Properties --> Customize --> Book -> AddBook or press Alf+f9
4. Enter Book details in Dialogboxes
5. Enter Book picture filename packaged within the JAR e.g 'pic/10.jpg'
6. If everything is done correctly, new book will appear in a new category "Added Book"

```

## Bugs
- After adding a new book, books wont automatically refresh.
- Unable to Select First Index of Book Via Drop Down Menu.
- If multiple books have the Same Price, Book Selection will be wrong.

## Notes
- JAR file is just an packaged folder. Use an archiver(like winrar) to add or remove files from it.

## Dev Notes
- Uses a Dictionary data structure to hold all the books
- Max of 35 Books
