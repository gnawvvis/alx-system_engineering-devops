**0x01. Shell, permissions**

The script **0-iam_betty** switches the current user to the user *betty*.

The script **1-who_am_i** prints the effective username of the current user.

The script **2-groups** prints all the groups the current user is part of.

The script **3-new_owner** changes the owner of the file *hello* to the user *betty*.

The script **4-empty** creates an empty file *hello*.

The script **5-execute** adds execute permission to the owner of the file *hello*.

The script **6-multiple_permissions** adds execute permission to the owner and the group owner, as well as read permission to other users of the file *hello*.

The script **7-everybody** adds execution permission to the owner, the group owner and the other users of the file *hello*.

The script **8-James_Bond** sets the owner no permissions, the group no permissions and other users all permissions to the file *hello*.

The script **9-John_Doe** sets the mode of the file *hello* to `-rwxr-x-wx`.

The script **10-mirror_permissions** sets the mode of the file *hello* to be the same as the mode of the file *olleh*.

The script **11-directories_permissions** adds execute permission to all subdirectories of the current working directory for the owner, the group owner and all other uses without changing regular files.

The script **12-directory_permissions** creates the directory *my_dir* with permissions `751` in the current working directory.

The script **13-change_group** changes the group owner to *school* for the file *hello*.

The script **100-change_owner_and_group** changes the owner to *vincent* and the group owner to *staff* for all the files and directories in the current working directory.

The script **101-symbolic_link_permissions** changes the owner and the group owner of *_hello* to *vincent* and *staff* respectively. *_hello* is a symbolic link in the current working directory.

The script **102-if_only** changes the owner of the file *hello* to *betty* only if it is owned by *guillaume*.
