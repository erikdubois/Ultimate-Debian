# Ultimate Debian

Let us first take a screenshot of the initial look of Debian

![Screenshots](http://i.imgur.com/RFfsxm6.jpg)

Update your system.

This is my way of working when installing a new operating system.

First upgrade kernel and install drivers.

If everything is still working we can install the software and start customizing the system.


#1 Kernel

You can run any of these scripts by downloading the zip file from github. Go to the download folder and right-click to Extract here.
Go inside the folder and right-click <b>in a blank space</b> to go to the terminal. Now your terminal is opened in this extracted folder.


	- ./update-to-the-last-stable-4.x-latest.sh 

Do not forget to type "./" in front of the name.


![Screenshots](http://i.imgur.com/46pHNmX.jpg)




#2 Software installation

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




# Sardi Icon Theme
-------------------

This icon theme can be downloaded at  sourceforge.

http://sourceforge.net/projects/sardi/

For ease of installation I use the script


	- icons-sardi-latest.sh



More documentation on http://erikdubois.be

Follow the collection on google+.

The most recent pictures can be found there.

https://plus.google.com/u/0/collection/YFP-LB


Some Examples!


Sardi Flexible has a script. Type a colour code and 3 seconds later all your icons have changed.

Colour codes can be figured out locally with gpick or online via http://www.colorpicker.com/.

![Screenshots](http://i.imgur.com/T9gN544.jpg)



This is the original colour of Sardi Flexible with Minty-transparent theme.



![Screenshots](http://i.imgur.com/iS6zFFU.jpg)

Sardi Arc

![Screenshots](http://i.imgur.com/IeZFWvs.jpg)




# Surfn
--------------------------------- 

This icon theme is based on an older one i.e. yltra flat also on github.

This is an exercise in changing the directories from scalable/... to 22x22/...

Super Ultra Flat Numix Remix will be updated not the Yltra Flat icon set.


For ease of installation I use the script

	- icons-super-ultra-flat-numix-latest.sh

Also the older icon set can be installed via

	-icons-yltra-flat-latest.sh



![Screenshots](http://i.imgur.com/i1FGsR9.jpg)



![Screenshots](http://i.imgur.com/EocrQ70.png)



# Aureola Conky
---------------

This is an exercise in writing conky configurations in lua syntax.

At https://github.com/erikdubois/Aureola you can check out these conky's.

![Screenshots](http://i.imgur.com/y92Jrp4.png)


![Screenshots](http://i.imgur.com/97Q8RO1.jpg)


![Screenshots](http://i.imgur.com/VgD9SqN.png)



# Plank
------------------
Start plank from the menu. <b>CTRL + Right-click</b> on the plank and choose preferences
and put in on top. I choose a transparent theme.

But there are more themes out there if you want.

If you want to autostart this everytime.
Type in the menu " startup". Start 'startup applications'.

Add application and choose plank or do it the old way and point to /usr/bin/plank.

![Screenshots](http://i.imgur.com/arie1IY.jpg)

A tutorial has been written here : 

http://erikdubois.be/install-plank-linux-mint-17-3-set-preferences-add-themes-autostart/




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



