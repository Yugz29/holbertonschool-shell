# 🐚 Shell Project – File Permissions and Ownership

This repository contains a set of shell scripts demonstrating file and directory permissions, ownership changes, user identity commands, and group management in Unix-like systems.

---

## 📚 Table of Contents


| File                          | Description                                                                                       |
|-------------------------------|-------------------------------------------------------------------------------------------------|
| `0-iam_betty`                 | Switches user to `betty` using `su betty`.                                                      |
| `1-who_am_i`                  | Prints the current effective username (`whoami`).                                               |
| `2-groups`                    | Displays the groups the current user belongs to (`groups`).                                     |
| `3-new_owner`                 | Changes ownership recursively to user `vincent` and group `staff` in the current directory.     |
| `4-empty`                    | Creates an empty file named `hello` using `touch`.                                              |
| `5-execute`                   | Adds execute permission for the user on the `hello` file (`chmod u+x hello`).                   |
| `6-multiple_permissions`      | Adds execute permission for user and group, and read permission for others on the `hello` file. |
| `7-everybody`                 | Adds execute permission for user, group, and others on the `hello` file.                        |
| `8-James_Bond`                | Changes group ownership of the `hello` file to `school`.                                        |
| `9-John_Doe`                  | Changes group ownership of `/hello` to `school`.                                               |
| `10-mirror_permissions`       | Mirrors the permissions of the file `olleh` onto the file `hello` using `chmod --reference`.    |
| `11-directories_permissions`  | Recursively adds execute permission to all directories and files in the current directory.      |
| `12-directory_permissions`    | Creates a directory named `my_dir` with permissions set to `751`.                               |
| `13-change_group`             | Changes group ownership of `/hello` to `school` (alternative method).                          |
| `14-change_owner_and_group`   | Recursively changes ownership to user `vincent` and group `staff` in the current directory.     |
| `15-symbolic_link_permissions`| Changes ownership of symbolic link `_hello` to user `vincent` and group `staff`.               |
| `16-if_only`                  | Changes ownership of `/tmp/hello` to user `betty`.                                             |
| `_hello`                     | Symbolic link with ownership modified.                                                         |
| `hello`                      | File with various permissions changed in different scripts.                                    |
| `olleh`                      | Reference file for permission mirroring.                                                       |

---
