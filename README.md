
# Item Catalog
This is the last project for the Udacity Full Stack Nanodegree. The Item Catalog project consists of developing an application that provides a list of items within a variety of categories, as well as provide a user registration and authentication system.

A user does not need to be logged in in order to read the categories or items uploaded. However, users who created an item are the only users allowed to update or delete the item that they created.

This program uses third-party auth with Google. Some of the technologies used to build this application include Flask, Bootsrap, Jinja2, and SQLite.

## Configuration:
- To access through ssh, use : ``` ssh grader@159.89.3.54 -i ~/.ssh/grader -p 2200```
-  URL to my hosted web application: ```http://mycomdot.ml```
-  grader private key:``` -----BEGIN OPENSSH PRIVATE KEY-----
b3BlbnNzaC1rZXktdjEAAAAABG5vbmUAAAAEbm9uZQAAAAAAAAABAAABFwAAAAdzc2gtcn
NhAAAAAwEAAQAAAQEAstODSBwivcV6lFcbyul7/kIVcVXsgzs/fOc9J3OFpscCTinwYhQr
KG5beSzWwjOH1nHAaZ4bzjJpPccz1xZlhbdngsr6pio1xC3snLPxwQEdjfetF1IVScZWst
HemQUyugC8rCJnFdk8ncEDNLxjJ6H9oWpdsy00MbmVgvElOaBeo6+14O3Ey/dZI3dgqGQq
Qn5ULJFSHYUtHmaE0gNqbcQqxYHTePlRTuJ/SJk0Fe7EO15XusNkAPeMubh7jFgqPWlwrF
b8dC5Rp+ziYqMB08lUagK3hKOP3B13XPaRjs53BBG+WsJo7zoDqK+7kMAF4v7EN4C5nBwX
ybF938rhKQAAA9hpE0jOaRNIzgAAAAdzc2gtcnNhAAABAQCy04NIHCK9xXqUVxvK6Xv+Qh
VxVeyDOz985z0nc4WmxwJOKfBiFCsoblt5LNbCM4fWccBpnhvOMmk9xzPXFmWFt2eCyvqm
KjXELeycs/HBAR2N960XUhVJxlay0d6ZBTK6ALysImcV2TydwQM0vGMnof2hal2zLTQxuZ
WC8SU5oF6jr7Xg7cTL91kjd2CoZCpCflQskVIdhS0eZoTSA2ptxCrFgdN4+VFO4n9ImTQV
7sQ7Xle6w2QA94y5uHuMWCo9aXCsVvx0LlGn7OJiowHTyVRqAreEo4/cHXdc9pGOzncEEb
5awmjvOgOor7uQwAXi/sQ3gLmcHBfJsX3fyuEpAAAAAwEAAQAAAQAJBrwdq63lPk6Npkf0
2gw0LUm/ysKBbUArIdDoaOBaJrlrEJrdmH8FL2zWlPjSHJ/Cp0M7EYv9wHWndKKdPLgrI7
LJ200DjiXgnSDQWBTf1RqUy+ekwbPpYWWG6Sj/OE/zK45acfIaHDj/DXsH8mpe2cJfn2rT
XHjB+cgeL+XdHrGG/4nRZMZcHGUaQIl9ZBbfF4PNkkVWEcyFLfxBCzfTdfoJjFZa8mQoOQ
p6CxHNQ1uKIVgSd9ZQy0IuAQwKbAOfuO5lzD9t+Tsawqo7LfEo/hQkFVBQtPjQWPgXvqKI
2wmidWyXRsire86P8bezyNr2UDOSUzxE1Sk92w6N0w+xAAAAgQC+sH84EASq9tlAdaMjC+
QAdCZZWx9rrCsZHkik03EbkmgxQLnSzvWnsK8tbYQZ0X8YxU9dckRrLAoa92bc+R3/NTZ5
cLd8TpXba50NCpjtGe89ITO0fU319uyVbA6QJb2d78P6hqMWMwBiYrbubPMacNk81gvy6m
gRdp6APJMvnwAAAIEA4YYafekco7L87pDT2zv17ej54Q8u8mSTsGwZ+t24G0D3Ov9wrQWl
71D0X6F1gWtqPZcyqBMZRle1oiOBiBUf6MdXTo2Kvjz8PGJ2dkpmzRwcdREp1635EeHBUa
7Osy5WkBuudPoGV3+dSaM/+geimrySG1CHShLVSueKoWy0X1sAAACBAMr97RGC6jjdVLY1
VicrnKX4cVfKQ4DRdwNuUCR/A7w9YHouM9Pa99MV+4j4vd36SuMVFsaTjPUPmPrlNd04ER
gAZdukAqEZvK3hplN/TYO8YKKB57O5xymtc/Lbwii1eUHM6RY/WfGvpxfVvmjjJs1XtUI+
q4mIi/rF9ZxN0QzLAAAAIW1obWRhbHNrckBtaG1kcy1NYWNCb29rLVByby5sb2NhbAE=
-----END OPENSSH PRIVATE KEY-----```

- sudo password : ```rootroot ``` 

## PreRequisites:
my project created by python3 in the backend and HTML (Bootsrap) the frontend and SQLite is my database
### Configuration changed

- Created new user grader with sudo privileges.
- Changed Timezone to UTC.
- Installed and updated the required software.
- Changed SSH port to 2200.
- Configured UFW to allow connections only on SSH (port 2200), HTTP (port 80), and NTP (port 123).

### Software Installed
- Ubuntu
- Apache2
- mod_wsgi
- python3
- pip
- Flask
- SQLAlchemy
- oauth2client



### Helpful  Resource 
- [FLASK HELLO WORLD APP WITH APACHE WSGI] (https://www.bogotobogo.com/python/Flask/Python_Flask_HelloWorld_App_with_Apache_WSGI_Ubuntu14.php)
- [Start / Stop / Restart Apache Web Server Via SSH](https://www.cyberciti.biz/faq/restart-apache-via-ssh/)
- [SQLAlchemy ORM Tutorial for Python Developers](https://auth0.com/blog/sqlalchemy-orm-tutorial-for-python-developers/)
- [Python](https://www.python.org/)
