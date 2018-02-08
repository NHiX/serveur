# serveur

yum install -y epel-release

yum install -y mc htop 

adduser toto
adduser titi
adduser test

groupadd sshuser
usermod -aG sshuser $USER

usermod -aG freecult toto
usermod -aG freecult titi
usermod -aG freecult test

