# APCS1-MASHER

Team Members                                                                                                                     Period
John Park                                                                                                                                          7
Charles Zhang

Team Name
The Doozy Folderol 

Project Title
Masher


Project Idea:
Create a single player musical game
Example of games this is similar to: Smule, Tap Tap, Guitar Hero

Objective of Masher is to have the player press the keys in succession with rhythm to a melody
There will be scoreboard that accounts for:
Streaks
Faults
Double keys
There will be different songs to choose from based on the player’s taste

Critical Features:
1.      Have a way to track multiple keys being pressed at the same time.
a. Chords and other combinations of notes will be implemented requiring the player to hit multiple keys at the same time.
 
2.      Soundtrack.
a. This will be the melody which the player will “play” to.
 
3.      Generating beats and continuous notes.
a.  The issue of whether notes will be randomly generated or created based on the attributes (tempo, pitch, etc) of the soundtrack. 

To be Added Later Features:
Different types of level, for the weak and the athletics
This scoreboard is associated with the audience’s zing, which at the end would give you money
Having cash would allow you to have access to more songs

Developmental Stages:
1.      Create an array of notes designated to a “key” that adds more notes when played.
 
2.      Find a way to generate the graphics for the notes moving down the screen and have a separate symbol for continuous notes.
 
3.      Code the registering of keys pressed/held for periods of time.
 
4.      Figure out some animation to go with pressing the keys correctly with the notes on the screen.
 
5.      Add the soundtrack. If possible match the motion of the notes with the tempo/pitch of the song.
 
6.      Have some sort of background on the screen. Add a homepage/start page. 

The minimum product of this project would be a version that only include one song, and that will have a scoreboard that account for successions with the melody. No homepage or any other features.

Possible Defects: For some reason, clicking play goes directly to playing one of the songs instead of listening out the options. This happens occasionally, and I do not understand why. Charles claims that it works fine on his computer.

LOG

1/20/16: Using the Minim library to play sound files.

1/21/16: Changed the keys to ASD and LEFT DOWN RIGHT keys

1/22/16: Changed the keys to use ASD and JKL


1/23/16 - 1/24/16: Beats now synchronize with the song. Using 2D arraylists and Minim to achive this. From now on refer to masher_minim. Fixed many bugs.

1/25/16: I (Charles) combined the actual game with John's homepage/song selection pages. The keys to play are now just ASDJ. Implemented score system including deduction of points for incorrect playing.


Instruction to compile/run:

First go into APCS1-MASHER/homepage and open homepage.pde.

Then run it. To select songs click on PLAY and then click on any song name.

When playing the song, use the ASDJ keys to hit the beats as they pass through the hitboxes near the bottom. When the song ends your score (+1 for correctly matching with a beat and -1 otherwise) with be displayed along with a button directing you back to the main menu. 



