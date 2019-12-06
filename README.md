1 - Download visual studio code -> https://code.visualstudio.com/

2 - Download Xampp or any other lamp stack -> www.apachefriends.org

3 - Launch the lamp stack machine

4 - Create index.php with phpinfo(); to see information  

5 - Go to xdebug website in the wizard section -> https://xdebug.org/wizard

6 - copy all the phpinfo page ( ctrl+a ctrl+c) then copy inside the wizard 

7 - follow the instructions on the website

8 - on the php.ini , you need to add these two command 

xdebug.remote_enable = 1
xdebug.remote_autostart = 1 

DONT FORGET TO RESTART THE APACHE
