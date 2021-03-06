# LukeBook  
> Announcement: The LukeBook-OTG project is moved to [LukeWon.com Git](https://git.lukewon.com)  
  
[![Join the chat at https://gitter.im/LukeBook/Lobby](https://badges.gitter.im/LukeBook/Lobby.svg)](https://gitter.im/LukeBook/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) 
[![Github All Releases](https://img.shields.io/github/downloads/LukeWonDotCom/LukeBook/total.svg)](https://github.com/LukeWonDotCom/LukeBook/archive/master.zip)  

This is the source code for [LukeBook](www.lukewon.com/lukebook) made by [Luke Won](@lukecywon)  
**Default Admin Username**: ``root``  
**Default Admin Password**: ``root``  
  
## **Requirements**  
1. Mysql Server  
2. Phpmyadmin (_Must be this_)  
3. Php server  
4. **The Php server must have short open tags enabled**  
  
## **Installation (Composer)** ``Recomended``  
* Log on to your server using ssh
* Go to your desired installation folder
* Run ```composer create-project lukecywon/lukebook```

## **Installation (Git)**  
* Log on to your server using ssh
* Go to your web server location (ex: /var/www)
* Run ```git clone https://github.com/LukeWonDotCom/LukeBook.git```
* Rename the ```LukeBook``` folder to your desired name (ex: html)

## **Installation (Zip)** ``Hardest way``  
* Download the zip from [here](https://github.com/LukeWonDotCom/LukeBook/archive/master.zip)
* Unzip/move the files into a folder in your webserver  
* Go to **phpmyadmim** and import ``lukebook.sql`` to your desired database  
* Open the folder and edit db.php  
* Replace 'Your-hostname', 'Your-Username', 'Your-Password' and 'Your-DB' with your real Database info (Only Mysql database will work)  
* Go to ``'_your-webserver/where-ever-you-put-the-files/index.php_'`` and login  

## License  
[View License](https://github.com/LukeWonDotCom/LukeBook/blob/master/LICENSE)  
