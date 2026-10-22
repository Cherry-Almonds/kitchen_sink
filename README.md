Purpose of these files is for enumeration of OSCP exam. 

# smb.sh
* Can be run for unauth and auth mode. Unauth requires a domain name and ip address. 
* Auth requires credentials.
* Should be run everytime you get a new user, on every box, every time you get a new user.

# ldap.sh
* Can be run in unauth and auth mode.
* Auth requires credentials
* should be run against a dc controller or any device with ldap enabled.

# kerberos.sh
* Requires ip address, credentials (password or hash), and a domain name
* Requires connection to the domain controller

# file_collecter.sh
* For linux boxes where you have an initial shell. Looks for important files.
* Will find all files owned by relevant users and sort them.
* Highlights files that are likely to have exposed credentials

