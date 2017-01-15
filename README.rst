========
vimp3tag
========

``vimp3tag`` is a script that allows you to specify a list of ``mp3`` files
from the command line, and then edit it using your configured ``$EDITOR``
(``vim`` by default).

.. code-block:: bash

    vimp3tag edit ~/Music/Amy\ Winehouse\ -\ Back\ to\ Black\ \(2006\)/

This will bring up a file that looks like this: 

.. code-block:: none

    1|Amy Winehouse|Rehab|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/01 Rehab.mp3
    2|Amy Winehouse|You Know I'm No Good|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/02 You Know I'm No Good.mp3
    3|Amy Winehouse|Me & Mr. Jones|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/03 Me & Mr. Jones.mp3
    4|Amy Winehouse|Just Friends|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/04 Just Friends.mp3
    5|Amy Winehouse|Back To Black|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/05 Back To Black.mp3
    6|Amy Winehouse|Love Is A Losing Game|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/06 Love Is A Losing Game.mp3
    7|Amy Winehouse|Tears Dry On Their Own|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/07 Tears Dry On Their Own.mp3
    8|Amy Winehouse|Wake Up Alone|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/08 Wake Up Alone.mp3
    9|Amy Winehouse|Some Unholy War|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/09 Some Unholy War.mp3
    10|Amy Winehouse|He Can Only Hold Her|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/10 He Can Only Hold Her.mp3
    11|Amy Winehouse|Addicted|/home/techhat/Music/Amy Winehouse - Back to Black (2006)/11 Addicted.mp3

The lines in this file are pipe-delimited, with the fields being track number,
artist, title, and filename, in that order. All fields are editable except for
the filename, as it is used for the script to know which files to edit.
