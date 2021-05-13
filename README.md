# Rock, paper, scissors game
Project made for the discipline of computer networks, using sockets, threads and multiclients

## How to play?
First of all, you will need to install Python (if you don't already have it on your system), here we use version 3.9.5 but any version >= 3 is ok, for more details on how to install see the [language website](https://www.python.org/downloads/).

After that, you will need to install ```pygame``` library (if you don't already have it on your system). You can do the installation using the ```pip``` installer package, which is already built into python 3. 

Open your terminal and type ```pip install pygame```. (in some cases you need to use the command ```pip3 install pygame```)

If all goes well, you will receive a message of successful installation in the terminal.

With the library installed, you will now clone this repository on your local machine, using the following command through the terminal: 
```
git clone https://github.com/audreyemmely/rock-paper-scissors.git
```
If you do not have Git installed on your machine, you can download the repository in "zip" format, just click on the green button named "Code" (top right) and choose the option "Download ZIP". After that, unzip the file and follow the next instructions.

After cloning/downloading the repository, find where the repository is located on your machine and open the folder named "rock-paper-scissors". Inside there are four files named "client.py", "game.py", "network.py" and "server.py".

To be able to play on your machine, you will need to change the ip address in the "network.py" and "server.py" files. Open the files with the editor of your choice (here we use Visual Studio Code).

To find the address that you should use in the server variable simply open cmd > type "ipconfig" > copy the IPV4 Address. Do this on whatever machine will be running the server script.

After making the change, save the files.

Now, using the terminal go to the path where the folder is located on your machine (Ex.: C:\Users\Audrey\Desktop\rock-paper-scissors).

After access the folder "rock-paper-scissors" in the terminal, you will run the command ```python server.py``` or ```python3 server.py``` (it depends on your system configuration).

To run the client application you will open two other terminals and access the same path that was used to reach the server application, but now the command used will be  ```python client.py``` or ```python3 client.py``` (it depends on your system configuration).

## About the files
### client.py

### game.py

### network.py
It's a basic class capable of connecting to the server and sending/receiving information about the state of the player. 

### server.py
The server is responsible for handling all of the different clients that are playing our game. It will store and send information to each of clients appropriately.


[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
