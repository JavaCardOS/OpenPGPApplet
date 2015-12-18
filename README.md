## OpenPGP Applet

====


This project implement the OpenPGP card functionality can used on the A40CR Card that is sold by [JavaCardOS](http://www.javacardos.com). 

OpenPGP is an open standard for signing and encrypting. It enables RSA or ECC sign/encrypt operations using a private key stored on a smartcard (such as ), through common interfaces like PKCS#11.
The AID of the applet should be according to the OpenPGP card standard v2.0.1 

====
You can also get information from [Sourceforge](https://sourceforge.net/projects/openpgp/).

License
===

The upstream project was released under the GPLv2+ and our fork uses
the same license.  All of our changes are released under the same
license.  See the file LICENSE for more information.


 Building
===

There are several ways to build the project:
1) With  [JCIDE](http://javacardos.com/javacardforum/viewtopic.php?f=26&t=43) open this project,  Click "Buid All Packages(F7)" to build the source code and click "Debug" or "Run" you can Debug/run this project using Java Card Simulator. 
2) With Eclipse and eclipse-jcde.
3) ......


Usage
===

Installing Applet to Java Card.
--------------------------
1, Generally, you can using JCIDE to debug/run this project directly.

2, You can also use [pyApduTool](http://javacardos.com/javacardforum/viewtopic.php?f=3&t=38) to Download this CAP file to card and install, select the applet, send APDU to card. 

You can visit "http://javacardos.com/javacardforum/viewforum.php?f=34" to get more informations.
