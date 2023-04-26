<h1>ALX Software Engineering Shell Project</h1>

<p>This is a collaboration project in which we were tasked to create a replicate of the Bash shell.</p>

<h2>Requirements</h2>
<h3>General:</h3>
<p>Allowed editors: vi, vim, emacs
<br>All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89.
<br>All your files should end with a new line
<br>A README.md file, at the root of the folder of the project is mandatory
<br>Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
<br>Your shell should not have any memory leaks
<br>No more than 5 functions per file
<br>All your header files should be include guarded
<br>Use system calls only when you need to (why?)
<br>Write a README with the description of your project
<br>You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository. Format, see Docker</p>

<h3>Output:</h3>
<p>Unless specified otherwise, your program must have the exact same output as sh (/bin/sh) as well as the exact same error output.
The only difference is when you print an error, the name of the program must be equivalent to your argv[0] (See below)</p>

<h4>Example of error with sh:</h4>

<p>$ echo "qwerty" | /bin/sh
<br>/bin/sh: 1: qwerty: not found
<br>$ echo "qwerty" | /bin/../bin/sh
<br>/bin/../bin/sh: 1: qwerty: not found
$</p>

<h4>Same error with your program hsh:</h4>
<br>$ echo "qwerty" | ./hsh
<br>./hsh: 1: qwerty: not found
<br>$ echo "qwerty" | ./././hsh
<br>./././hsh: 1: qwerty: not found


<h3>List of allowed functions and system calls</h3>
<p>access (man 2 access)
<br>chdir (man 2 chdir)
<br>close (man 2 close)
<br>closedir (man 3 closedir)
<br>execve (man 2 execve)
<br>exit (man 3 exit)
<br>_exit (man 2 _exit)
<br>fflush (man 3 fflush)
<br>fork (man 2 fork)
<br>free (man 3 free)
<br>getcwd (man 3 getcwd)
<br>getline (man 3 getline)
<br>getpid (man 2 getpid)
<br>isatty (man 3 isatty)
<br>kill (man 2 kill)
<br>malloc (man 3 malloc)
<br>open (man 2 open)
<br>opendir (man 3 opendir)
<br>perror (man 3 perror)
<br>read (man 2 read)
<br>readdir (man 3 readdir)
<br>signal (man 2 signal)
<br>stat (__xstat) (man 2 stat)
<br>lstat (__lxstat) (man 2 lstat)
<br>fstat (__fxstat) (man 2 fstat)
<br>strtok (man 3 strtok)
<br>wait (man 2 wait)
<br>waitpid (man 2 waitpid)
<br>wait3 (man 2 wait3)
<br>wait4 (man 2 wait4)
<br>write (man 2 write)<p/>
                              
