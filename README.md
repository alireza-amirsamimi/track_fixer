# track_fixer
This script adds zero at the start of mp3 music track's name that started with the number less than 10.

1- ...  >> 01- ... 
2- ...  >> 02- ... 
3- ...  >> 03- ... 
4- ...  >> 04- ... 
5- ...  >> 05- ... 
6- ...  >> 06- ... 
7- ...  >> 07- ... 
8- ...  >> 08- ... 
9- ...  >> 09- ... 

## How to insatll this script?

```
$ cd /tmp
$ wget https://raw.githubusercontent.com/alireza-amirsamimi/track_fixer/master/track_fixer
$ chmod +x track_fixer
$ mv track_fixer /usr/local/bin/
```

## How can I use it?
Suppose that you have a directory that contains some music albums in /home/alireza/Music/ and
you want to fix name of tracks.

Just type this in terminal and press enter!

```
track_fixer /home/alireza/Music/
```

track_fixer will find all mp3 in Music directory and all subdirectories and it will fix them.

![](http://s6.picofile.com/file/8382298376/track_fixer.gif)
