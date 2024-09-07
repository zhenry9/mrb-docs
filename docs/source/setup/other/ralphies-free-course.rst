Ralphie's Free Course
=====================

.. figure:: ../../img/ralphies-free-course-signal-flow.png

	Signal flow of the free course.

The free course on Ralphie's is a self-timed, non-homologated race course for the public. It is designed to operate without staff at the start or the finish. A start controller box at the start controls the start interval using red and green lights. Timing is handled internally in the :ref:`Alge Self Timer` display board. All that is needed is to connect the start (with controller) and finish to the display board.

.. contents:: Table of contents
	:local:

The Start
---------

.. figure:: ../../img/ralphies-free-course/free-course-start.jpg

:Equipment Needed:
	.. include:: ../../equipment/kits/free-course-start-kit.rst
	
Mount the start controller on bamboo between the start wand and the hill wire timing box. It is important to use an automatic returning start wand since this start will be unstaffed. Use one of the long pigtails to connect the start block to one of the leads on the self-timer start controller. Trench this wire under the snow to protect it from accidental disconnection. Use the other long pigtail to connect the other start controller lead to the hill wire box. Use the Time 1 plug.


The Finish
----------

.. figure:: ../../img/ralphies-free-course/free-course-finish.jpg

:Equipment Needed:
	.. include:: ../../equipment/kits/non-homologated-finish-kit.rst
	
The finish should be setup following the normal procedure for non-homologated races. Only one finish beam is needed. It can be a photocell pair, or a photocell and a reflector. A photocell and reflector works fine on sunny days, but a pair of photocells will be more resistant to problems if there is wind or snow.

.. figure:: ../../img/ralphies-free-course/free-course-finish-close.jpg

	Finish line setup using a photocell and reflector.

Use a :ref:`Hand Spool` to connect the photocell to the timing box on the lift tower, and trench the wire in. There are two pairs in the timing box. Remember which one you connect to.

Dye the finish line.


Timing Shack
------------

.. figure:: ../../img/ralphies-free-course/ralphies-shack-area.jpg

:Equipment Needed:
	- :ref:`Alge Self Timer`
	- A variety of :ref:`pigtails <Pigtail>`
	
Since all of the timing functionality is contained within the self-timer display board, the setup needed inside the timing shack is minimal. You just need to connect the start and finish to the display board itself. This can be accomplished by jumping a few connections on the Ralphie's shack timing board. 

The start signal is coming in on the 'Time 1' pair of the hill wire. Find this output on the left side of the timing board. Use a pigtail to jump it to the 'Time 1' input for the free course on the right side of the board. The start is now connected to the self-timer. The finish signal is coming in on either one of the two finish pairs. These should come out of the timing board on round plugs with banana plug jumpers already attached. Remember which one you plugged into on the lift tower, and plug it into the self-timer 'finish' input on the timing board. If you aren't sure just plug in both.

.. figure:: ../../img/ralphies-free-course/ralphies-shack-board.jpg

	The Ralphie's shack board with the correct connections made for the free course.
	
	
Testing and Troubleshooting
---------------------------

There should be at least someone at the start and someone inside the shack to effectively test. It is also helpful to have someone at the finish if possible.

The first step is to get a green light on the start controller. If you have no light, the connection between the start controller and the selftimer is broken somewhere. If the light stays lit red it is likely a polarity problem. Oftentimes swapping the polarity of the banana plug in the hill wire box will solve it. You can also try changing polarity inside the timing shack. If this doesn't work, double check your connections at the start and in the timing shack. Double check the functionality of the hill wire.

Once everthing is setup correctly, the start controller should show a green 'Go' light. When the wand is opened it will turn red for 10 to 15 seconds, then green again. The self-timer supports multiple racers on course.

Check that the timer starts counting up when the wand is opened, and stops on a finish impulse. If there is someone at the finish have them give you an impulse with their hand. If not, you can use a shorting bar to give an impulse in the shack. Just make sure to test the finish after.

If you have persistent trouble, start checking the condition of the display board and the wires connected to it. They have likely been outside year-round and may have been damaged by the sun or by lightning. If you have doubts about the timing wire connecting the self-timer display board to the timing board inside the shack, run a new one. Run a hand spool that you are confident in out the door and make the connection directly.

If you still can't get it to work, bring the display board and the start controller inside the Hilton and test it there. If it works inside the Hilton, look for trouble with the hill wires on Ralphie's. If it doesn't, the self-timer likely needs service. 