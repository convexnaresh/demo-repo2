# Header
Trying with another repo, built first locally!

//Comments from Naresh

use fgets instead of scanf #because fgets is more secure than scanf that can cause buffer overflow
use sprintf instead of printf to print and format output. #becuase it is more secure.
use memset immediately after malloc; like this:
  int *p=malloc((sizeof (int))*5);
  memset(p,0, (sizeof (int))*5);


define strings such as "print", "add", "remove" as constant string at the top. //brings changability in the program

#points to cover in video
1. C compiler used. For eg. GNU C compiler prevents compiling and executing programs with potential buffer overflow issues.
2. Program is build with Address Sanitizer (ASan) to prevent some of the memory leak errors.
3. Tool such as Valgrind used to check memory leaks and other initialization problems in the program
4. Talk about defining string constants that make the program more maintainable and changable.
