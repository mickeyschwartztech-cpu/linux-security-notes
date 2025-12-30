md
#  Linux Permissions

## Concepts
-users
=people 
-groups 
= collections of users, like a team 
-others
= everyone else on the computer who isn'y you or your group 
-read / write / execute
= what they are allowed to do with files ( look at them, change them, run them )

## Permission Notation 
-Symbolic: 
-rwx 
- r = read, w = write, x = execute
Numeric values:
- 4 = read, 2 = write , 1 = execute
-Example:
- 7 = 4+2+1 = read + write +execute
- ( rwxr-- file.txt ) :
- First rwx = owner can read/ write / execute
- rwxr-- = group can only read
- r-- = others can only read 
- 

## Common Comands 
-1s -1 shows files and their permissions 
-chmod changes permissions 
-chown changes file owner 
-groups shows whitch groups you're in 
-id shows your user info 

## Examples 
chmod 755 file.sh - owner full access, groups & others read/execute 
chmod u+x script.sh - adds execute permission to the owner 
chown user: group file - changes file owner and group

## What I learned 


