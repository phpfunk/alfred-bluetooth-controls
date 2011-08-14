Bluetooth Controls for Alfred
============

An AppleScript so you can browse and send files to devices via Bluetooth from [Alfred App](http://alfredapp.com/). You will need Alfred and the Powerpack to use this.

Installation
----------------

To install Bluetooth Controls in Alfred double click on the extension file: Bluetooth Controls.alfredextension

How to use
----------------

Once installed with Alfred you can run the following commands


    bt start  					::  To open or activate the Bluetooth Utility (can also use 'bt init')
    bt quit   					::  To quit the application (can also use 'bt end' or 'bt kill')
    bt send  					::  Open the bluetooth controls to choose a file to send
    bt send /FILE/   			::  To open the bluetooth controls to choose a device to send the file to
    bt send /FILE/ to DEVICE  	::  To automatically send the specified file to the specified device
    bt browse					::	Open the bluetooth controls to select a device to browse
    bt browse DEVICE   			::  Open the specified device to browse
      

Examples
----------------
    $ bt send
    $ bt send /Users/phpfunk/Music/sample.mp3
    $ bt send /Users/phpfunk/Music/sample.mp3 to phpfunk's phone
    $ bt browse
    $ bt browse phpfunk's phone
    $ bt kill


Download
----------------
[Bluetooth Controls](http://dl.dropbox.com/u/45930/Alfred%20Apps/Bluetooth%20Controls/Bluetooth%20Controls.alfredextension)
    

## Version History ##
### 1.0.0 - August 14, 2011###
 
- Commit: Initial Release