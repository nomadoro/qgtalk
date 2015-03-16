## Latest version: 0.5.1 ##

qGTalk is a Google Talk client developed with Qt and libgloox. qGTalk functions like the Windows version of Google Talk (currently only text messaging is implemented) but runs on Linux.

### Screenshots ###
![https://lh4.googleusercontent.com/-ndLORTUu0rE/UW4-hbfk-XI/AAAAAAAAAEM/9a2zwBGL0Nk/s144/login.png](https://lh4.googleusercontent.com/-ndLORTUu0rE/UW4-hbfk-XI/AAAAAAAAAEM/9a2zwBGL0Nk/s144/login.png)
![https://lh5.googleusercontent.com/-sfyIwIVRBYo/UW4-hdZ1HwI/AAAAAAAAAEM/v84RwrAyr4Y/s144/mainb.png](https://lh5.googleusercontent.com/-sfyIwIVRBYo/UW4-hdZ1HwI/AAAAAAAAAEM/v84RwrAyr4Y/s144/mainb.png)

### Main features ###
  * instant messaging
  * roster retrieval and management
  * conversation history management
  * encryption of local settings file
  * exporting/importing settings
  * exporting/importing conversation history

### Dependencies ###
  * g++
  * GNU Make
  * GnuTLS (development package)
  * Qt 4.5 or higher (development package)
  * [gloox](http://camaya.net/gloox/) 1.x (development package)
  * [crypto++](http://www.cryptopp.com/) (development package)

### Installation ###
  * tar zxf qGTalk\_xxx.tar.gz
  * cd qGTalk\_xxx
  * qmake qGTalk.pro (OR: qmake-qt4 qGTalk.pro)
  * make
  * (sudo) make install

The default installation path is /usr/local/bin. A shortcut should also appear in the "Applications" menu (or equivalent).

### Notes ###
  * Since version 0.5, qGTalk uses a new format for settings and history files, which is unfortunately not compatible with previous versions. But this new format is designed to be compatible with future releases.
  * If you are building gloox from source code, please make sure that the GnuTLS development package is already installed before you invoke the "configure" command.