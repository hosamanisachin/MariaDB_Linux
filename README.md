System: CentOS

on Terminal
sudo systemctl start mariadb.service
<Nothing is printed on the terminal>

sudo mysql_secure_installtion
<root password - No>
<remove anonymous users - No>
<disallow root login remotely - No>
<remove test database and access to it - No>
<reload privilage tables now - No>
<DONE !!!>


To start MariaDB
mysql -u root -p
*if there is error : Can't connect to mysql server* then use the below command and run above command again
sudo systemctl start mariadbserver.
