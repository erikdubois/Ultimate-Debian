# Ultimate Debian

You can install a lot of desktops on Debian like on any other distro...almost any.

I installed following iso

http://cdimage.debian.org/cdimage/stretch_di_alpha8/amd64/iso-dvd/


Installing all desktop environments and checking Sardi icons

	LXDE,
	Budgie
	Cinnamon,
	Gnome,
	Gnome classic,
	Gnome on wayland,
	lxqt,
	mate,
	openbox,
	plasma,
	xfce


http://cdimage.debian.org/cdimage/stretch_di_alpha8/amd64/iso-dvd/

of 2016-11-11

XFCE4

![Screenshots](http://i.imgur.com/9Z8XnNn.jpg)

BUDGIE

![Screenshots](http://i.imgur.com/A10P4mo.jpg)

CINNAMON

![Screenshots](http://i.imgur.com/ghnEv9H.jpg)


# Youtube

You can follow my installation of this iso on vmware and see me installing all desktops, installing all icons and changing settings in the various desktop managers. Writing down all the sardi icons I should still make or fix.

https://www.youtube.com/watch?v=5vH5oPsu0jw



# Update your system.

This is my way of working when installing a new operating system.

First upgrade kernel and install drivers.

If everything is still working we can install the software and start customizing the system.


# Kernel

You can run any of these scripts by downloading the zip file from github. Go to the download folder and right-click to Extract here.
Go inside the folder and right-click <b>in a blank space</b> to go to the terminal. Now your terminal is opened in this extracted folder.


	- ./update-to-the-last-stable-4.x-latest.sh 

Do not forget to type "./" in front of the name.


![Screenshots](http://i.imgur.com/MyiDTnB.jpg)




# Software installation

We start the installation script of all the needed software in the same way as above. 

	- ./install-all-needed-software-at-once-latest.sh

Do not forget to type "./" in front of the name.

The best of them 

	Spotify
	Sublime Text
	Variety
	Inkscape
	Plank
	Screenfetch
	Numix Icons
	Google Chrome
	...

Want more scripts then this github is the 'mothership'.

https://github.com/erikdubois/Ultimate-Linux-Mint-18-Cinnamon


# Sardi Icon Theme
-------------------

This icon theme can be downloaded at  sourceforge.

http://sourceforge.net/projects/sardi/

For ease of installation I use the script


	- icons-sardi-vx.sh



More documentation on http://erikdubois.be

Follow the collection on google+.

The most recent pictures can be found there.

https://plus.google.com/u/0/collection/YFP-LB


GNOME

![Screenshots](http://i.imgur.com/HSF0MDK.jpg)





# F  A  Q
--------------------

#What can you do if the script does not execute?

Since I sometimes forget to make the script executable, I include here what you can do to solve that.

A script can only run when it is marked as an executable.

	ls -al 

Above code will reveal if a script has an "x". X meaning executable.
Google "chmod" and "execute" and you will find more info.

For now if this happens, you should apply this code in the terminal and add the file name.

	chmod +x typeyourfilename

Then you can execute it by typing

	./typeyourfilename



------------------------------------
#But that is the fun in Linux.

You can do whatever <b>Y O U</b> want.

Share the knowledge.
------------------------------------



