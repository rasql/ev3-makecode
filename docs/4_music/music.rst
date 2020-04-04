Music
=====

The EV3 brick can produce sounds.


Play a melody
-------------

Let's program the musical score of *Frère Jacques* a popular French song.

.. image:: jacques.gif

We start the first measure when pressing the center button.

.. image:: music1.png

To select the note to play, just click on the name, for example *Middle C*,
and select another note on the piano scale keyboard.

.. image:: music1b.png

Repeat a melody
---------------

To repeat a part of the melody, place it inside a loop. 
For exemple the first measure needs to be repeated twice.

.. image:: music1c.png

Longer and shorter notes
------------------------

So far our notes had a duration of one beat.
We can increase to the duration to two beats, which is required in the second mesure.

.. image:: music1d.png

The next measure has 4 notes with only half a beat.

.. image:: music1e.png

The last measure has long note again.

.. image:: music1f.png

Change the tempo
----------------

The next part allows you to change the tempo.
The tempo of the music is measured in **beats per minute** (bpm).
Let's make a program to display the inital tempo.

.. image:: music2a.png

When you run the simulation you see that the temp is 120 bpm.

.. image:: music2b.png

Now let's program two buttons to increase and decrease the tempo.

- The **up** button makes the tempo faster by 20 bpm (beats per minute).
- The **down** button decreases it by 20 bpm.

.. image:: music2c.png

Change the volume
-----------------

To keep track of the volue we need to create a variable.

.. image:: music3.png

We can **set this variable** to 5 in the **start** block.
The we set the volume using this variable.
And finally we display its value on line number 4.

.. image:: music3b.png

Finally we program the **left/right** buttons to increase or decrease the volume.

.. image:: music3c.png





