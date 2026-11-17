# Linux Lesson 3: File Permissions

## What I Learned

Linux file permissions control who can access files and what they can do with them.

### Types of Permissions

- Read (r): Allows reading a file.
- Write (w): Allows modifying a file.
- Execute (x): Allows executing a file.

### User Categories

- Owner (u): The person who owns the file.
- Group (g): Users belonging to the file's group.
- Others (o): Everyone else.

### Commands Practised

- `ls -l` — Displays file permissions.
- `chmod` — Changes file permissions.

### Practical Exercise

I created a file called `test.txt` and ran:

chmod 600 test.txt

The result was:

-rw-------

This means the owner can read and write the file, while the group and others have no permissions.

### Why It Matters

File permissions help protect sensitive files, such as passwords and database credentials, from unauthorized access.
