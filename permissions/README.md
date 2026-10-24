# Shell permissions

Scripts for practicing Linux users, groups, and file permissions.

- 0-iam_betty: switches the current user to betty.
- 2-groups: prints all the groups the current user belongs to.
- 3-new_owner: changes the owner of the file hello to betty.
- 4-empty: creates an empty file called hello.
- 1-who_am_i: prints the effective username of the current user.
- 5-execute: adds execute permission to the owner of the file hello.
- 6-multiple_permissions: adds execute permission to the owner and group, and read permission to other users, for the file hello.
- 7-everybody: adds execute permission to the owner, group, and other users for the file hello.
- 8-James_Bond: sets no permissions for the owner and group, and all permissions for other users, on the file hello.
- 9-John_Doe: sets the permissions of the file hello to 753 (rwxr-x-wx).

- 10-mirror_permissions: mirrors the mode of olleh on hello.
- 11-directories_permissions: adds execute permission for all users to subdirectories of the current directory, leaving regular files unchanged.
- 12-directory_permissions: creates a directory named my_dir with permissions 751 in the working directory.
- 13-change_group: changes the group owner of the file hello to school.
- 14-change_owner_and_group: changes the owner to vincent and the group to staff for all files and directories in the current directory.
- 15-symbolic_link_permissions: changes the owner and group of the symbolic link _hello to vincent and staff, without changing its target.
- 16-if_only: changes the owner of the file hello to vincent only if it is owned by guillaume.
