## The content of this file are arrange in a file name and what they do format.

### [0-hello_world](0-hello_world)
This file execute a script that prints `Hello, World`, followed by a new line to the standard output

### [1-confused_smiley](1-confused_smiley)
This file execute a script that displays a confused smiley `"(Ôo)'`

### [2-hellofile](2-hellofile)
This file execute a script that display the content of the `/etc/passwd` file

### [3-twofiles](3-twofiles)
This file execute a script that display the content of `/etc/passwd` and `/etc/hosts`

### [4-lastlines](4-lastlines)
This file execute a script that display the last 10 lines of `/etc/passwd`

### [5-firstlines](5-firstlines)
This file execute a script that display the first 10 lines of `/etc/passwd`

### [6-third_line](6-third_line)
This file execute a script that display the third like of the file `iacta`

### [7-file](7-file)
This file execute a script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line.

### [8-cwd_state](8-cwd_state)
This file execute a script that writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it

### [9-duplicate_last_line](9-duplicate_last_line)
This file execute a script that duplicates the last line of the file iacta

### [10-no_more_js](10-no_more_js)
This file execute a script that deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders

### [11-directories](11-directories)
This file execute a script that counts the number of directories and sub-directories in the current directory
* The current and parent directories should not be taken into account
* Hidden directories should be counted

### [12-newest_files](12-newest_files)
This file execute a script that displays the 10 newest files in the current directory

### [13-unique](13-unique)
This file execute a script that takes a list of words as input and prints only words that appear exactly once

### [14-findthatword](14-findthatword)
This file execute a script that display lines containing the pattern `“root”` from the file `/etc/passwd`

### [15-countthatword](15-countthatword)
This file execute a script that display the number of lines that contain the pattern `“bin”` in the file `/etc/passwd`

### [16-whatsnext](16-whatsnext)
Tis file execute a script that display lines containing the pattern `“root”` and 3 lines after them in the file `/etc/passwd`

### [17-hidethisword](17-hidethisword)
THis file execute a script that display all the lines in the file `/etc/passwd` that do not contain the pattern `“bin”`

### [18-letteronly](18-letteronly)
This file execute a script that all lines of the file `/etc/ssh/sshd_config` starting with a letter

### [19-AZ](19-AZ)
This file execute a script that replace all characters `A` and `c` from input to `Z` and `e` respectively

### [20-hiago](20-hiago)
This file execute a script that removes all letters `c` and `C` from input

### [21-reverse](21-reverse)
This file execute a script that reverse its input

### [22-users_and_homes](22-users_and_homes)
This file execute a script that displays all users and their home directories, sorted by users

### [100-empty_casks](100-empty_casks)
This file execute a script that that finds all empty files and directories in the current directory and all sub-directories
* Only the names of the files and directories should be displayed (not the entire path)
* Hidden files should be listed
* One file name per line
* The listing should end with a new line
* You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`

### [101-gifs](101-gifs)
This file execute a script that lists all the files with a `.gif` extension in the current directory and all its sub-directories.
* Hidden files should be listed
* Only regular files (not directories) should be listed
* The names of the files should be displayed without their extensions
* The files should be sorted by byte values, but case-insensitive (file `aaa` should be listed before file `bbb`, file `.b` should be listed before file `a`, and file `Rona` should be listed after file `jay`)
* One file name per line
* The listing should end with a new line
* You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`

### [102-acrostic](102-acrostic)
This file execute a script that decodes acrostics that use the first letter of each line
* The `‘decoded’` message has to end with a new line
* You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`

### [103-the_biggest_fan](103-the_biggest_fan)
This file execute a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests
* Order by number of requests, most active host or IP at the top
* You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`