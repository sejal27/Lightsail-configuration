# Configuration Amazon Lightsail server and deploying flask app using Apache2, postgresql, sqlalchemy

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

## Table of Contents
- [Author](#author)
- [Frameworks and Tools Used](#frameworks-and-tools-used)
- [How to Use](#how-to-use)
- [License](#license)

## Author
[Sejal Parikh](https://in.linkedin.com/in/sejalparikh)

## Frameworks and tools used
1. Materialize - for front-end styling
2. SQLAlchemy - connects and interacts with database using ORM
3. Postgresql - Database system
4. Flask - Python web developement framework
5. Amazon Lightsail for deploying

## How to Access
1. Access the app directly using this address: http://ec2-34-200-129-17.compute-1.amazonaws.com/
2. Public Static IP : 34.200.129.17
3. SSH Port : 2200
4. The firewall is configured only to accept connections on port 2200(SSH), 80(HTTP), and 123(NTP)

Steps to Connect:
1. Copy the contents of the RSA file into a .pub file in your /users/<username>/.ssh directory.
2. Using GITBash from the same directory login to the server by this command:
   ssh -p 2200 grader@34.200.129.17 -i grader
3. Enter the passphrase provided to connect to the server.

## License
[GNU General Public License v3](../LICENSE)
