Steps to Install Vesta Control Panel (VestaCP) in CentOS 8 x64 System

1) SSH

Enter in Console/Terminal with root (sudo su root) or su root

2) RUN

dnf install -y nano wget perl perl-core psmisc mlocate epel-release; dnf install -y screen dos2unix;

3) INSTALL

cd; wget https://raw.githubusercontent.com/carlosfriascf/vesta8/master/install.sh -O /root/install.sh; unix2dos install.sh; sed -i 's/\r$//' install.sh; sh install.sh;

And done :)

For troubleshooting, contact me by email.:

sys@sysdop.com
