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

Updated on 2024-06-23

Updated on 2024-06-26

Updated on 2024-06-30

Updated on 2024-07-01

Updated on 2024-07-07

Updated on 2024-07-08

Updated on 2024-07-14

Updated on 2024-07-16

Updated on 2024-07-19

Updated on 2024-07-21

Updated on 2024-07-23