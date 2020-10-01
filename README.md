# ET2598-Assignment-2-Network Automation
In this assignment, you are to implement a simple web service. The service is really simple, and the content is shown below.
<?php echo date("Y-m-d H:i:s") . " Welcome to " . gethostname() . "|" .$_SERVER['SERVER_ADDR'] .":" . $_SERVER['SERVER_PORT'] ."<br>\n"; ?> 
This line is to be stored in the main index.php file of a webserver, 
furthermore, the server should serve content from the "/var/www/html" folder. 
The webserver that you are to use is Nginx, and it should be deployed on a Ubuntu 18.04LTS or Ubuntu 20.04LTS (preferred). 
For the service to work properly, you need to install the following packages; nginx, php, and php-fpm. 

