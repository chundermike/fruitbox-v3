# fruitbox-v3
Retro Audio/Video Jukebox for Raspberry Pi and Windows

fruitbox is a customisable video and audio player for the Raspberry Pi and Windows PCs, allowing the user to create the look and feel of classic jukeboxes.

It's an updated version of fruitbox v2, re-coded to use SDL3 and gstreamer.  Enhancements over v2 are:

 - 64-bit Raspberry Pi and 64-bit Windows versions
 - Capable of playing many audio and video file formats
 - Multiple display monitor support
 - Multicast Tx and Rx modes
 - Karaoke lyric support
 - Audio visualisers
 - Enhanced display object rendering (pseudo 3d)
 - Easy installation
 - Plus lots of other improvements and minor enhancements

Installation is as follows:

<b>Raspberry Pi (version 4 or 5 recommended):</b>
1. Ensure latest version of the 64-bit Trixie Desktop OS is installed
2. Download the <code>fruitbox_3.02.02_arm64_portable.deb</code> file and save it to the Desktop
3. Open a command line terminal and type:<br>
    <code>sudo apt install ~/Desktop/fruitbox_3.02.02_arm64_portable.deb</code><br>
4. Ignore any Notices about <i>"Download is performed unsandboxed..."</i>
5. fruitbox is now installed and can be run from a command line by typing <code>fruitbox</code>

<br>For first time installations, skins can be downloaded from the fruitbox menu (TAB).  Running this download option any other time will check for updated or new skins.<br><br>

Note that fruitbox, its fruitbox.ini file, user guide and the sample skins are stored in <code>/opt/fruitbox/</code><br><br>
By default, fruitbox looks for your music files in your Music directory <code>$HOME/Music</code>. If they are somewhere else, you will need to edit the <code>/opt/fruitbox/fruitbox.ini</code> file and change the <code>MusicPath</code> setting.<br><br>
<b>Windows (10/11, 64-bit):</b>
1. Download and run the <code>fruitbox_3.02.02_win64_setup.exe</code> file
2. Follow the installation instructions
3. Run fruitbox using the desktop shortcut

<br>Let's Rock!
