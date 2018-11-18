# Linux-Server-Configuration
It is a baseline installation of a Linux distribution on a virtual machine and preparing it to host the web applications, to include installing updates, securing it from a number of attack vectors and installing/configuring web and database servers.
  
  IP address: 139.59.90.65
  SSH port : 2200
  URL : http://139.59.90.65.xip.io/
  
  
# Setup the server .
1. Make a droplet in digital ocean.
2. Paste the ssh keys on the droplet and start it.
3. Connect to the server using root@your-ip-address


# Secure your server.
4. Update the packages.
5. Change the SSH port from 22 to 2200. 
6. Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
7. Create a new user named grader.
8. Give grader the permission to sudo.
9. Disable root login.


# Prepare to deploy your project.
10. Configure the local timezone to UTC.
11. Install and configure Apache to serve a Python mod_wsgi application.
12. Install and configure PostgreSQL:
13. Install flask and other dependencies.
14. Configure and enable a new virtual host.
15. Install git.


# Deploy the Item Catalog project.
16. Clone and setup your Item Catalog project from the Github repository you created earlier in this Nanodegree program.
17. Set it up in your server so that it functions correctly when visiting your server’s IP address in a browser. Make sure that your .git directory is not publicly accessible via a browser!


## References

1 <https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-18-04>
2. <https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps>
3.https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-with-ufw-on-ubuntu-18-04
