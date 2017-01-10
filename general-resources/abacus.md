#Abacus

Abacus is the name of our group's cluster.

Cluster address: `abacus.berkeley.edu`

##Getting Started 

To first get started, you need an account on the computer. 
Email Professor Slaybaugh, Josh, or Kelly (the administators) for an account.

##Software
If you'd like to install a piece of software on the cluster, let one of the
administrators know. 
They will create a group for that piece of software and add the appropriate
users.
Then
- You can create a folder (code name and version) in `/home/software` with the correct group permission.
- Place the source code for the software in that location. 

Note: all users on our sever will be put in the `comp-n` group. 
If you'd like to make something available to everyone, please set the group to
`comp-n`.

##Permission Management
### File Permissions

Every file and folder has an _owner_ and a _group_
association. Different permissions can be granted to the owner, group
and other users. Using the `ls -l` command will show you a string of
10 characters on the left: `drwxrwxrwx`

- The first indicates the type of file it is, `d` here means I'm
  looking at a directory.
- The next three groups of `rwx` stand for the permissions for the
  owner, group, and other users, respectively. 
- `r`: read, `w`: write, `x`: execute

Examples:

`drwx------`: directory with full permissions for the owner

`drwxrwx---`: directory with full permissions for the owner and group
members, this is common for a software directory that has a license
requirment.

`drwxr-xr-x`: full permissions for owner, group/others can read or
execute files. Common for home directories, people can look at your
files and run them in their own directories, but can't write or change
anything in yours.

### Useful commands

`ls -l`: this will show all the files in your current directory with
owners, groups, and permissions.

`id` : this command will show your current user id `uid=xxxx(name)`)
your _current_ group `gid=xxxx(name)`, and all the groups you belong
to `groups=xxxx(name),...`. This is important to keep
track of, as all files you create will automatically set your current
user as the owner, and your current group as the assigned group.

`groups`: shows the groups you are a member of.

`newgrp group_name`: this command opens a new bash session setting your current
group to `group_name`, assuming you are a member of that group. Now
you can make files that are accessible to everyone in that group.

`chgrp group_name file_name`: changes the _group_ ownership of a
file, and _can_ be used by all users.

### Modifying File Permissions

The `chmod` command modifies access permissions on files that you
own. Different permissions can be set for the owner, group, and
others. I recommend using the man page for help: [man page](http://ss64.com/bash/chmod.html)

**need:** 
* directions for software installation and management (where to install and
 build).
