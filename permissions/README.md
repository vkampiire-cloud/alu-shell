# Shell Permissions

Scripts for managing file permissions and ownership in Linux.

0-iam_betty - switches to user betty
1-who_am_i - prints the effective username
2-groups - prints all groups the current user belongs to
3-new_owner - changes the owner of hello to betty
4-empty - creates an empty file called hello
5-execute - adds execute permission to the owner of hello
6-multiple_permissions - adds execute for owner and group, read for others
7-everybody - adds execute permission for all users
8-James_Bond - sets hello permissions to only other users have access
9-John_Doe - sets hello permissions to rwxr-x-wx
10-mirror_permissions - sets hello permissions to match olleh
11-directories_permissions - adds execute to all subdirectories
12-directory_permissions - creates my_dir with permissions 751
13-change_group - changes the group of hello to school
14-change_owner_and_group - changes owner to vincent and group to staff for all files
15-symbolic_link_permissions - changes owner and group of symbolic link _hello
16-if_only - changes owner of hello to vincent only if owned by guillaume
