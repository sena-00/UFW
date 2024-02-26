# UFW Install and Configuration - Arch Linux
This is an orientation guide on how to make your Linux more secure with UFW (Uncomplicated Firewall).

## Installation

First, open your terminal and install the package. 

For Ubuntu:
~~~
sudo apt-get install ufw
~~~
For Arch:  

~~~
sudo pacman -S ufw
~~~
After the installation is completed, lets check the status of UFW. As the stardand, UFW will always be disabled after the initial installation. You can check this with:
~~~
ufw status
~~~
