<!--Title-->
# Effat University Book Club

## Purpose
<!--Purpose of the project-->
This poject is a website dedicated for Effat University book Club (leader and members). 

<img src="https://github.com/AichaSidiya/BookClub/blob/main/demoBookClub.gif"/>

<!--Header 2 description of the project-->
## Description

This project will create a database for the club which stores members data, data about the books they read and event they hosted. 

## Enhancement
* Send the contact us message to the club email.
* Add a back up button to the club members and book list pages
* Add a menu and a back up buttoon to the event page for the each event
* Add a more button to the each book in the book list and hide some the summary
* Create an discssion board for each book and a rating option.


<!--Header 3 front end-->
## FRONT-END

### Website Layout

#### Home
* Main activities that the club provide. 
* Joining or logging in: 
* Contact the club. 

##### Join Us 
* Form to join the club

##### Log In Page
###### Profile Page
* Edit/Delete profile 
**Note**: admin can't delete her account she can only update it.

###### Book Read
* Form to add books (accessed by members only)
#### About Us
* Breif about the club mission, vision, and objective, with a "Be Part of Our Family" button which take her to the join us form. 
#### Event
* View and register in events.
* Manage event button for the **admin**.

##### Manage Event
* Add/Edit/Delete event. 
* View who registered in events.

#### Club Members
* List of all club members.

#### Book List
* List of all read books with a summary of each book. 
* Edit Book button for members and admin.
* Delete button for the admin.
##### Edit Book
##### Delete Book 


## Back-END

We have 5 tables in our database

### Members
* Includes all the member information extracted from the join us form.
### Books
* Includes all the book information exctracted from the book read form.
### Events
* Includes all the event information exctracted from the add event form.
### Event Attendance
* Includes all the student and event id.
### Messages
* Includes the message and the the contact information of the user who left the message.


## Files
### CSS

* Ourstyle.css
* booklist.css
* clubMembers.css
* styles.css


### Javascript

* Bookread.js
* Deletebook.js
* Editbook.js
* Editevent.js
* Editprofile.js
* eventRegistration.js
* myScript.js
* newevent.js
* scripts.js

<!--Header 3 installation and launching the project-->
## Installation
* Clone the repository to your local machine:
```
git clone https://github.com/AichaSidiya/BookClub.git
``` 
* Install [xampp](https://www.apachefriends.org/download.html)
* Import the bookclub.sql file to [phpmyadmin](localhost/phpmyadmin/)
* Update the database connection to match your database crendentials.
* Host the files on a web server and access the website using your preferred browser.

## Authors
<!-- The contributors to the project-->
* [Aicha Sidiya](https://github.com/AichaSidiya)
* [Hanin AlZaher](https://github.com/hanin-az)
* [Razan AlMahdi](https://github.com/RazanAlmahdi)
* [Reem AlSharabi](https://github.com/ReemAlsharabi)


## Acknowledgments
<!-- Insparation files, codes, and general refrences used in writing the code of the project-->
* [BootStrap used](https://startbootstrap.com/previews/agency)
* [JavaScript guide](https://www.w3schools.com/js/default.asp)
* [JavaScript form Validation](https://www.javatpoint.com/confirm-password-validation-in-javascript)
* [JavaScript password Validation](https://www.javatpoint.com/javascript-form-validation)
* [JavaScript form Validation2](https://www.geeksforgeeks.org/form-validation-using-html-javascript/)
* [CSS grid style](https://stackoverflow.com/questions/47587892/how-does-css-grid-layout-works)
* [Readme Template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
* [Readme Content Table](https://ecotrust-canada.github.io/markdown-toc/)
