# Ansible-Playbooks ![Ansible Logo](/assets/ansible_logo.png)

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
 - uri

### Project3

In this playbook we are using variables in place of directly using name of the packages ,services and rules.

variables are defined using vars keyword.
To call a variable anywhere in the playbook we have to use {{variable-name}}.
* vars:
     * variable_name: value
    
