# Cplusplus
/* 
1. Summarize the project and what problem it was solving:

The project aimed to create a C++ program for a corner grocery store. By reading data from an input file containing item names and their occurrences, the program provides a menu for users to interact with the data. The users can search for specific items, display item frequencies, create an item histogram, and save the data to a backup file. This project addresses the need for a simple inventory management system for a corner grocery store.

2. What did you do particularly well?
 
   Clear Menu Design: The menu design is clear and user-friendly, providing a straightforward interface for users to navigate through the available options.
   Input Validation: The getUserChoice function incorporates input validation, ensuring that the program handles invalid user inputs

5. Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
   
   Error Handling: Enhancements in error handling could be made to provide more detailed error messages, aiding users in understanding issues when file operations fail. 
   Example: I would like to update input validation to include Case sensitive input and item (s). To validate whether an item being searched is plural or single and to relate them to the same result.
   Modularization: Breaking down the code into smaller, modular functions would improve readability, maintainability, and reusability, facilitating easier debugging and future modifications.
   
7. Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
   
   ‘getUserChoice()’ was difficult due to input validation 
   Public members of the class ‘CornerGrocer’ was difficult due to file opening check and reading and mapping of the input file to the stored map. 
   File Handling: Dealing with file operations, particularly reading from and writing to files, presented challenges. Overcoming this involved consulting C++ documentation, seeking assistance from online forums, YouTube,       and thorough testing to identify and address issues.
   Map Usage: Effectively understanding and using the ‘std::map’ data structure required careful consideration. I figured out these difficulties through a lot of trial and error and by running the program while purposely       trying to crash it. I had to make one small change at a time to see what improved and what got worse. 

9. What skills from this project will be particularly transferable to other projects or coursework?
    
   Input Handling: The input validation approach used in the getUserChoice function is a transferable skill applicable to various projects, ensuring robust user interactions.
   File I/O: Experience gained in reading from and writing to files can be applied to other applications involving data persistence and storage.
   Menu Design: Designing and implementing a user-friendly menu system is a valuable skill applicable to a wide range of interactive programs, enhancing user experience and interaction.
   
11. How did you make this program maintainable, readable, and adaptable?
    
    Comments: Thorough comments provide clarity on the purpose and functionality of each part of the code, aiding maintainability and future understanding.
    Descriptive Naming: Meaningful names for functions and variables contribute to code readability and understanding.
    Modular Design: Breaking the program into modular functions with specific responsibilities enhances maintainability and allows for easier adaptation or expansion.
    Consistent Coding Style: Adhering to a consistent coding style improves readability and supports collaboration with others on the project.
    */
