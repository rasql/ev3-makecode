Introduction
============

This tutorial is an introduction on how to program the **LEGO MINDSTORMS EV3**
robot with **Microsoft MakeCode**.

The language MakeCode is a **graphical language** where you assemble blocks to tell the robot what to do.
All the programming is done online **inside a navigator** window (Safari, Firefox, Chrome) and does not 
need any installation of software.

To program the EV3 go to the following site: 
https://makecode.mindstorms.com/#editor 

MakeCode also has a **simulation screen** which allows you to see the result of your program immeditely, 
even without downloading it to the EV3 brick.

Hello world
-----------

It is a tradition for most tutorials to start with a program which 
displays **Hello world** on the screen. Here it is.

.. image:: hello1.png

The program displays a line of text on the line you specifiy. 
Here we display it on line nummer 1, but you have up to 12 lines.
When you run it the simulator dispays this.

.. image:: hello1s.png

Show the mood
-------------

Now let's use the center button to display the mood of the robot.

.. image:: hello2.png

To express a mood you choose from among 12 images showing different types of eyes.
Each image has a different sound associated with it. Choose a mood and test it.

.. image:: hello2b.png

When you press the center button, the robot will display this image.

.. image:: hello2s.png

On start and forever
--------------------

When you create a new project, you have already two blocks on the canvas.
The **on start** and **forever** block.

.. image:: intro1.png

The **on start** block executes all blocks inside exactly once, when the program starts.

The **forever** block is an infinite loop and repeats all the blocks inside until the program stops.

The following program plays a deep tone (Middle C) at the start, 
and then a higher toone (Tenor C) repeatedly every 1 second.

.. image:: intro1b.png

Download a program
------------------

Once you connect the EV3 via a USB cable to your computer, it appears as a hard-disk.

.. image:: ev3_hd.png

In order to download a program to the brick, click on the **Download** button.
If you have a project called **intro** this will download a file called **intro.uf2**.
To install the file on the EV3 you must place the file inside the EV3 disk icon.

.. image:: download.png

Inside the preferences of your navigater you can specify to which folder the files are downloaded.
You can either

- automatically save to the **EV3** drive
- ask each time for the destination


