# LinuxGame
A small Linux SSH based game for OSC's Salakhana event

## Setting Up the game 

*Preferabely use root to set up everything first*
*Can be hosted on a dedicated Virtual Machine*

* First install openssh server and client(use yum for Fedora family)
```
$ sudo apt-get install openssh-server openssh-client
```
* Restart/start the ssh service 
```
$ sudo /etc/init.d/ssh restart
```
* To run the game on your system you need to create the following users and add the levels in the repositories to their home folders respectively (will be updated)

| Level | Username | Password | 
|-------|----------|----------|
|Level 1|  user1   |  user1   |
|Level 2|  user2   | ThisIsTheFlag|
|Level 3|  thisistheusername | 0f90af52378de424313acdb34de1e16f |
|Level 4 |   nmapisuseful   |  depends on the hosting computer  |

>Test the open ports and change it for the fourth username before the game starts

>If you want to change the contents of the file leading to the third level you have to change the password of the third level 
>Because the md5sum of the .txt will change

* The player is provided with the first username and password

