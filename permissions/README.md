# Shell Permissions

Scripts covering Linux file permissions, ownership, and user management.

## Scripts

| File | Description |
|------|-------------|
| `0-iam_betty` | Switches the current user to betty |
| `1-who_am_i` | Prints the effective username of the current user |
| `2-groups` | Prints all groups the current user is part of |
| `3-new_owner` | Changes the owner of the file hello to betty |
| `4-empty` | Creates an empty file called hello |
| `5-execute` | Adds execute permission to the owner of the file hello |
| `6-multiple_permissions` | Adds execute permission to owner and group, and read permission to others for hello |
| `7-everybody` | Adds execute permission to owner, group, and other users for hello |
| `8-James_Bond` | Sets permissions of hello to no access for owner and group, all for others |
| `9-John_Doe` | Sets the mode of hello to rwxr-x-wx (753) |
| `10-mirror_permissions` | Sets the mode of hello to the same as olleh |
| `11-directories_permissions` | Adds execute permission to all subdirectories for all users |
| `12-directory_permissions` | Creates directory my_dir with permissions 751 |
| `13-change_group` | Changes the group owner of hello to school |
| `14-change_owner_and_group` | Changes owner to vincent and group to staff for all files and directories |
| `15-symbolic_link_permissions` | Changes owner and group of symbolic link _hello to vincent and staff |
| `16-if_only` | Changes owner of hello to vincent only if currently owned by guillaume |
