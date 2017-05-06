
### Run Following Command to install Apache on centos 32 bit 
`` 
sudo yum install httpd mod_ssl

``
### Configure Apache to run automatically

 - After Apache is installed and working, set to start automatically when the server is rebooted.
  + Run the following command:
`` 
sudo /sbin/chkconfig httpd on
``
  + Test to confirm that the setting works.
``
sudo /sbin/chkconfig --list httpd
``
