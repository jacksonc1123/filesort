# Filesort
Sorts files from given directory by file extension (linux)

# usage:
```
usage: filesort [-h] [-e EXT] [-f] [-s SRC] [-d DEST]

sorts files in directory by file extension.

optional arguments:
  -h, --help            show this help message and exit
  -e EXT, --ext EXT     sort by this file extension
  -f, --force           create destination directory if it doesn't exist
  -s SRC, --src SRC     sort this directory (default is current directory)
  -d DEST, --dest DEST  move files to this directory (ignored if sorting
                        entire folder. If left unspecified, default
                        destination folders will be used)
```

Example: 
```
filesort -e .mp3 -s /home/bob/miscdir -d /home/bob/music
```
# TODO:
* Option specify additional extensions when doing full sort
* Maybe add a config file
* Change format of the destination folder list 

