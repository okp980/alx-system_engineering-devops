su betty = switches the current user to the user betty
id -un =  prints the effective username of the current user.
group =  prints all the groups the current user is part of
sudo chown betty hello = changes the owner of the file hello to the user betty
touch hello = create a hello file
chmod 744 hello = adds execute permission to the owner of the file hello
chmod 754 hello = adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod ugo+x hello = adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello = permision to users only
chmod 753 hello = sets the mode of the file hello to -rwxr-x-wx

