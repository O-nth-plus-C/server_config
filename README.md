# server_config

#Access
The server is located at ip address 54.202.137.18.

It can be accessed using the grader user on port 2200.

The application can be accessed at 54.202.137.18.xip.io

The server runs mod_wsgi on apache2. PostgreSQL is used for the database. 

Software Installed:
pip
apache2
PostgreSQL
mod_wsgi

Configurations Made:
ssh port changed to 2200 from default
ports other than 80, 2200, and 123 are blocked for incoming communication
root login is disabled
grader user is added, and given sudo access

Third-party resources:
AWS
Stack-overflow
