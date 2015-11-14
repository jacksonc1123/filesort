# Filesort
Sorts files from given directory by file extension (linux)

## TODO: 
* Add fancy output (if needed)
* Add flags 
* Add create destination directory option 
* Add ability to sort directory other than current working directory 
* Add verbose output 
* Customize output 

# usage:
```
filesort [-h] [-e EXT] [-f] [PATH] [DEST]

positional arguments:
  PATH                  sort this directory (default is current directory)
  DEST                  move files to this directory (ignored if sorting
                        entire folder)

optional arguments:
  -h, --help            show this help message and exit
  -e EXT, --extension EXT
                        sort by this file extension
  -f, --force           create destination directory if it doesn't exist
```

