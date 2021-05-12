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

After cloning/downloading the repository, open the terminal and go to the path where the repository is located on your machine. (Ex .: C:\Users\Audrey\Desktop)

Then access the folder named "rock-paper-scissors", inside there are four files named "client.py", "game.py", "network.py" and "server.py".

To be able to play on your machine, you will need to change the ip address in the "network.py" and "server.py" files. Open the files with the editor of your choice (here we use Visual Studio Code).

![network](https://user-images.githubusercontent.com/52829664/118035280-6396b780-b341-11eb-9f70-a1e926668888.jpg)

![server](https://user-images.githubusercontent.com/52829664/118035293-67c2d500-b341-11eb-8ed6-1d73dfa6d27f.jpg)

After making the change, save the files.

Now, still inside the folder "rock-paper-scissors" in the terminal, you will run the command ```python server.py``` or ```python3 server.py``` (it depends on your system configuration).

To run the client application you will open two other terminals and access the same path that was used to reach the server application, but now the command used will be  ```python client.py``` or ```python3 client.py``` (it depends on your system configuration).

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
