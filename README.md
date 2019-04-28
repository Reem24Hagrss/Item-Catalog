# ***Item Catalog*** 
    Item Catalog is one of the udacity's Full Stack Web Developer Nanodegree projects.
    and the application provides a list of items within a variety of categories .
    and provide a user registration and authentication system. 
    Registered users will have the ability to add, edit and delete their own items.

## Technology used :
    I build this project using :
        1- Linux Virtual Machine (using Vagrant and VirtualBox to install and manage the VM).
        2- Python DB-API (to write my code).
        3- sqlalchemy (for creating and connecting to database)
        4- Flask 
        5- Oauth2 (for login)

### The DataBase Used :
The database named `restaurantmenuwithusers` and includes three tables :
1- The `user` table includes information about the users.
2- The `restaurant` table includes the resturant which favourite for this user.
3- The `menu_item` table includes the menu item in each restaurant.

## Steps Required : 
(For windows user install git in the first)
1- Install Virtual Machine.
2- Install Vagrant.
3- Download the VM Configuration  and unZip the file .
4- Open the terminal inside the unzip directory .
5- Change terminal with `cd` inside the vagrant directory .
6- Run `vagrant up` command to open the VM.
7- Run `vagrant ssh` command to log  into the VM.
8- Install python3 `sudo apt-get install python3`.
9- Install pip3 `sudo apt-get install pip3`.
10- Install sqlalchemy `sudo pip3 install sqlalchemy`.
11- Install Flask `sudo pip3 install flask`.
12- Open the terminal in the app folger.
13- Creating the database `python3 database_setup.py`.
14- Adding some elements to database `python3 lotsofmenuitem.py`.
15- Run the applecation `python3 project.py`.
16- Open browser in `http://0.0.0.0:5000/`.
### View JSON endpoints:
1- JSON APIs to view Restaurant
    ``/restaurant/JSON``.
2- JSON APIs to view Restaurant Information 
    ``/restaurant/<int:restaurant_id>/menu/JSON``.
3- JSON APIs to view Menu Item Information
    ``/restaurant/<int:restaurant_id>/menu/<int:menu_id>/JSON``.

### Downloading Links : ###
1- [Virtual Machine](https://www.virtualbox.org/wiki/Download_Old_Builds_5_1).
2- [Vagrant](https://www.vagrantup.com/).
3- [VM Configuration](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5acfbfa3_fsnd-virtual-machine/fsnd-virtual-machine.zip).