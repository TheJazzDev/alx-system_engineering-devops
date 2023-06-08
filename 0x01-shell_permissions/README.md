## The content of this file are arrange in a file name and what they do format.

### [0-iam_betty](0-iam_betty)
This file execute a script that switches the current user to the user `betty`

### [1-who_am_i](1-who_am_i)
This file execute a script that prints the effective `username` of the current user

### [2-groups](2-groups)
This file execute a script that prints all the `groups` the current user is part of

### [3-new_owner](3-new_owner)
This file execute a script that change the owner of the file `hello` to the user `betty`

### [4-empty](4-empty)
This file execute a script that create an empty file called `hello`

### [5-execute](5-execute)
This file execute a script that adds execute permission to the owner of the file `hello`

### [6-multiple_permissions](6-multiple_permissions)
This file execute a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`

### [7-everybody](7-everybody)
This file execute a script that adds execution permission to the owner, the group owner and the other users, to the file `hello`

### [8-James_Bond](8-James_Bond)
This file execute a script that sets the permission to the file `hello` as follows:
     - Owner: no permission at all
     - Group: no permission at all
     - Other users: all the permissions

### [9-John_Doe](9-John_Doe)
This file execute a script that sets the mode of the file `hello` to `rwxr-x-wx`

### [10-mirror_permissions](10-mirror_permissions)
This file execute a script that sets the mode of the file `hello` the same as `olleh`’s mode

### [11-directories_permissions](11-directories_permissions)
This file execute a script that adds execute permission to all subdirectories of the `current directory` for the `owner`, the `group owner` and all `other users`

### [12-directory_permissions](12-directory_permissions)
This file execute a script that creates a directory called `my_dir` with permissions `751` in the working directory

### [13-change_group](13-change_group)
This file execute a script that changes the group owner to `school` for the file `hello`

### [100-change_owner_and_group](100-change_owner_and_group)
This file execute a script that changes the `owner` to `vincent` and the `group owner` to `staff` for all the files and directories in the working directory

### [101-symbolic_link_permissions](101-symbolic_link_permissions)
This file execute a script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively