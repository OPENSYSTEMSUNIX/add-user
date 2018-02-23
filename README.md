# add-user

Update the root password with the supplied value.

### Variables
- `password:`       #hash of password
- `name:`           #default root
- `shell:`           #default shell
- `groups:`          #groups
- `comment:`         #user comment

### how to generate passwords

`$ sudo pip install passlib` 

`$ python -c "from passlib.hash import sha512_crypt; import getpass; print sha512_crypt.encrypt(getpass.getpass())"` 

Enter the password when prompted. The output will be a hash that is usable for the password varible.
