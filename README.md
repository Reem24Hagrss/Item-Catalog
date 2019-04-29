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

### The DataBase Used :##
The database named `restaurantmenuwithusers` and includes three tables :
> * The `user` table includes information about the users.
> * The `restaurant` table includes the resturant which favourite for this user.
> * The `menu_item` table includes the menu item in each restaurant.

## Steps Required : ##
(For windows user install git in the first)
> * Install Virtual Machine.
> * Install Vagrant.
> * Download the VM Configuration  and unZip the file .
> * Open the terminal inside the unzip directory .
> * Change terminal with `cd` inside the vagrant directory .
> * Run `vagrant up` command to open the VM.
> * Run `vagrant ssh` command to log  into the VM.
> * Install python3 `sudo apt-get install python3`.
> * Install pip3 `sudo apt-get install pip3`.
> * Install sqlalchemy `sudo pip3 install sqlalchemy`.
> * Install Flask `sudo pip3 install flask`.
> * Open the terminal in the app folger.
> * Creating the database `python3 database_setup.py`.
> * Adding some elements to database `python3 lotsofmenuitem.py`.
> * Run the applecation `python3 project.py`.
> * Open browser in `http://0.0.0.0:5000/`.

### View JSON endpoints: ##
> * JSON APIs to view Restaurant
    ``/restaurant/JSON``.
> * JSON APIs to view Restaurant Information 
    ``/restaurant/<int:restaurant_id>/menu/JSON``.
> * JSON APIs to view Menu Item Information
    ``/restaurant/<int:restaurant_id>/menu/<int:menu_id>/JSON``.

### Downloading Links : ###
1- [Virtual Machine](https://www.virtualbox.org/wiki/Download_Old_Builds_5_1).
2- [Vagrant](https://www.vagrantup.com/).
3- [VM Configuration](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5acfbfa3_fsnd-virtual-machine/fsnd-virtual-machine.zip).
