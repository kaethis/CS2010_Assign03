------------------------------------------
    _            _              ___ _____ 
   / \   ___ ___(_) __ _ _ __  / _ \___ / 
  / _ \ / __/ __| |/ _` | '_ \| | | ||_ \ 
 / ___ \\__ \__ \ | (_| | | | | |_| |__) |
/_/   \_\___/___/_|\__, |_| |_|\___/____/ 
                   |___/                  
------------------------------------------
Author: 	Matt W. Martin, 4374851
		kaethis@tasmantis.net

Project:	CS2010, Assignment 03
		Dictionary III (Linked-List Implementation)

Date Issued:	27-Oct-2014
Date Archived:	[REDACTED]

Comments:	This lab consists of just one program: dict 

		- dict: This program will read either a text file or input and build
			a "Dictionary" of words based on that file or user input.
			This Dictionary will contain not only each word, but also the
			frequency of each unique word.

			NOTE: By default, this Dictionary can store a maximum 100
			      words.

		To read from a file, execute like so:		$  ./dict < TEXT.txt
		(Where "TEXT" is the name of your file.)

		Otherwise, the program will request input from the user as soon as
		the program executes: it will interpret the each word from the input
		and add them to the Dictionary before printing its contents on the
		screen.

		ATTENTION: Unlike previous versions of dict, this program does NOT
			   sort the words alphabetically.  See Notes.

MAKE:		./dict		Creates the dict program described above.
		./clean		Removes dict program.
		./archive	Creates a .tar in parent-directory (../).
		
GIT Repository:			https://github.com/kaethis/CS2010_Assign03.git

Notes (Optional):	- I could not, for the life of me, sort my Linked List.
			  Seeing as how I cannot allot any more time to the project,
			  the Dictionary will not be sorted.  Sorry.
