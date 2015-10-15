# بسم الله الرحمن الرحيم
In the name of Allah, Most Gracious, Most Merciful

# Quran Image Generator
Using primary source fonts originating from the King Fahed Glorious Qur'an Printing Complex in Saudi Arabia. <em>As seen on Quran.com</em>

# Required Perl modules
* GD
* GD::Text::Align
* DBI
* DBD::SQLite2

# Original Authors/Contributors
* Ahmed El-Helw
* Nour Sharabash
* Bassem Shama

# About this Fork
The original fork was made to be used in *NIX systems. I have a Windows machine and needed to use the project and thus this fork.

# Installation
* Install a perl distribution. I used ActiveState's [ActivePerl](http://www.activestate.com/activeperl) after encountering some issues with Dwimperl. Being a perl noob and handicapped on a Windows machine, I decided not to go debugging.
* Install the required perl modules using ppm.
* Open a (Windows) command prompt in the project folder directory and execute commands to generate your required ayaat/pages. I was not able to run it in a bash emulator but then again I'm a novice.

# Usage
```perl
perl generate.quran.ayah.pl --width 162 --em 1.62 --batch
```

or,
```perl
perl generate.quran.ayah.pl --width 262 --em 1.38 --sura 2 --ayah 255
```

etc...

# Examples
**Note**: The links of examples from the original project are dead. I might add some to this fork later on.

# TODO
* From the original repo: Refactor and improve generate.ayah.pl
* Check if all the functions with folder links are edited to work in Windows. Currently only single ayaat and pages have been tested but that too not extensively.

# License
The code is copyleft GPL (read: free) but the actual fonts and pages (in the 'data' directory) belong to the [King Fahed Glorious Qur'an Printing Complex in Saudia Arabia (http://www.qurancomplex.com)