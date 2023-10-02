## summary of 5weeks.

### <I/O Redirection>    
* standard output:
 use ' > ' to create and save the output in a file and use ' >> ' appends output to an existing file.
 cat: displays the content of a text file.
* standard input:
use ' < ' 
can mix ' > ' and ' < ' in a single line

#### <Expansion>
- echo: print out the text
- echo* = ls
- echo~ : show the home directory of current user.

### <Permission>
**File permission is very important in Linux.** 

ex)
-rwx rwx rwx | root root

r is read, w is write, and x is execute
-/d  is file tyoe, - indicates regular file and d indicates directory.
filw owner/ group owner/ other users.

ex) chmod 600 some_files

chmod changes permission.
600: 6 = 110 = rw- for owner / 0 = 000 = --- for group / 0 = 000 = --- for others.

* superuser has all system administration.
* put sudo if you're superuser.
