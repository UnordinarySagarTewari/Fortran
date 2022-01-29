# Fortran
Some Fortran Code
Making sense of what we just wrote:

LINE 1 program helloworld : This indicates the start of the program "helloworld" 

LINE 2 If we don't declare a variable type, Fortran treats a variable with a name that begins with a letter from i to n as integer, and all others as a real number. 
       It is recommended to use implicit none if you don't need that behaviour.

LINE 3 character*14 hello_string : This declares an array of characters which is called hello_string.

LINE 4 hello_string = "HELLO WORLD!!!" :This assigns the value "Hello, world!" to the declared array. !: This marks an inline comment.

LINE 5 write (*,*) hello_string : This prints the value of hello_string to the standard output. The first * means to write to standard output, as opposed to some file. The second * means not to use any special formatting.

LINE 6 end program helloworld : This indicates end of the program.

# Fortran Editors
Here’s a list of the most popular text editors that support Fortran syntax, in alphabetical order:
Atom

Emacs

NotePad++

SublimeText

Vim and Neovim

Visual Studio Code

A comprehensive list with more choices is provided in fortranwiki.org.
