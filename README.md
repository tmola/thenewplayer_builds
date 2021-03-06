![Image text](logo.png)



# Home Page
[https://sudormroot.github.io/thenewplayer_builds/](https://sudormroot.github.io/thenewplayer_builds/)

# Supported platforms

Linux and macOS

# Download
## macOS:
[https://github.com/sudormroot/thenewplayer_builds/releases](https://github.com/sudormroot/thenewplayer_builds/releases)
## Linux:
[https://github.com/sudormroot/thenewplayer_builds/releases](https://github.com/sudormroot/thenewplayer_builds/releases)


# Linux
For Linux deepin/ubuntu

install
tar xzvf thenewplayerfree.xxx.tgz
dpkg -i thenewplayerfree.xxx.deb

Fix Chinese language problem in Linux:
sudo ln -s /usr/local/thenewplayerfree/languages /usr/local/thenewplayerfree/bin/languages

No sound problem:
Please do a google search with 'linux qt no sound' and fix the problem by installing extra libraries.


# Motivations

Watching IPTV programs is hard in macOS platform, since most existing applications are built merely for Windows or Android. That is the first motivation why I develop this application for macOS. The graphic rendering is based on OpenGL, which is responsible for automatically renderring frames onto the computer screen. The decoding library is from FFMPEG, the front-end UI library is from QT.

The second reason why this project is built is that receiving analog TV programs with GNU SDR (Software-defined Radio) is fascinating, if I can build a software to do so, that would be a wonderful experience, in a sense, we can reflect our past again - the pre-ditigal times where we were living ever.

# Features
* Hardware decoding, compared with mpv/VLC, the CPU usage is only 1/2 of them.
* Support IPTV program list files ending with m3u, m3u8 and txt
* Support 6 audio channels while mpv/VLC can not work correctly.



# ~~Install via brew~~

Ref: https://brew.sh

~~brew search thenewplayerfree~~

## ~~Install from brew (not working currently)
brew cask install thenewplayerfree
* according to the policies of brew, the stars need to be above 50 at least, otherwise the project will not be accepted to be in the repo of brew cask. Once the stars are 50, I'll add thenewplayerfree to brew again.~~

## ~~Uninstall~~
~~brew cask uninstall thenewplayerfree~~

# FAQS
## Why the OpenTV does not provide IPTV source file?
The OpenTV is merely a player for playing the content offered by your content providers. For this reason, based on copyright laws or codes, the OpenTV software would not provide any channel source files or contents. From your side, you also have the obligatory to obey the laws or codes in your areas or countries.


## How to setup the IPTV channel list?
1. Download IPTV source txt or m3u or m3u8 files to local.
2. Drag the txt or m3u or m3u8 channel list file to the player's window directly.
3. The player will automatically recognize the channel file format and build the IPTV channel.


# Troubleshooting

## Remove all configuration files, and navigation channel lists.
1. cd ~/.config/thenewplayer
2. rm -rf \*.txt upgrade objectstate playstate
3. Reboot the player.

## No sound in Linux
Please go to preferences->audio, choose the audio output device to 'pulse' for example -- you might need related libraries as well. This might fix the problem.


# Screenshots

![screenshot0](screenshots/screenshot0.jpg)

![screenshot1](screenshots/screenshot1.jpg)

![screenshot2](screenshots/screenshot2.jpg)

![screenshot3](screenshots/screenshot3.jpg)

![screenshot4](screenshots/screenshot4.jpg)

![screenshot5](screenshots/screenshot5.jpg)

![screenshot6](screenshots/screenshot6.jpg)

![screenshot7](screenshots/screenshot7.jpg)

![screenshot8](screenshots/screenshot8.jpg)

![screenshot9](screenshots/screenshot9.jpg)


