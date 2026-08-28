I made this skin to play all songs from an album when you select that album.

There might still be a few unnecessary files in the skin, but those are things that are not used and will not affect operation.

I like to have the albums presented in a random manner.  This is specified in the line.....

   SortAlbumsBy = Random


The six channel color organ is set to display concentric diamonds that react to the frequencies present in the song.  I have included a second set of images that can replace the concentric diamonds with randomly placed stars.  Those images would have to be specified in the appropriate color organ lines.

IMPORTANT:  Syncronizing the color organ fine adjustment

On my Windows PC, I have added the following line to the fruitbox.ini file in GENERAL AREA.   This is the file in the fruitbox directory and not the MCMLP skin directory:

     SpectrumAudioSyncOffset = 3 Ticks

I find this additional offset gives me the best response.  The built-in offset is close, but can be adjusted using this line by -5 to 5 Ticks.  See the manual for how tick length is related to frame rate.

Finally, there are two other sets of color organ images.  R1, B2, G2...etc are bolder colors.  RedLayerD, BlueLayerD, GreenLayerD...etc are layers of stars that could be used instead of the diamond patterns.  I settled on the more muted diamond pattern to more match the muted color palette that is associated with the mid century modern theme.

Enjoy.


Dermbrian (aka Derm-O-Dyne)



