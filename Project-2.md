# Project 2 Documentation


## Project-2 LEMP STACK IMPLEMENTATION


`Installing the Nginx Web Server`


![Sudo apt update and Install Nginx](./Images/Sudo-apt-Install-Nginx.new.PNG)


`Verify nginx successfully installed and running`


![Sudo apt update and Install Nginx](./Images/Sudo-Systemctl-status-Nginx-Running.new.PNG)


`Confirm Server Running and Accessible locally`


![Curl localhost](./Images/curl-localhost-in-ubuntu-shell.PNG)


`Test nginx running on internet`


![test nginx running on internet](./Images/test-nginx-running-on-internet.PNG)


## Installing MYSQL


`Install MYSQL Server`


![Sudo apt install mysql-server](./Images/sudo-apt-install-mysql-server.PNG)


`login to MYSQL console`


![Sudo mysql](./Images/sudo-mysql.PNG)


`test login to mysql`


![login to mysql](./Images/test-login-to-mysql-server.PNG)


## Installing PHP


`Install php-fpm-mysql`


![Install php-fpm-mysql](./Images/sudo-apt-install-php-fpm-php-mysql.PNG)


## Configuring NGINX to Use PHP Processor


`Create root web directory`


`Assign Ownership of the directory`


`Open new Configuration file in Nginx`


![Create Root Web Directory](./Images/create-root-web-directory-projectlemp.PNG)


`Activate configuration by linking to the config file from Nginx`


![Activate configuration](./Images/Activate-test-nginx-configuration.PNG)


`Nginx working confirmation`


![Nginx Confirmation](./Images/echo-message-nginx-ok.PNG)


## Testing PHP with NGINX


`Create test PHP file in document`


![test PHP](./Images/testing-php-with-nginx.PNG)


## Retrieving Data from MYSQL Database


`Create a New Database`


`Create a New User and grant access`


![New Database](./Images/create-newuser-grant-access.PNG)


`Test if New User has proper permission`


![User Permission](./Images/run-show-databases-command.PNG)


`Insert Content to the Database Table`


![insert Content to DB Table](./Images/show-insert-database-todo-list.PNG)


`Create PHP Script`


![Create PHP Script](./Images/php-site-info.php)


`Access todo list on internet`


![Access todo list](./Images/access-todo-list-web-browser.PNG)


`Remove PHP site`


![remove PHP site Data](./Images/remove-php-site-info.php)


`Reload site`


![reload site](./Images/reload-website.PNG)