# Centos

# systemctl status firewalld
firewall-cmd --permanent --add-service=http
firewall-cmd --permanent --add-service=https
firewall-cmd --permanent --add-port=122/tcp
firewall-cmd --reload
firewall-cmd --list-all-zones

dnf install bind bind-utils +enable +start named
dnf install httpd +enable +start
dnf install perl-CGI

# need transform to code

#2


Updated on 2024-06-09

Updated on 2024-06-13

Updated on 2024-06-14

Updated on 2024-06-16

Updated on 2024-06-19