# Linux Server Configuration

The objective of this project is to turn a brand-new, bare bones, Linux server into the secure and efficient web application host your applications need.
To complete this project,  I used Amazon EC2 for the Linux server instance. I created a new user account named grader and give grader the permission to sudo.

The information of my Linux server is as follows:
1. The IP address is 3.14.14.218 and SSH port is 2200
2. The complete URL of my hosted web application is http://ec2-3-14-14-218.us-east-2.compute.amazonaws.com/
3. Summary of software I installed and configuration changes made:
   i. Database Postgresql
      Installed Postgresql and created a new database user named catalog that has limited permissions to your catalog application database
   ii. Server Apache2 wsgi
      Installed and configured Apache to serve a Python mod_wsgi application
   iii. Installed python3 and git
4. '/home/grader/.ssh' is the location  of the SSH key for the grader user.
5. The list of third-party resources to complete this project:
   - [How to deploying python flask on apache2 ubuntu 16.04](https://www.youtube.com/watch?v=wq0saslschw)
   - [mod_wsgi](https://docs.webfaction.com/software/mod-wsgi.html)
   - [WSGIPythonPath](https://modwsgi.readthedocs.io/en/develop/configuration-directives/WSGIPythonPath.html)
   - [Virtual Environments](https://modwsgi.readthedocs.io/en/develop/user-guides/virtual-environments.html)
