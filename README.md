# serveur

yum install -y epel-release

yum install -y mc htop 

groupadd sshuser 
usermod -aG sshuser $USER

adduser toto
adduser titi
adduser test

usermod -aG freecult toto
usermod -aG freecult titi
usermod -aG freecult test

