# Arabic-Phonetic-Keyboard-Linux


This is a quickly put together Arabic phonetic keyboard based off Omar al-Zabir:

http://arabic.omaralzabir.com/home

I'm just here to put my project up for other people to use if they need to.

Note: this keyboard doesn't have third level keys (AltGr). I may add it in the future, I never use them personally. If you want this feature added please let me know. And don't forget to report any issues or mistakes!

# Updates

4/2/2020: Made comma button print the Arabic comma (right to left), also fixed tilde / grave key 

# Install instructions

This has only been tested on ubuntu. However, since this is a basic keyboard layout file, 
it should work just fine on any distro, provided you know what you are doing.

Instructions:

1. Open your keyboard folder. On ubuntu 19.10, this is:

/usr/share/X11/xkb/symbols

2. Then find the file named 'ara' and copy it into the same folder. 
Name this ara_backup or whatever. This is in case you want to restore defaults.

3. Next, download the ara file from here and replace your old ara file. 

4. Reboot (or log in / log out). Now, your qwerty arabic keyboard layout
should be replaced with the phonetic keyboard. If you haven't enabled it,
just add arabic (QWERTY) as you normally would.

# Troubleshooting.

In case something goes wrong and you can't boot into your GUI,
use the command line to delete 'ara' and rename ara_backup as 'ara'.

Good luck!

PS. Yes, it's possible to make a separate new layout based on this but 
I am too lazy, and I replaced my qwerty layout.

