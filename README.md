# Programming-Practices
• You should validate input before processing to prevent errors or hacks. By validating and processing input you can remove special charactors that would otherwise inject in to your code. Additionally it prevents objects of different types inserted into functions or conditional statments where they shouldn't be (provoking logical errors). 
• a clear and uncluttered mainline this allows code to be easily read and debugged - also it looks nice (:
• one logical task per subroutine this means that you can test the code as you go and when errors arrise you can more easily identify where the bug is
• use of stubs allows you to continue testing code as they are a placeholder for unflished code
• don't use 2 dementional arrays when you should be using dictionaries. and don't use if-elif-elif... when match/switch-case is more appropriate
• writing for subsequent maintenance makes it easier for others to change in the future. Such as comments and easy to understand variable names
• version control allows you to back-track to past versions to recover old code and help identify issues in existing code.
• regular backup allows you to recover lost data or return to un-bugged code if something goes wrong
• exception handling allows the code to deal with errors as you go so you can more easily interprit and identify them (also sometimes errors shouldn't stop the code and rather trigger another event)
• functions are able to return a single data structure or value to help modularise code and keep it easy to read and understand
