###  
- (서버 재구축 후 데이터 복원 전) 사용자 계정 생성
- 
~~~
$ sudo mkdir /mnt/backup
$
~~~
- 사용자 계정 생성  
~~~
$ sudo adduser sunakang
[sudo] password for xman:
info: Adding user `newuser' ...
info: Selecting UID/GID from range 1000 to 59999 ...
info: Adding new group `newuser' (1004) ...
info: Adding new user `newuser' (1004) with group `newuser (1004)' ...
info: Creating home directory `/home/newuser' ...
info: Copying files from `/etc/skel' ...
New password:
Retype new password:
passwd: password updated successfully
Changing the user information for newuser
Enter the new value, or press ENTER for the default
        Full Name []: 신인류
        Room Number []:
        Work Phone []:
        Home Phone []:
        Other []:
chfn: name with non-ASCII characters: '신인류'
Is the information correct? [Y/n] Y
info: Adding new user `newuser' to supplemental / extra groups `users' ...
info: Adding user `newuser' to group `users' ...
~~~
