# Omnis-Dynamic-MySQL-DAM

These MySQL dams are used to establish secure SSL connections to the MySQL database. Created using Omnis Studio tech note: https://www.omnis.net/developers/resources/technotes/tnsq0039.jsp


These MySQL dams are "Universal" MacOS binaries, meaning they will work on both Intel and ARM macOS Omnis clients.


Download the 4 files:
- libcrypto.1.1.dylib
- libssl.1.1.dylib
- libmysqlclient.21.dylib
- libmysqlclient.dylib

and place them into the following locations into your Omnis .app. Note, if the lib folder does not exist, simply create it.


- xxx.app/Contents/lib/libcrypto.1.1.dylib
- xxx.app/Contents/lib/libssl.1.1.dylib 
- xxx.app/Contents/Frameworks/libmysqlclient.21.dylib
- xxx.app/Contents/Frameworks/libmysqlclient.dylib 
