Some notes on this album-only skin.  I am thrilled that fruitbox now supports displaying *random* albums on every screen.  It's a fantastic way select and "put a record on" for the evening, and helps me keep listening to things that I might not if I was limited to media players in alphabetical order.

1) When you select an album, all of its tracks are added to the queue (assuming FREEPLAY or enough credits).

2) The record player is my own non-working Stewart Warner 1948 Hi-Fi's turntable.

3) For variety, you can load up a few albums and then use SHUFFLE QUEUE (whatever key is assigned on your jukebox) to make a nice mix.

4) I've included a built-in screensaver, with a few photos and artworks that kicks in after some time when there is no record playing, the queue is empty, and no buttons have been pressed for awhile.  It will select random images from images that you place in the screensaver folder.  If you want only one image....put only one picture in there.  If you don't want any screensaver, comment out (put a # in front of...) the last six lines of the fruitbox.cfg file.

5) I like the record drop.  If you want to not have the record drop at all, find and comment out (put a # in front of...) the following lines of the fruitbox.cfg file:

   [status] 				# Load Record Video
   Video = LPchanger.mp4 100
   Position = 20 738
   Size = 590 329
   Contents = status_load.txt

6)  If you don't want the record drop, you can also set SongLoadTime = 0 Seconds in the [general] parameters at the start of the skin.  As it exists, that's at a rather lengthy six secons.  It has to be that long to allow the initial record drop.  Sorry.  


Enjoy.  