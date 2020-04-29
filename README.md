# Project 0

Web Programming with Python and JavaScript

Hello, I bring you my project0 containing 4 html pages namely: Index,Education,BioData,Hobbies.
1. Index.html page is used to Greet User and allow user to easily nagivate to other pages of website.
2. Education.html page uses table feature to list my Education Qualification.
3. Hobbies.html page gives user a graphical way to look at my hobbies using column and grid feature of bootstrap.
4. Personal_Details.html prints out my personal details ie. BioData including the places I have travelled.

project0/images -> contain all necessary images needed to load the webpage.
project0/css    -> contain all necessary css/stylesheet files.  

        1. bgcolor.css : This file contain stylesheet support for Education,Hobbbies,BioData Pages.
              -> this file is generated from bgcolor.scss contained in project0/css/scss/bgcolor.scss
              -> bgcolor.scss : This file lets me dynamically change bg color of all pages (except Index)
                                by making use of "SCSS Variable".
                                Quotes of Education Page can also be dynamically changed directly from this
                                file using "SCSS Variable" , selector and content property of CSS.
                                Also, This file makes use of "SCSS Inheritance" and "SCSS Nesting" feature
                                to easily set CSS properties for quotes section on Education Page. 
                                Also, this page serves as css file of navigation bar , which is common to all
                                above pages.
        2. education.css : This file is used as stylesheet file of Education and Hobbies page both.
        3. index.css : This file is used as stylesheet file of  Index Page.
        4. pd.css : This file is used as stylesheet file of  BioData Page.
