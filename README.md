# CSE-115-Modern-Periodic-Table-Console-Application
Modern Periodic Table with C programming is a console application written in C programming language for CSE115 of North South University. 

<p align="center">
   NORTH SOUTH UNIVERSITY<br>
   Department of Electrical and Computer Engineering
<p>
<p align="center">
   ![image](https://user-images.githubusercontent.com/63312173/169691415-09dddee0-04c9-4411-911f-f0e02282f318.png)
   
</p>
<p align="center">
   CSE 115 L<br>
   Programming Language I Lab<br>
   Project Title: Modern Periodic Table<br>
   Submitted to: Ashik Mostafa Alvi<br>
   Date of Submission: 26th April 2019<br>
 <p>

# Project Overview:
Chemistry is everywhere in the world around us! Chemistry sometimes is called the "central science" and to know chemistry, all we need to learn about the chemical elements which occurs reactions behind. Periodic Table is one of the most important parts of Chemistry.  In this C language program where the user, can see a look alike model of IUPAC Periodic Table of Elements, also can search an element’s details (period, group, symbol, electron configuration, atomic weight , boiling point and melting point.) through its name, symbol, or atomic number by  giving specific inputs . It also displays history of periodic table, Information, and tips about the periodic table. All these will help the user to learn and know the periodic table of IUPAC .It will be interesting to learn periodic table through C programming.
Features:
1. Standard view of the IUPAC modern periodic table.
2. Provides historical information about modern periodic table.  
3. Provides information about how the modern periodic table is organized.
4. There is an option to search an element of modern periodic table. 
5. A search can be done by three ways.
      I.	By using element’s name.
      II.	By using element’s symbolic name.
      III.	By using element’s atomic number.
So, searching is user friendly.
6. For every successful search the program provides necessary information like name, origin of name, atomic weight, melting point, boiling point, electronic configuration, period number, and group name about that element.
7. All the information are added from reliable sources.  
    
The program can be controlled by a user driven menu; that has these following features: 
      1. View of modern periodic table.
      2. History of periodic table.   
      3. Search element of periodic table.  
      4. Information about periodic table.
      5. Exit.   
    
1. If 1st option is chosen:
          i. Displays the periodic table.
         ii. Shows an option to go back to the menu.
2. If 2nd option is chosen:
         User finds some notes about history of the periodic table and an option to go back to menu. 
3. If 3rd option is chosen:
          i. Displays 3 options to search the element for details.
1. Enter name according to order   takes input   Element’s details
2. Enter symbolic name   takes input      Element’s details                       
3. Enter atomic number   takes input   Element’s details
          ii. Shows option to search again.
         iii. Shows option to go back to menu.
4. If 4th option is chosen:
          - Displays some tips and information about periodic table and option to go back to menu.
5. If 5th option is chosen:
          - Ends the program and shows a “thank you” message on console.

# Functions: 
I. Pre-Defined Functions:
      1. printf ( ): displays information on console<br>
      2. scanf ( ): reads the information entered by user from console<br>
      3. fopen ( ): opens file<br>
      4. fgetc ( ): reads the information (character) from a file<br>
      5. strycpy ( ): copies one string to another string<br>
      6. system ( ): Execute system command<br>
      7. fclose ( ): closes file<br>
      8. fflush ( ):  typically used for output stream only<br>
      9. exit ( ):   Terminates calling process<br>
               
II. UserDefined Functions:
      1.	menu ( ): Is used to displays Menu<br>
      2.	displayTable ( ): Is used to display the periodic table<br>
      3.	displayInfo ( ): Is used to display the history of periodic table).<br>
      4.	searchElements ( ): Is used takes input to search elements of the table and display the result<br>
      5.	info ( ): Is used to display specific information about periodic table<br>
      6.	TAG ( ): Is used to display “Modern Periodic Table”<br>
