# Ansible-Playbooks

### Project1

This is a simple playbook for Apache web server.
In this playbook three modules are used 
 - yum
 - copy
 - service

These modules are used for Installing httpd,copying file to the correct location and
 starting the service of httpd respectively.


### Project2

This Playbook contains Multiple plays ,it's an extension of the previous playbook 
in this playbook First play will update the Apache and firewalld package to it's 
latest version .
In the second play the web server is being tested .

Modules Used :
 - yum
 - copy
 - service
 - firewalld
In the second play :
 - uri
