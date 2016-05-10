This repo is forked from Demirten's work. I've made some changes to support Ubuntu 14.04 (LTS)

# twamp-gui

Cross platform twamp client with Qt QML backend

You must have a working Qt5 - QML Development environment, it is not tested with Qt4.

Support OS `Ubuntu 14.04.4 LTS \n \l`

## Build on Linux

It is tested on Debian Jessie and newer versions. You need to install following packages:

```
$ sudo apt-get install qt5-default qtdeclarative5-dev qml-module-qtquick-controls \
  qml-module-qtquick-dialogs qml-module-qtquick-layouts qml-module-qtquick-window2 \
  qml-module-qtquick2 
```

If you are facing problem with Ubuntu, try install the Development Package for Ubuntu
`sudo apt-get install ubuntu-sdk`

After that you need to follow standard build process of Qt applications:

```
$ qmake
$ make
```

Once completed, you have 2 binary files in

```
responder/twamp-responder
client/twamp-client
```

You may need root privilege to start the responder.

## Build on Windows

Install latest Qt5 development kit and build the project.

## Build on Mac

Install latest Qt5 development kit and build the project.

## Precompiled Binaries

You can download precompiled binaries for several platforms:
https://github.com/demirten/twamp-gui/releases

## Screenshots

You can look at the screenshots on project page: http://demirten.github.io/twamp-gui/#screenshots
