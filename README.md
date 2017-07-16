# Titiksha-website
<img src="http://inspire.smvdu.ac.in/inspire8/SMVDU.png">
                                               
                                               
<p><strong>Repository for Official Website of Titiksha, Technical Festival of SMVDU.</strong></p><br>
<p>Feel Free To Contribute</p><br>
<ins><b>Contribution</b></ins><br>

<b>Installing php:</b><br>
Add the necessary repositories in order to fetch the correct PHP
version. The commands to add and update them are:<br>
$ sudo apt-get install python-software-properties<br>
$ sudo LC_ALL=en_US.UTF-8 add-apt-repository ppa:ondrej/php -y<br>
$ sudo apt-get update<br>
Finally, we need to install PHP 7 together with the driver for MySQL. For this,
just execute the following three commands:<br>
$ sudo apt-get install php7.0 php7.0-fpm php7.0-mysql -y<br>
$ sudo apt-get --purge autoremove -y<br>
$ sudo service php7.0-fpm start<br>


Change Directory To The Project and Use PHP built in server:<br>
Run This Command in Terminal<br>
php -S localhost:8000(any port)<br>


