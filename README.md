# FinalProject

The goal of this program is to deal with basic operations with PDF document.
I used the PDBbox from Apache and added it to my librairy. 

There are 6 main options to the program: Merge, Split, Encrpypt, Create, Edit and Read. The user can choose the option he wants.
I will describe each option:
  - Merge PDF: The user can insert the path of the PDFs he wants to merge. The program will check if the field is a PDF or not. The user can add as many PDF as he wants
               Then he has to select the folder in which he want to create the new PDF and enter the name he wants to give to the PDF. The program will check if a PDF with this
               name does not already exist in the folder. If it is, the user will have to choose another name.
               After the Pdf are merged, the user can choose to add or not a bibliography at the end of the new document. This bibliography will contain all the name of all the
               PDF added and the page at which they begin in the document. 
  - Split PDF: The user is asked to insert the path of the PDF he wants to split. The program will check if it exists. The user will then be asked to select an empty folder to 
               put the new file. Then the user is asked to select all the pages he wants to wants to retrieve from the PDF. He can select as many pages as he wants. All the pages
               selected will be merged in one new document. The user can repeat this option as much as he wants. 
  - Encrypt PDF: The user is asked to enter the path of the PDF he wants to encrypt. The program will check that this file is a PDF. Then the user will have to enter an owner 
                 password and a user password. The user can repeat this option as much as he wants.
  - New PDF: The user is ask to select a folder in which to create a PDF and enter a name for this new PDF. The program will check if a file with the same does not already exist.
             If yes, the user will have to select another name. The user can choose the number of pages will contain his PDF. 
  - Edit PDF: The user is asked to select a PDF to edit. The program will check if the file is a PDF or not. Then the user has the choice to either edit a new page or edit a page
              that already exists. He can choose to put a title or not. And to add as many lines as he wants. The program will automaticallu put on the next line the content when 
              it reaches the limit on the page. 
  - Show content of the PDF: This option shows all the content which was edited on a PDF. 
  
  Limits of my program:
  If the PDF is encrypted, my program cannot read it and will close.
  If the user does not enter a path of a folder when it is required, the program will not detect the error and when being working it will close.
  The bibliography which is created will fit only one page. I didn't program to add a page. If the bibliography is too long, some content will not be seen. 
  The same problem occurs when editing a page. If the user wants to insert more lines than what a page can fill, some content will not appeir on the page as no additional page will be created.
  
