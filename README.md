docsetbuild
===========

<code>docsetbuild</code> is a command line script for building XCode (and Dash) docsets manually based on reference .html files written in PHP.

You can install it with an one-liner:

<code>curl https://raw.github.com/vis7mac/docsetbuild/master/install | /bin/sh</code>

If you don't want to install it to the system bin directory (which requires a <code>sudo</code> call), you can also navigate to the directory you want to download it to and make

<code>curl https://raw.github.com/vis7mac/docsetbuild/master/docsetbuild > docsetbuild;chmod u+x docsetbuild</code>

The usage of it can be found when running <code>docsetbuild</code> without params.

arduinobuild
===========
<code>arduinobuild</code> is a fork of this project and shows how you can manipulate .html files, fetch images from servers and get names out of the files.
That's not so special, because you can do all that with PHP.
If you want to create your own fork which creates another specific docset you could get inspired by this one.

License
===========
Both scripts are released under GNU General Public License (GPL) and are free to use and to modify however you want.