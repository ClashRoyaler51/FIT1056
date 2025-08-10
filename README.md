# How this code works 
This file will contain information regarding the MSMS.py file uploaded, providing how each segment/fragment works in regards to the code. 

# Fragment 1 (Inputs)
This fragment defines a student and a teacher variable which allows the code to use the users input to create variables and store their information for later use. 

# Fragment 2 (Foundations)
Fragment 2 creates actions or tools to utilise such as;     
- list_students
- list_teachers
- add_teachers 
- find_students 
- find_teachers

This fragment lays the foundation for the core functions that will be implemented later on

# Fragment 3 (Core functions)
This part of the code does the behind the scenes functions for the main menu such as finding student/teacher ids, enrolling students with their instruments etc. this fragment utilises the other 2 fragments to create the music school system. These core functions include; 
- find_student_by_id
- front_desk_register
- front_desk_enroll
- front_desk_lookup

With these functions set up, the rest of the code is ready to be finished.

# Fragment 4 (Main menu)
This section creates the "Menu" that the user will see and interact with. This will show the options that the user can do, and depending on which option they choose, perform different actions. The user will need to input an integer between 1-5 or the letter "q" to quit for the code to work.

# How to use the code
To use the code provided, the user must run the code and then use the options displayed in the terminal, and then provide an integer for the options, or provide the letter "q" to quit the program. If an empty space is inputed, the program will ask for a valid option. If a false id is given, program will ask for a valid id.
