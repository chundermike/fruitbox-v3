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
2. Download the <code>fruitbox_3.00.00_arm64_portable.deb</code> file to the Desktop
3. Open a command line terminal and type:<br>
    <code>cd ~/Desktop</code><br>
    <code>sudo apt install ./fruitbox_3.00.00_arm64_portable.deb</code><br>
4. Ignore any Notices about <i>"Download is performed unsandboxed..."</i>
5. fruitbox is now installed and can be run from a command line by typing <code>fruitbox</code>

Note that fruitbox, its fruitbox.ini file and the sample skins are stored in <code>/opt/fruitbox/</code><br>

<b>Windows (10/11, 64-bit):</b>
1. Download and run the <code>fruitbox_3.00.00_win64_setup.exe</code> file
2. Follow the installation instructions
3. Run fruitbox using the desktop shortcut


<br>V3 is largely compatible with V2 skins, but you may find some tweaks are required, notably for font sizes

Let's Rock!
